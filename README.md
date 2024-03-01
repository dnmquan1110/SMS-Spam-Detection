# SMS Spam Detection
 Classify collected messages as spam or legitimate

## Information
In this repo, I use some Naive Bayes models and 2 neural network models to detect if a sms is junk or not

## Purpose

The purpose of this notebook is to:
- Check the performance of some Naive Bayes basic model on classification text task
- Compare my custom neural network to Bidirectional LTSM model - powerful tools for processing sequential data like text or time series
- Compare the performance of these models

## Steps
1. Load the SMS-Spam-detection dataset on Kaggle using kaggle.json file saved on my drive
2. Preprocessing data for training
3. Train 5 models: MultinomialNB, GaussianNB, BernoulliNB, custom neural network, bidirectional LSTM
4. Compare these performance

## Result

- My custom neural network model has a best performance with 97.78 accuracy score
- The BernoulliNB model is only slightly inferior to custom neural network although I did not fine-tune anything with this model, and is better than Bi-LSTM model
- GaussianNB model has the worst performance among these models, but its result is not bad

# Software and Hardware Requirements

- Kaggle framework
- kaggle.json file: It stores the authentication and configuration information required to access and download the dataset from the Kaggle API. You can visit  https://www.kaggle.com/docs/api to know more
- Some common frameworks: numpy, pandas, matplotlib, tensorflow, scikit-learn
