# pneumonia_detection_app   
hey....   
following are the steps for deploying a machine learning project over the heroku cloud platform

step1: install the heroku application.

step2: create a folder named with the application name and have the following foolder in it(keep track of the alphabet cases as file names are case sensitive):      
  
     1.static    
     2.uploads    
     3.templates    
     4.Procfile    (in File format mind it P in procfile is in capital letters)  
     5.requirements.txt    (here filename is requirements.txt not requirement.txt)     
     6.app.py  
     7.training_code.py    
     8.saved_model.h5  

step3: open your cmd   
step4: write following commands as shown below:
     
     1. git init
     2. git add .
     3. git commit -m "message of commit"
     4. heroku create (for creating the app)  
     5. git remote -v  (to check status)  
     6. git push heroku master  
     
if every thing done in correct manner and as stated as above then this will deploy your application over the heroku cloud platform.....   
congrats....   you have deployed your application over the heroku..    
