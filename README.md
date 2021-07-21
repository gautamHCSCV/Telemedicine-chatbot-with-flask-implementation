# flask-chatbot
Built on python 3.6
Flask==0.11
chatterbot==0.8.4
SQLAlchemy==1.1.11

#### A web implementation of [ChatterBot](https://github.com/gunthercox/ChatterBot) using Flask.

## Local Setup:
 1. Open command prompt and locate folder. run 'pip install -r requirements.txt'
 2. Run *train.py*
 3. Run *run.py*
 4. Demo will be live at http://localhost:5000/


bot : Hi There! I am a medical chatbot. You can begin conversation by typing in a message and pressing enter.
user : my name is yogesh
bot : - Hello! your name has been stored. What is your age?
user : hello
bot : - Hi. How are you feeling today?
user : i am 19 years old, am good
bot : - you shall be called once the doctor is available. Do you want to book an appointment?
user : i am good
bot : - good to know. how may i assist you then?
user : but i have some issues with my head
bot : - symptom noted.
