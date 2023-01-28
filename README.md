# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram
![hostel2](https://user-images.githubusercontent.com/118707091/215277743-aef2a1d6-97b5-4a22-a252-15ccdce5975f.png)


## DESIGN STEPS

### STEP 1:
Clone the repository to theia ide. start a new app inside the project folder.

### STEP 2:
Type the appropriate code for your table and provide appropriate data types to the columns.

### STEP 3:
Create a report about your project in readme.md file and upload the django.orm.app folder to your remote repository.


## PROGRAM

```
from django.db import models
from django.contrib import admin
class hostel(models.Model):
    roomno=models.IntegerField(primary_key=True,help_text="roomno")
    name=models.CharField(max_length=100)
    native=models.CharField(max_length=100)
    inmates=models.CharField(max_length=100)
    food=models.CharField(max_length=10)
class hostelinfo(admin.ModelAdmin):
    list_display=('roomno','name','native','inmates','food')
    ```

## OUTPUT

Include the screenshot of your admin page.
![Screenshot (67)](https://user-images.githubusercontent.com/118707091/215277144-d84d2df9-45a0-45f2-be06-a430acefd7c3.png)


## RESULT
Thus the project is developed to have Hostel information database
