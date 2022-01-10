# Jan22_Q3   IP Locator

There is a Free API which gives the response in json with lots of information as lat,long,country, country code, region etc as follow:- 

URL :- http://ip-api.com/json/{query} 
Method :-  GET
Here the query is the IP address. 

{
  "query": "24.48.0.1",
  "status": "success",
  "country": "Canada",
  "countryCode": "CA",
  "region": "QC",
  "regionName": "Quebec",
  "city": "Montreal",
  "zip": "H1A",
  "lat": 45.6752,
  "lon": -73.5022,
  "timezone": "America/Toronto",
  "isp": "Le Groupe Videotron Ltee",
  "org": "Videotron Ltee",
  "as": "AS5769 Videotron Telecom Ltee"
}
 
The candidate should ensure the availability of Git, 
Python and Django on their system as part of the setup exercise.. Preferred IDE is PyCharm to import the project directly. Postman tool to test the REST APIs and git.  
To start the development a skeleton repo for the project is provided at the github link – https://github.com/kumarram1011/Jan22_Q3   (master branch).
Then repo can be cloned into their local system through HTTPs or SSH. After cloning the project at your location, follow the below points:  Create Virtual env (ubuntu) 
  1. sudo apt install python3-venv 
  2. python3 -m venv relevel_env 
  3. cd relevel_env/ 
  4. source bin/activate Now quit this env location and jump to your working location/ Parent directory  

Install all dependencies using ‘pip install -r requirements.txt’

Now run your initial migrations with the command as: 
  1. python manage.py makemigrations 
  2. python manage.py migrate  
   
  Note :-  A. Initially there is no any model in your projects so the 1st command will give you the response has "NO changes" but the 2nd command will configure you all initial settings like DB and all. 
  B. At every stage while developing/implementing the features please use both of the above commands to reflect your changes in the running/development server.  Run ‘python manage.py runserver’ to start the development server. 
  
 The hosted app can be checked on http://localhost:8000 on the browser.  
 
 
 
 Submission Instructions  Code Submission: Compress the code on the local system in the form of a *.zip file. Upload the code on your personal google drive in a folder titled - “Name_BD_ Code Base” Don’t forget to change the permissions of the folder to ‘Anyone with the link can edit’.  Loom video submission: Create an account on Loom. Go through the quick tutorial on how to record loom videos. Create a Loom video (while screen sharing) covering the following points: Show the functionality of the app you have created i.e demo of the working APIs through a command line. (1 min) Run through the key parts of your code explaining the core logic and how you organized the code. (2 min) Explain your problem-solving approach (what logic you have used and why). (2 min) Please keep your explanation to under 5 mins only. Avoid too much jargon and explain your app in a simple and clear manner.
