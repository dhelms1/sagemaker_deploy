# SageMaker Sentiment Analysis Project

---

<img src="/Image/header.jpg" width="400">

### Introduction 

We will perform sentiment analysis using natural language processing and recurrent neural networks on the [IMDb movie reviews dataset](https://ai.stanford.edu/~amaas/data/sentiment/) from Stanford. Using Amazon SageMaker, we will deploy a custom PyTorch model that can be deployed and used in a simple web application. The end goal for this web app is to allow a user to input a review and recieve an output of either a positive or negative sentiment. We will set up a public API using Gateway and Lambda to allow our web app to access the endpoint.

---

### Project Outline

- Prepare data: format the data so that it is ready for an RNN (convert reviews to list, create bag-of-words representation, pad review arrays, upload to S3).
- Modeling: create custom model using `sagemaker.pytorch`, write python modules for training and predicting.
- Web app: set up a Lambda function, set up API Gateway.

---


