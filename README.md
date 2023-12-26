# aumnitechworks
Testing-assignment2023
``` Tasks to do By 
Author : Bharat Mishra
Date : 12-26-23

Given the data in the CSV file provided to you:
1. Design a relational database schema to store the data for the Ships and their
Positions.
2. Write Python code to automatically load the CSV data into a relational database.
3. Write, using Python, a REST API that implements 2 endpoints:
a. /api/ships/: must show a list of current ships in the database. Payload
should show at least the imo and name of every ship record.
b. /api/positions/<imo>/: given the imo of one of the ships, must show
the positions related to that ship in descendent order (starting from the last
one received, list all of them until the oldest one). Payload should also show
at least the latitude and longitude of every position. ```



#### Key Features
- 1 . Rest Api
- 2 . CSV Import
- 3 . File Upload
- 4 . CSV Export
- 5 . show list of current ships
- 6 . Positions of ship "imo of one of the ships, must show
the positions"


# Step for Set Up


``` 
 1. git clone https://github.com/Misrabharat/aumnitechworks.git

 2. Change settings.py MYSQL CONFIGURATIONS (name, user, password)

 3. python manage.py load_csv

 4. pip3 install -r requirements.txt

 5. python manage.py migrate

 6. python manage.py makemigrations

 7. python manage.py migrate

 8. python manage.py runserver

 9. Login to http://127.0.0.1:8000

 10. python manage.py createsuperuser (enter username, email, password)

```

# Now Rest Api Django Project Ready

