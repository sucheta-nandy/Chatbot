# Chatbot
## What is a Chatbot?
A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human. 
Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client. 
There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.

## The Dataset
The dataset we will be using is ‘intents.json’. 
This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

### Here are the 5 steps to create a chatbot in Python from scratch:
## 1.	Import and load the data file 
First, make a file name as train_chatbot.py. We import the necessary packages for our chatbot and initialize the variables we will use in our Python project.

## 2.	Preprocess data
When working with text data, we need to perform various preprocessing on the data before we make a machine learning or a deep learning model.
Tokenizing is the most basic and first thing you can do on text data. Tokenizing is the process of breaking the whole text into small parts like words.

## 3.	Create training and testing data
Now, we will create the training data in which we will provide the input and the output. 
Our input will be the pattern and output will be the class our input pattern belongs to. 
But the computer doesn’t understand text so we will convert text into numbers.

## 4.	Build the model
We have our training data ready, now we will build a deep neural network that has 3 layers. We use the Keras sequential API for this.
After training the model for 200 epochs, we achieved 100% accuracy on our model.

## 5.	Predict the response
We will load the trained model and then use a graphical user interface that will predict the response from the bot. 
The model will only tell us the class it belongs to, so we will implement some functions which will identify the class and then retrieve us a random response from the list of responses.

## Summary
In this project, we understood about chatbots and implemented a deep learning version of a chatbot in Python which is accurate. 
You can customize the data according to business requirements and train the chatbot with great accuracy. 
Chatbots are used everywhere and all businesses is looking forward to implementing bot in their workflow.



