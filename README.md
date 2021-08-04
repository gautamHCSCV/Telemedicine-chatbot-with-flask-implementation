Made a telemedicine chatbot to assist the doctors. The bot is trained to greet the patients, provide information about availability of the doctor and provide some basic home remedies. It helps to know the symptoms of the patient and the type of symptom he/she is experiencing. The chatbot can easily be updated on updating the data files and running train.py file.

# flask-chatbot
Built on python 3.6
Flask==0.11
chatterbot==0.8.4
SQLAlchemy==1.1.11

## Virtual enviroment for python 3.6
 Download env3.6.zip file
 Install virtual enviroment
 unzip it
 run env3.6/Scripts/activate on command line
 A virtual enviroment for python 3.6 will get activated.

#### A web implementation of [ChatterBot](https://github.com/gunthercox/ChatterBot) using Flask.

## Local Setup:
 1. Open command prompt and locate folder. run 'pip install -r requirements.txt'
 2. Run *train.py*
 3. Run *run.py*
 4. Demo will be live at http://localhost:5000/
 
 #### Deployment on heroku: https://telemedicine--chatbot.herokuapp.com/

**Demo**

_bot : Hi There! I am a medical chatbot. You can begin conversation by typing in a message and pressing enter.

user : my name is yogesh

bot : - Hello! your name has been stored. What is your age?

user : hello

bot : - Hi. How are you feeling today?

user : i am 19 years old, am good

bot : - you shall be called once the doctor is available. Do you want to book an appointment?

user : i am good

bot : - good to know. how may i assist you then?

user : but i have some issues with my head

bot : - symptom noted._
