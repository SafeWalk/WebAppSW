SafeWalk Webpage
============
This module of the SafeWalk project allows the administration of Macalester SafeWalk services to remotely manage the request placed through the SafeWalk android application (see SafeWalk module of this project).

The web interface utilizes two main outside dependencies. The first is Firebase, a real-time backend, which is used as the main avenue of communication with android application, to pinpoint user location, and hold login information for the client. It acts as an external server and requires no serve-side code. The second, google play services is used to create a map and its markers, to identify location of users who place a requests. 

##Getting Started with Firebase
<b>How does the web app interact with Firebase?</b><br>
The web app primarily connects with Firebase through the use of a web references. These directories provide the location of data, with each reference pointing to specific data. The web app uses javascript commands such as set,remove, update to manipulate data on Firebase. These commands update realtime, allowing the user app and web app to both detect changes immediately.

<b>What does it require?</b><br>
Utilizing Firebase primarily requires the use of a javascrip library they provide and a jquery library.

<b>How is it implemented?</b><br>
They are both implemented and linked using a script source in the head tag on the html page.

<b>How to access Firebase directly?<b><br>
To manage how the data is structured, accessing Firebase would be important.This can be done by visiting the Firbease website directly. Any changes to the data can be made directly on Firebase and would update to both the web app and user app. Many of the finer details of working with Firebase is provided in their developer docs.  

<b>Limitations</b><br>
The current of Firebase is developer mode. Which allows a maximum of 50 Max Connections, 5 GB Data Transfer, 100 MB Data Storage. If the app were to be published, scaled further a fee would be charged for firbase. 


## Getting Started with Google play services
<b>How is it implemented?</b><br>
The google play services is implemented using a script source in the head tag on the html page.

<b>What does it require?</b><br> 
It requires a google api library. Commands used to make the map and markers use functions defined in the api. 
