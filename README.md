# psycholobot
**Miley: The Psychologist ChatBot** named after my cat, Miley...so you could say this is a *CATbot*. (I'll hold for laughter)     
* This is a deep learning project using seq2seq neural networks.  
* Trained from a serialized pickle file after running the train_chatbot.py.

## Setup
1. Get your virtual-environment running:
    * `pip install virtualenv`
    * `python -m venv ./venv`
    * `cd ./venv/Scripts`
    * `source activate`
2. Download your depenedencies:
    * `pip install tensorflow, keras, pickle, nltk`
        * *NOTE: if tensorflow doesn't work, make sure you have python 64 bit installed.*
        * *NOTE NOTE: run `pip install pickle-mixin` if you have pickle probs. However, it looks like pickle is a default lib install on Python38 these days, so this may be overkill.*

## Run
1. Train the model
    * `python train_chatbot.py`
2. Run the program!
    * `python miley.py`
  
  
### Full Disclosure
I'm not this clever. People have already built things like this. Actually, I've copied most of the model's source code from the source below. I've just changed the look, the feel, and the intents of this model. Full credit should be given to the data-flair.training org. Sauce: https://data-flair.training/blogs/python-chatbot-project/
