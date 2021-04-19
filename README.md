# Let's learn how to build a chatbot using RASA Framework

🔴 Follow this video for the code walkthrough:

[![Alt text](https://raw.githubusercontent.com/pik1989/RASAChatbot/main/RASA%20Chatbot.jpg)](https://www.youtube.com/watch?v=2qI1CcMa55c)



# Introduction
If you want to build a conversational ai we need a bot that should be created so that a person can interact with it. Every time that a person interacts with the computer a chatbot as an assistant can guild a person on that particular website and so that is why chatbot is important.

A Conversation chatbot understands the context of the conversation and can handle any user goal gracefully and help accomplish it as best as possible. This doesn’t always mean that the bot will be able to answer all questions but it can handle the conversation well.

Making a chatbot or virtual assistance is used to transform the user experience. Nowadays, chatbots are gaining attraction, big or small entities such as IBM, Google, Facebook? are working on it and building their in-house products.

# What is rasa?
Rasa is a machine learning conversational ai which is used to build a chatbot. It is one of the best open-source machine learning toolkits which is used to developer complex chatbot with minimal training data.

It is based on two frameworks-

1.Rasa nlu– a library for natural language understanding (NLU) which does the classification of intent and extracts the entity from the user input.

2.Rasa Core– A chatbot framework that predicts the next best response or action based on conversational history.


# Requirements
We majorly require the installation of Rasa Stack and a language model. The language model is going to be used to parse incoming text messages and extract the necessary information. We will be working with the SpaCy language model.


2.How it works
First, let us understand how it works (rasa chatbot).
 

When Rasa receives a message from the user, it predicts or extracts the intent and entities present in the. This part is handled by Rasa   NLU (mentioned previously).
Rasa then tries to predict the next action (what it should do next). This decision is taken considering multiple factors. This part is handled by Rasa Core
Once the user?s   intent is identified,   Rasa performs an action called action_request_certificate to get the request the certificate in question.
3 Installing Rasa and Dependencies
 

# 1.  Install the python development environment.

run this in the terminal or the command prompt cmd

python –version

pip –version

this is to ensure that the python is installed in the system.

# 2. Install rasa open source and virtual environment

this is to activate the virtual environment. If you want to build in more functionality in the rasa bot then you should install the virtual machine using these commands.

You should first install all the packages of python and TensorFlow and Keras should be installed first then only install rasa open source and virtual environment. Install rasa open source and virtual environment.

1.pip install -U pip

2.pip install rasa(cmd) and pip install rasa[full]


3.  You also need to install a spaCy English language model:
Python -m spacy download en

(write this after installing rasa)

Or you can download a language model using this command


2.2 Make sure you also install rasa -SDK by writing the code
pip install rasa rasa-SDK

(As this will help to create the rasa chatbot)

When you have done all the things then now we can set up the chatbot in rasa. All the steps work best in cmd or pycharm as in the next steps are all in pycharm.


# How to run the rasa Chatbot in a custom widget

1.Once you have developed your bot and you are ready to integrate the bot with the UI, you can start the Rasa server using the below command

rasa run -m models --enable-api --cors "*" --debug


2.If you have custom actions, you can start the action server using the below command

rasa run actions

