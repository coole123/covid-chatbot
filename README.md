# covid-chatbot
New covid chatbot using rasa 2.0


                                                                      RASA CHATBOT
Introduction

If you want to build a conversational ai we need a bot that should be created so that a person can interact with it. Every time that a person interacts with the computer a chatbot as an assistant can guild a person on that particular website and so that is why chatbot is important.

A Conversation chatbot understands the context of the conversation and can handle any user goal gracefully and help accomplish it as best as possible. This doesn’t always mean that the bot will be able to answer all questions but it can handle the conversation well.

Making a chatbot or virtual assistance is used to transform the user experience. Nowadays, chatbots are gaining attraction, big or small entities such as IBM, Google, Facebook? are working on it and building their in-house products.

What is rasa?
Rasa is a machine learning conversational ai which is used to build a chatbot. It is one of the best open-source machine learning toolkits which is used to developer complex chatbot with minimal training data.

It is based on two frameworks-

1.Rasa nlu– a library for natural language understanding (NLU) which does the classification of intent and extracts the entity from the user input.

2.Rasa Core– A chatbot framework that predicts the next best response or action based on conversational history.



Install the python development environment.


run this in the terminal or the command prompt cmd

python –version

pip –version

this is to ensure that the python is installed in the system.


2. Install rasa open source and virtual environment

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




Once you have developed your bot and you are ready to integrate the bot with the UI, you can start the Rasa server using the below command

1.rasa run -m models --enable-api --cors "*" --debug


If you have custom actions, you can start the action server using the below command

2.rasa run actions

 
