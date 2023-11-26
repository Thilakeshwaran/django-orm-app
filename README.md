# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

Install myapp using command prompt

### STEP 2:

Edit  setting.py and model.py

### STEP 3:

create a username and password usingfor your django 'python Createsuperuser' and then run the program using python manage.py runserver [your port number]

## PROGRAM
```
admin.py
from django.contrib import admin
from.models import Football_player,Football_playerAdmin
admin.site.register(football_player, Football_playerAdmin)

model.py
from django.db import models
from django.contrib import admin
class Football_player (models.Model):
     Name-models.CharField(max_length=20)
     Dob models.DateField()
     Height models. IntegerField()
     Address-models.CharField(max_length=100)
     MobileNo=models. IntegerField()
class Football_player (admin.ModelAdmin):
     list_display=["Name", "Bob", "Height", "Address","MobileNo"]
```
## OUTPUT

I![exercise2output](https://github.com/Thilakeshwaran/django-orm-app/assets/147473132/6f4cecb3-2f5c-48f8-88d4-28039b1f978f)



## RESULT 

Thus the program for creating a database usimg ORM has been ececuted successfully
