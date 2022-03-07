# insta-clone | Kiprono Dominic Segem

>[Kiprono Dominic Segem](https://github.com/segem001)  
  
# Description  
This is a clone of  Instagram where people share their  images and videos for other users to view. 
Users can sign up, login, view and post photos, search and follow other users.
##  Live Link  
 Click [View Site]()  to visit the site
  

 
## User Story  
  
* Sign in to the application to start using.  
* Upload  pictures to the application. 
* Search for different users using their username.  
* See your profile with all your pictures.  
* Follow other users and see their pictures on my timeline.  
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 
##### Navigate into the folder and install requirements  
 ```
cd instagram-clone
 pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```
- python3 -m venv virtual 
source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations instagram
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* Python3.8
* Html
* Heroku
* Bootsrap5
* js

  
## Contact Information   
If you have any question or contributions, please email me at [kipdom001@gmail.com]  
  
## License 
* MIT license
* Copyright (c) 2022 **Kiprono Dominic Segem**