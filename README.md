Made a telemedicine chatbot to assist the doctors. The bot is trained to greet the patients, provide information about availability of the doctor and provide some basic home remedies. It helps to know the symptoms of the patient and the type of symptom he/she is experiencing. The chatbot can easily be updated on updating the data files and running train.py file.

# flask-chatbot
Built on python 3.6
Flask==0.11
chatterbot==0.8.4
SQLAlchemy==1.1.11

## Virtual enviroment for python 3.6
https://stackoverflow.com/questions/52138280/easiest-way-to-use-python-3-6-and-3-7-on-same-computer

Download the Python3.6 tgz file from the official website (eg. Python-3.6.6.tgz)
Unpack it with tar -xvzf Python-3.6.6.tgz
cd Python-3.6.6
run ./configure
run make altinstall to install it 
You'll normally find your new python install under /usr/local/bin. Now you can create a new virtualenv specifying the python version to use with:

virtualenv --python=python3.6 env3.6
Get into the virtualenv running the command source env3.6/bin/activate.


#### A web implementation of [ChatterBot](https://github.com/gunthercox/ChatterBot) using Flask.

## Local Setup:
 1. Open command prompt and locate folder. run 'pip install -r requirements.txt'
 2. Run *train.py*
 3. Run *run.py*
 4. Demo will be live at http://localhost:5000/
 
 #### Deployment on heroku: https://telemedicine12chatbot.herokuapp.com/

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

Sources of data:
1. Most of the data is self prepared.
2. https://www.aplustopper.com/conversation-between-doctor-and-patient/
3. https://www.peptalkindia.com/english-conversation-between-doctor-and-patient/
  
  Note: Patients are recommended to consult doctor before using measures suggested by the bot.
