# First Python Chatbot Project for Begginers

Chatbots are extremely helpful for business organizations and also the customers. The majority of people prefer to talk directly from a chatbox instead of calling service centers. Facebook released data that proved the value of bots. More than 2 billion messages are sent between people and companies monthly. The HubSpot research tells us that 71% of people want to get customer support from messaging apps. It is a quick way to get their problems solved so chatbots have a bright future in organizations.

Today we are going to build an exciting project on Chatbot. We will implement a chatbot from scratch that will be able to understand what the user is talking about and give an appropriate response.

# Prerequisites

To implement the chatbot, I used Keras, which is a Deep Learning library, NLTK, which is a Natural Language Processing toolkit, and some helpful libraries. Run the below command to make sure all the libraries are installed:

pip install tensorflow keras pickle nltk 

# How do Chatbots Work?

Chatbots are nothing but an intelligent piece of software that can interact and communicate with people just like humans. Interesting, isn’t it? So now let's see how they actually work.

All chatbots come under the NLP (Natural Language Processing) concepts. NLP is composed of two things:

NLU (Natural Language Understanding): The ability of machines to understand human language like English.

NLG (Natural Language Generation): The ability of a machine to generate text similar to human written sentences.

Imagine asking a question to a chatbot: “Hey, what’s on the news today?”

The chatbot will break down the user sentence into two things: intent and an entity. The intent for this sentence could be get_news as it refers to an action the user wants to perform. The entity tells specific details about the intent, so "today" will be the entity. So this way, a machine learning model is used to recognize the intents and entities of the chat.

# Project File Structure

After the project is complete, you will be left with all these files. Lets quickly go through each of them. It will give you an idea of how the project will be implemented.

 Train_chatbot.py — In this file, we will build and train the deep learning model that can classify and identify what the user is asking to the bot.

 Gui_Chatbot.py — This file is where we will build a graphical user interface to chat with our trained chatbot.

 Intents.json — The intents file has all the data that we will use to train the model. It contains a collection of tags with their corresponding patterns and responses.

 Chatbot_model.h5 — This is a hierarchical data format file in which we have stored the weights and the architecture of our trained model.

 Classes.pkl — The pickle file can be used to store all the tag names to classify when we are predicting the message.

Words.pkl — The words.pkl pickle file contains all the unique words that are the vocabulary of our model.
