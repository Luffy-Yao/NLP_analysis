# NLP analysis of windows log in messages
An individual project aimed at predicting the right event type given purely text information. My way approaches this type of task is to 
leverage of power of Natural Language Processing techniques and Deep Learning models.


# Data Description
A dataset in a short time period on OCT 3rd, 2019. It contains three features: time, messages, event type. My goal is to develop a model so that it can successfully put each observation into the right eventype category without knowing the event type beforehand.



# Glove Embeddings
I need to convert the text information into a vector format so that deep learning models could fit well. That's why Glove Embedding
comes into play. An high level behind Glove Embedding is that by fixing the dimension of a word representation, any word can be 
accurately transformed into a vector form without losing connection to its synonyms and creating a very sparse word vector.

Intersted readers can refer to the official webiste of [Glove Embedding](https://nlp.stanford.edu/projects/glove/)


# Building the Model
The main tool I use for developig deep neural networks is Keras. Keras uses Google's Tensorflow (TF) as the primary backend engine
can work with TF libraries when building and training models. Keras abstracts TF building blocks, allowing us to build a model 
layer by layer.

For more information, readers can refer to the official website of [Keras](https://keras.io/). 


# Outcome
By calibrating the models with an huge amount of effort, I conclude this model with 99.4% accuracy without incurring an overfitting issue.
