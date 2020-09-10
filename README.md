# psycholobot
Miley: The Psychologist ChatBot. A deep learning project using seq 2 seq neural networks.
Sauce: https://data-flair.training/blogs/python-chatbot-project/

## Setup
1. Get your virtual-environment running:
    * `pip install virtualenv`
    * `python -m venv ./venv`
    * `cd ./venv/Scripts`
    * `source activate`
2. Download your depenedencies:
    * pip install tensorflow, keras, pickle, nltk
        * *NOTE: if tensorflow doesn't work, make sure you have python 64 bit installed.*
        * *NOTE NOTE: run `pip install pickle-mixin` if you have pickle probs. However, pickle is a default lib install on Python38 these days and may be overkill.*

## Run
1. Train the model
    * `python train_chatbot.py`
2. Run the program!
    * `python miley.py`
