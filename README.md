This is my Slot Booking project

This is a simple Django-based backend system for managing fitness class bookings. It allows users to view available classes,
 book a class (which decrements the available slots), and filter bookings by their email address.


The data like the class,instructor name date time and avilable slots were added manually

for that you have to login to the django admin using 

http://127.0.0.1:8000/admin/

username : admin
password : admin@123

after login then need to add the details for saving the entry
you should run the server while adding data

listing the classes using GET request
http://127.0.0.1:8000/classes/

for booking a slot using POST request
http://127.0.0.1:8000/book/

then in the form section give values to the parameters

id,name,email


for listing the bookings according to the email as GET request
http://127.0.0.1:8000/bookings/
then in the form section give value to the parameter

email 

for running the code use 

python manage.py runserver
