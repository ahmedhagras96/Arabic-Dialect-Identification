# Arabic-Dialect-Identification

## Introduction
- This project is about detect the dialict of arabic text. It's considered as text classification problem so the pipeline fowllwed to get the best accurcy is 
![Screenshot 2022-03-14 221039](https://user-images.githubusercontent.com/32541520/158253289-5713dba8-f113-4655-a4d4-12691fda257d.png)

## About Data
- The Data used in this project is QADI dataset that is labeled from Qatar Computing Research Institute (Research team) manually by native speakers from every country and The average accuracy across countries was 91.5%

## Data Preprocessing
- Clean our data from English and symbol characters to avoid distracting model with chars that not represented our required dialects
- For embedding we use different types of embedding with different models according to logic we are follow you will find further information in the Model Training notebook

## ML & DL Applied Models
- SVM classifier when using a word n-grams embedding
- SGD classifier when using a Tf-idf Vectorizer
- RNN with contextualized embeddin
