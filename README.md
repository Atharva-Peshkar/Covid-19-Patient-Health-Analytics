# Covid-19-Patient-Health-Analytics
A Boosted Random Forest Classification model was implemented to predict the outcome of the CoV-2 positive patients in China. Based on multiple features.

The original dataset was taken from: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

cvd
  + data.csv -> original dataset
  + train.csv -> training dataset (contains data for 'death' and 'recovered' columns)
  + test.xlsx -> test dataset (does not contains data for 'death' and 'recovered' columns)

final.csv -> result obtained by running the model on test.xlsx

Steps to reproduce results:

1) Place the 'cvd' directory in your Google Drive.
2) Connect the Colab Notebook to Google Drive.
3) Run the 'Covid-19 Patient Health Prediction.ipynb' file.
