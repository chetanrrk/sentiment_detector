# Sentiment Detection from IMDB Movie Review Deployment Project

The simple web app interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. LSTM model is built using PyTorch consisting of single a single hidden layer and sigmoid activation function. XGBoost model that uses the ML libarary of sagemaker is also trained and deployed on a separate notebook. The models are trained on a large IMDB movie review data converted into bag-of-words with labels, and  deployed on AWS SageMaker using lambda function and API GateWay.

# To Run
git clone https://github.com/chetanrrk/sentiment_detector

cd sentiment_detector

## LSTM Model
jupyter-notebook SageMaker_LSTM.ipynb 

## XGBoost Model
jupyter-notebook SageMaker_XGBoost.ipynb

# The architecture of the deployed application

![alt text](https://github.com/chetanrrk/sentiment_detector/blob/main/Web_App_Diagram.svg?raw=true)