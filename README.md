SafeWalk Webpage
============
This module of the SafeWalk project allows the administration of Macalester SafeWalk services to remotely manage the request placed through the SafeWalk android application (see SafeWalk module of this project).

The web interface utilizes two main outside dependencies. The first is Firebase, a real-time backend, which is used as the main avenue of communication with android application, pinpoint user location, hold login information for client. It acts as an external server and requires no serve-side code. The second, google play services is used to create the map and markers, to identify location of user who place requests. 

##Getting Started with Firebase
<b>How does the web app interact with Firebase?</b><br>
Using a Firebase reference as starting point for the location of a particular data, the web app uses javascript commands such as set,remove, update to manipulate data on firebase. These commands update realtime, allow the user app and web app to both detect changes. 

<b>What does it require?</b><br>
Utilizing firebase primarily requires the use of a javascrip library they provide and jquery library.

<b>How is it implemented?</b><br>
They are both implement and linked using a script source in the head tag on the web page.

<b>Limitations</b><br>
The current of Firebase is developer mode. Which allows a maximum of 50 Max Connections, 5 GB Data Transfer, 100 MB Data Storage. If the app were to be published, scaled further a fee would be charged for firbase. 


## Getting Started with Google play services
<b>How is it implemented?</b><br>
The google play services is implemented using a script source in the head tag on the the web page.

<b>What does it require?</b><br> 
It requires a google api library. Commands used to make the map and markers use function defined in the api. 
