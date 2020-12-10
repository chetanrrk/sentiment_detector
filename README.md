# Sentiment Detection from IMDB Movie Review Deployment Project

The notebook and Python files, and simple web app interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. LSTM model was built on PyTorch single a single hidden layer and sigmoid activation function. The model is trained on a large IMDB movie review data converted into bag-of-words with labels, and  deployed on AWS SageMaker using lambda function and API GateWay.

# To Run
jupyter-notebook SageMaker_LSTM.ipynb

# The architecture of the deployed application

![alt text](https://github.com/chetanrrk/sentiment_detector/blob/main/Web_App_Diagram.svg?raw=true)