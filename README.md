# Chatbot With Python README

## Description
This Python chatbot is designed to interact with users through text-based conversations. It utilizes Natural Language Processing techniques to understand user input and generate appropriate responses.

## Features
- **Natural Language Processing:** The chatbot uses NLP algorithms to analyze and interpret user messages.
- **Response Generation:** Based on the input received, the chatbot generates relevant responses.
- **Customizable Responses:** You can easily customize the responses by modifying the code.
- **User Interaction:** The chatbot engages users in meaningful conversations.

## Files
1. `chat.py` : a script to boot the chatbot and receive the input from the user.
2. `train.py` : script to train the chatbot on the training data saved in the `intent.json`.
3. `intent.json` : json file full of patterns of possible user requests, followed by responses of each pattern.
4. `nltk_utils.py` : containes methods of tekoninzing and stemming...
5. `model.py` : model of chatbot absed on PyTorch Library

## Usage
1. Run the training script: `train.py`
2. Run the chatbot script: `chat.py`
3. Start interacting with the chatbot by typing messages in the console.
4. Quit the chatbot by typing 'quit'

## Customization
- To add new responses/patterns or modify existing ones, edit the `intent.json` file.
- You can enhance the functionality by integrating additional NLP libraries or APIs.


Enjoy chatting with your Python chatbot! 🤖🐍
