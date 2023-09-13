# AI-Chatbot
feed forward nural network with 2 hidden layers

### Intents
this is the training data. if gives tags and examples of things to ask and response patterns
if you ask it a question that it has, it gives one of the responses. If it is asked something different, it will 
try to map it to a different response.  

### Set up pytorch on computer
1. set up python vertual environment
- in command prompt type:  python3.11 -m venv /samplesession/ 
- - samplesession can be replaced with any session name
2. now run samplesession\Scripts\activate
- if that doesnt work, you will need to open powershel as admin and set exicution policy to remore signed
- - set-executionpolicy remotesigned
- then retry code
3. now you should instal pip
- pip3 install --upgrade pip
4. install torch
- pip install torch

### NLP Preprocessing Pipeline
1. tolenize
2. lower and stem
3. exclude punctuation characters
4. bag of words
"C:\Users\bette\OneDrive\Documents\GitHub\AI-Chatbot"


