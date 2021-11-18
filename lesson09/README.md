**Date**: Nov 18, 2021

**Slides**: https://docs.google.com/presentation/d/1BE2C6eB4YNoVmPFvMLf6_VwGuikXNbE2yLpeab3okQc/edit?usp=sharing

* Transformer architecture
* Hugging Face 
* NLP Tasks, pipeline, Small-E-Czech

**Assignment**: (by Nov 24, 20:00):

Choose one of the following tasks:

1) Select a text corpus of your choice and train a language model over it (e.g. [Karel Čapek's novels](https://github.com/simecek/capek), [Bible](https://danielhnyk.cz/kompletni-bible-v-cestine-v-html-txt-kralicka-ekunemicka-bible21/), [C++ code](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)...). Then generate a few examples of the text. Did you manage to make it believable (or at least funny)? You can use any tokenizer and model you want, e.g.

    - either character-lever or word-level tokenizer and LSTM/GRU (as we have seen in [NLP From Zero To Hero](https://goo.gle/3aSTLGx) for Irish songs).

    - or take HuggingFace model and fine-tune it (an example for [German receipts](https://colab.research.google.com/github/philschmid/fine-tune-GPT-2/blob/master/Fine_tune_a_non_English_GPT_2_Model_with_Huggingface.ipynb))

2) Find some creative use for [Small-E-Czech](https://huggingface.co/Seznam/small-e-czech) model (like using fill-mask to guess y/i or fine-tuning it on a completely different task).