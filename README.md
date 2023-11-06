# NaanMudhalvan1
# Chatbot - NAAN MUDHALVAN

## Overview
- This repository contains the code for a simple chatbot that can recognize user intents and generate responses based on predefined training data. The chatbot is implemented using Python, PyTorch, NLTK, and Flask.


## Setup

Clone repo and create a virtual environment
```
$ git clone https://github.com/jaya180/NaanMudhalvan1.git
$ cd chatbot-deployment
$ python3 -m venv venv
$ venv/Scripts/activate
```
## Dependencies
Before running the code, you'll need to install the following dependencies:
- Python (3.7+)
- PyTorch (1.9+)
- Flask (2.0+)
- NLTK (3.6+)
- NumPy (1.20+)
You can install these dependencies using pip. For example:
```
$ pip install torch flask nltk numpy
```

Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```
## Running the Web Application:
- The chatbot is accessible through a web application. To run the web application, use the following command:
```
python app.py (or) flask run
```
- The web application will be available at http://127.0.0.1:5000/ by default. You can access it through a web browser.

## Interacting with the Chatbot:
- Access the web application in your browser.
- Type messages or questions in the chat interface.
- Press Enter to submit each message.
- The chatbot will respond based on the training data and model predictions.

## Terminating the Chatbot:
- To exit the chatbot, you can type "quit" in the chat interface, and the chat session will end.

## Customization
- You can customize the chatbot's behavior by updating the training data in the intents.json file. Add new intents, patterns, and responses to enhance the chatbot's capabilities.
- You can also modify the model architecture and hyperparameters in the model.py and train.py scripts to improve performance.

## Working video
[Chatbot_NaanMudhalvan](https://drive.google.com/file/d/1AjiXHgfPMxDfg80r7cEI6Li0KP9CK3cU/view?usp=sharing)
