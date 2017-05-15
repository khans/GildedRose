# GildedRose
Design v1 for Gilded Rose Inn

## Pre-requisites
+ Install Python 2.7+, I am using Python3
+ Terminal 

## Basic components
Different classes have been created:
+ class _Room_ in **room.py**
+ derived class _InUseRoom_ in **room.py**
+ class _Squad_ in **squad.py**
+ class _Gnome_ in **gnome.py**
+ class _Customer_ in **customer.py**
+ class _Reservation_ in **reservation.py**
+ class _Solution_ in **main.py*
All classes barring the Solution class, are important individial components of the system.
All rooms have a current situation, either Available, Occupied, Not Clean or Cleaning Up.
Only the rooms that are available can be booked.
If other types of rooms need to be booked at a later date, cleaning information needs to be obtained.


## How to run
Simply download the files in a directory.
From Terminal go to the directory and run **python main.py**


## Steps taken in case of unlimited time:
+ Would have Designed mysql database
+ Would have Create database gildedRose
+ Create tables for the classes (Basic design)
  - Table _Room_
  - Table _InUseRoom_ (special type of room which is not vacant, will have more columns)
  - Table _Customer_
  - Table _Gnome_
  - Table _Squad_
  - Table _Reservation_
  - Table _Bookings_
  - Table _Accounts_
+ All the tables would have current data stored and updated, each time there is a successful reservation.
+ Would have written more methods in all classes and tested each one of them.
+ Would have written unit tests in Python and tested individual components thoroughly.
+ Would have taken user input from terminal or command-line
+ While booking or reserving, in case a room that is occupied is required at a future date,
  the cleaning squad's next availability and the time they will finish cleaning is obtained.
  If it is before te requested check in date, that room would be bookable.
+ Would have designed a front page for interfacing

 
## References
[Codecademy](https://www.codecademy.com/learn/python "Python Codecademy!")
[Datetime](http://stackoverflow.com/questions/20365854/comparing-two-date-strings-in-python "StackOverflow")
[Python](https://learnpythonthehardway.org/book/ex40.html "Learn Python") 
[TimeDelta](http://stackoverflow.com/questions/27912803/how-to-get-total-hours-and-minutes-for-timedelta-in-python "TimeDelta in Python")
[Datetime calculations](http://stackoverflow.com/questions/13685201/how-to-add-hours-to-current-time-in-python "StackOverflow")



