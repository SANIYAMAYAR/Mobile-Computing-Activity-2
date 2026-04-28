# Mobile-Computing-Activity-2


https://www.mediafire.com/file/czh4ryhnsucdikk/Screen_Recording_20260428_233709.mp4/file

AIM and Algorithms 

To develop a Bus Ticket Booking Android Application using MIT App Inventor that allows users to search buses, select seats, enter passenger details, make payments, and view booking history.
••ALGORITHM (SCREEN-WISE)
*Screen 1 – Splash Screen
Start the application
Display app logo and title
Wait for user to click START
Navigate to Login Screen (Screen2)

*Screen 2 – Login
Algorithm:
Initialize variable userName
Accept input from user (name)
If name is empty → show alert
Else store name in variable
Navigate to Search Bus Screen (Screen3)

*Screen 3 – Search Bus
Algorithm:
Display input fields (From, To)
Load predefined bus routes into ListView
When user clicks SEARCH:
If From/To is empty → show alert
Else → go to Bus List Screen (Screen4)

*Screen 4 – Bus List
Algorithm:
Display list of available buses
When user selects a bus → store in selectedBus
When SELECT button clicked →
Navigate to Seat Selection Screen (Screen5)

*Screen 5 – Seat Selection
Algorithm:
Display seat buttons (Seat1, Seat2, Seat3)
When user clicks a seat → store selected seat
Display selected seat
On NEXT → go to Passenger Details Screen (Screen6) 

*Screen 6 – Passenger 
Algorithm:
Accept passenger name and age
Validate input fields
On NEXT → navigate to Payment Screen (Screen7)

*Screen 7 – Payment
Algorithm:
Display payment options (UPI/Card)
Wait for user selection
On PAY button click →
Process payment (basic simulation)
Navigate to Ticket Screen (Screen8)

*Screen 8 – Ticket
Algorithm:
Display confirmation message
Show details:
User Name
Selected Bus
Seat Number
Save booking into history list
On HOME button → go to Search Screen (Screen3)

*Screen 9 – History
Algorithm:
Load all previous bookings
Display in ListView
Allow user to view past ticket details

*Screen 10 – Settings
Algorithm:
Display Reset and Logout options
If Reset clicked → clear stored data
If Logout clicked →
Navigate back to Login Screen (Screen2)


