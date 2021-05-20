# Wellness Tracking Assistant
## Overview:
This repo contains all the neccesary chatbot files, i.e RASA project files. The aim is to train the assistant to identify the user's intent, ask few health-related question, and store the retrieved data into spreadsheet. The implemention of this project is done using RASA Open-Source and RASA X. Refer below steps, in order to run and test the bot in conversational-driven development environment, accesing the application through Chrome Extension.

**Concepts:**
- ChatBot Development 
- Natural Language Processing

**Tools & Technologies:**
- [RASA: Open source](https://rasa.com/docs/rasa/)
- [Rasa X](https://rasa.com/rasa-x/)
- Anaconda virtual environment
- Python 
- Javascript
- HTML

***NOTE***: 
Some of the features may fail after Rasa 3.0 version update.
Refer [version-migration-guide](https://rasa.com/docs/rasa/migration-guide/) for version migration.

> Installation Guide:
- To install Rasa:
```
pip install rasa
```
- To install Rasa x:
```
pip install rasa-x
```

## Implementation:
```Python
Step 1: `rasa init`: This command creates a new Rasa project in specified directory 
         with example training data, actions, and config. files.
Step 2: Train the rasa assistant with suitable examples in NLU traning data directory.
Step 3: To test the trained model thorugh command line interface run `rasa shell` in your terminal.
Step 4: Running `rasa x` command should open a browser tab to `http://localhost:5002/`,
        in order to start the user-inetraction with trained bot in a conversational-driven environment.
```

## Screenshots:
![Snips](https://github.com/gauravpore/healthcare_rasa-bot/issues/1#issue-897002774)

## References:
- [Rasa documentaion](https://rasa.com/docs/rasa/)
- [Chrome Extension](https://github.com/gauravpore/healthcare_rasa-bot/tree/master/Chrome%20extension)

## Contribution:
Contributions are always welcomed.
Make sure you read the [Contribution info](https://github.com/gauravpore/healthcare_rasa-bot/blob/master/contribution.md) before making pull request.
        
        
        
        
        
        
