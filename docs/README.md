## Cats vs Dogs App

This is an example of web app based on TFjs, hosted on GitHub Pages.

https://simecek.github.io/dspracticum2021/

To create a similar web app for your image dataset:

   1. Adapt the following code to your data, download the exported TFjs model: https://github.com/simecek/dspracticum2021/blob/main/lesson04/Transfer_Learning_DogsAndCats.ipynb

   1. Copy the downloaded file into docs folder of your GitHub repository and unzip it into `export_model` folder.

   1. Add files `index.html` and `index.js` from https://github.com/simecek/dspracticum2021/tree/main/docs.

   1. Change the path in `index.js` from https://raw.githubusercontent.com/simecek/dspracticum2021/master/docs/export_model/model.json to the path in your repo.

   1. Change the setting of your repository to use GitHub pages (`main` branch, `docs` folder).
