Client Documentation
====================

<b>SafeWalk is a mobile app that allows Macalester College students to contact Safewalk services with only the touch of a button.</b> <br>
A web interface has been implemented for this project to allow SafeWalk employees to set the availability of their services and  to manage the incoming requests.

<b>How do SafeWalk employees access the web interface?</b><br>
Only prior authorized users, meaning a their user information is already set in the system, can and are allowed access to the webpage through a login system. Once logged in, the webpage displays three interactive interfaces, to set availibility and managed requests.  

<b>How is the availibility changed and how are the users notified?</b><br>
The admin user can change the availability of their services to three different status: "AVAILABLE", "BUSY", "NOT AVAILABLE". Three interactive buttons, which interacts with an external server (Firebase), allows real-time update of the status on all android SafeWalk app, notifying all the users.

<b>How are incoming notifications received and managed?</b><br>
Incoming notifications requested by the SafeWalk App users are displayed in a subwindow of the webpage titled "requests". The window presents the admin user with a list of the request, each with the following informations; name, phone number and the location of the user waiting to be picked up. The request can be removed from the list by clicking on the red "X" icon.

<b>How is the geographic location of users determined?</b><br>
A third window allows the admin user to view the location of users who submit a request. The position is displayed using the Google Map interactive interface. The admin can see the name of the user placing the request by clicking marker designating their position.
