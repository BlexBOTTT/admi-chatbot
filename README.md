# SFAC-LP Admission chatbot
A WIP text-based chatbot made with RASA framework via python

aims to be conversational

5/15/2014 TEST CHATBOT

# Configurations:
    This rasa project is supported with:
    - Python Version:   3.8.10 (In blexbottt's R5-3600 desktop)
    - Rasa Version:     3.6.20

# CHECKLIST (say DONE if completed)
- Connect to website (html-php)
    - configure dataset in the front-end
- MongoDB (Knowledge Management/Base??)
- BERT
- NLPaug (for data augmentation)
- ~~LLM integration via OpenAI?~~

# Commands:

Activate venv - python 3.8.10
- venv\Scripts\activate

- rasa train
- rasa shell

rasa run --enable-api 
rasa run --enable-api --cors "*"

rasa run --enable-api --cors "*" --model <path>

# Installation problems
    - if "mattermostwrapper" issue:
        - pip install setuptools==58.0.4
        - pip install rasa
        - rasa --version

