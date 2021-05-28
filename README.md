# 🔹Wellness Tracking Assistant 🤖
## 🔸Overview:
This repo contains all the neccesary chatbot files, i.e RASA project files. The aim is to train the assistant to identify the user's intent, ask few health-related question, and store the retrieved data into spreadsheet. The implemention of this project is done using RASA Open-Source and RASA X. Refer below steps, in order to run and test the bot in conversational-driven development environment, accesing the application through Chrome Extension.

🔸**Concepts:**
- ChatBot Development 
- Natural Language Processing

🔸**Tools & Technologies:**
- [RASA: Open source](https://rasa.com/docs/rasa/)
- [Rasa X](https://rasa.com/rasa-x/)
- Anaconda virtual environment
- Python 
- Javascript
- HTML
- [GTmetrix Analyzer Plugin](https://chrome.google.com/webstore/detail/gtmetrix-analyzer-plugin/abacfkkedifakkocbillijlcfhfblgci?hl=en-US)

📌***NOTE***: 
Some of the features may fail after Rasa 3.0 version update.
Refer [version-migration-guide](https://rasa.com/docs/rasa/migration-guide/) for version migration.

> 🔸Installation Guide:
- To install Rasa:
```
pip install rasa
```
- To install Rasa x:
```
pip install rasa-x
```

## 🔹Implementation:
```Python
Step 1: `rasa init`: This command creates a new Rasa project in specified directory 
         with example training data, actions, and config. files.
Step 2: Train the rasa assistant with suitable examples in NLU traning data directory.
Step 3: To test the trained model thorugh command line interface run `rasa shell` in your terminal.
Step 4: Running `rasa x` command should open a browser tab to `http://localhost:5002/`,
        in order to start the user-inetraction with trained bot in a conversational-driven environment.
```

## 🔹References:
- [Rasa documentaion](https://rasa.com/docs/rasa/)
- [Chrome Extension](https://github.com/gauravpore/healthcare_rasa-bot/tree/master/Chrome%20extension)

## 🔹Contribution:
Contributions are always welcomed.
Make sure you read the [Contribution info](https://github.com/gauravpore/healthcare_rasa-bot/blob/master/contribution.md) before making pull request.
        
 ## 🔹Screenshots:
 #### Command Line Interaction:
![alt tag](https://user-images.githubusercontent.com/67472558/119008714-09849a80-b9b0-11eb-9448-b1ae2fac9496.JPG "Command Line Interaction")

#### 🔸Chrome Extension:
![alt tag](https://user-images.githubusercontent.com/67472558/119008708-08536d80-b9b0-11eb-8a67-0fe087c9d801.JPG "Chrome Extension")

#### 🔸Interaction with Bot:
![alt tag](https://user-images.githubusercontent.com/67472558/119255658-9dd24580-bbda-11eb-86ed-6fe5a385e43e.png "Rasa x")

#### 🔸Rasa X:
![alt tag](https://user-images.githubusercontent.com/67472558/119008719-0ab5c780-b9b0-11eb-8d75-4fc0ecd0c7e0.JPG "Rasa x")

#### 🔸Wellness report form:
![alt tag](https://user-images.githubusercontent.com/67472558/119017327-84ea4a00-b9b8-11eb-8e33-07faabc91535.png "Form")

        
        
