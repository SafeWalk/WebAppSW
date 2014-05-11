Client Documentation
====================

<b>SafeWalk is a mobile app that allows Macalester College students to contact Safewalk services with only the touch of a button.</b> <br>
A web interface has been implemented for this project to allow SafeWalk employees to set the availability of their services and to manage the incoming requests.

<b>How do SafeWalk employees access the web interface?</b><br>
Only prior authorized users, meaning users with login information already set in the system, can and are allowed access to the webpage only, through a login system. Once logged in, the webpage displays three interactive interfaces, to set availibility and managed requests.  

<b>How is the availibility changed and how are the users notified?</b><br>
The admin user can change the availability of their services to three different status: "AVAILABLE", "BUSY", "NOT AVAILABLE". Three interactive buttons, which interact with an external server (Firebase), allow real-time update of the status on all android SafeWalk apps, thus notifying all the users.

<b>How are incoming requests received and managed?</b><br>
Incoming requests by SafeWalk App users are received as notifications, which are displayed in a subwindow of the webpage titled "Requests." The window presents the admin user with a list of the requests, each with the following informations: name, phone number, and the location of the user waiting to be picked up. A request can be removed from the list by clicking on the red "X"; this also removes its associated marker.

<b>How is the geographic location of users determined?</b><br>
A third window allows the admin user to view the location of users who submit a request. The position is displayed using the Google Map interactive interface. The admin can see the name of the user placing the request by clicking marker designating their position.
