
# Railway Reservation System Using Django

The Railway Reservation System facilitates the passengers to enquire about the trains available on the basis of source and destination, Booking and Cancellation of tickets, enquire about the status of the booked ticket, etc. The aim of case study is to design and develop a database maintaining the records of different trains, train status, and passengers.
 


## PROJECT DESCRIPTION

This project is about creating the database about Railway Reservation System.  Its design and develop a database maintaining the records of different trains, train status, and passengers. The record of train includes its number, name, source, destination, and days on which it is available, whereas record of train status includes dates for which tickets can be booked,  Passengers can book their tickets . For this, passenger has to provide the desired train number and the date for which ticket is to be booked. Before booking a ticket for a passenger, the validity of train number and booking date is checked. Once the train number and booking date are validated, the ticket is booked with confirm status and corresponding ticket ID is generated which is stored along with other details of the passenger. The ticket once booked can be cancelled at any time. For this, the passenger has to provide the ticket ID (the unique key). The ticket ID is searched and the corresponding record is deleted.






## Tech Stack

**Client:** Html, Css, Bootstrap

**Server:** Django, Sqlite


## Installation



```bash
  pip install django
  python manage.py makemigrations
  python manage.py migrate
  python manage.py runserver
  //Copy the address and paste to the browser
```
    
## Features

#### Index Page
    1. Home Page
    2. About Project
    3. Login
    4. Register
    5. Contact
    
#### Login & Register
    1. User Login
    2. Admin Login
    3. User Registration

#### User Page
    1. Dashboard - User Home Page
    2. Search Train -  Search The Train And Book Ticket
    3. My Booking - View Bokking And Print
    4. Logout - Logout User

#### Admin Page
    1. Dashboard - Admin Home Page
    2. Add Train - Add New train
    3. Add Route - Add Train Route
    4. View Route - View the route of train and Edit
    5. Train Report - Report of train schedule
    6. View Booking - View the booking of users
    7. View Reg. User - View Register user and edit
    8. Logout - Logout Admin




## 🛠 Skills
Python,Django, HTML, CSS , C , C++...


## Authors

- [Aman Singhal](https://github.com/amansinghal03)


## Related

Here are some related projects

[Bus Booking](https://github.com/jameskomo/bus-reservation-system.git)

