# Chatbot
This is an interactive Chatbot for conversing with the customer. <br>

Zomato Chatbot <br>

&nbsp; . <br>
&nbsp; |-------static <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;|-------base.html <br>
&nbsp; |-------templates <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;|------images <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;|-------chatbot.jpg <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;|-------app.js <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;|-------style.css <br>
&nbsp; |-------chat.py <br>
&nbsp; |-------data.pth <br>
&nbsp; |-------intents.json <br>
&nbsp; |-------main.py <br>
&nbsp; |-------model.py <br> 
&nbsp; |-------nltk_utils.py <br>
&nbsp; |-------requirements.txt <br>
&nbsp; |-------train.py <br>


intents.json - Has all the conversations for the chatbot with Tags , patterns and responses.
<br>
nltk_utils.py - Contains 3 functions for tokenising, stemming, lemmatising and bag of words.
<br>
model.py - Contains Neural Network function build with help of PyTorch.
<br>
train.py - Model Training
<br>
chat.py - Jsonfies the responses and sends it to the model and gets the reply from chatbot.
<br>
main.py - Flask API
<br>
<br>
base.html - Contains the structure of the dialog box of the chatbot.
<br>
style.css - Contains styling of the html skeleton.
<br>
app.js - Contains 3 functions as there are 3 actions:  
&nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. Opening the chatbox   2. Sending to chatbot  3.Toggling the state for the bot to reply.
<br>


        





