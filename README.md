Tic Tac Toe
forthebadge ForTheBadge built-with-love forthebadge forthebadge

A network based Tic tac toe game, this implementation was done as the java project @ ITI intake 40 by students of the open source cloud platform development track.

hg

Contents
Getting Started
Prerequisites
Installing
Diagrams
Class Diagram
Database Schema
Features
Feature 1
Getting Started
There are two ways to run the project.

-First through the terminal and jar files. open the terminal and cd to the Server jar file directory and run:

java -jar ./Server.jar
the server dashboard will pop up and the server should now be listening to requests on the localhost port 5005

Next open another terminal and cd to the Client jar file directory and run:

java -jar ./Client.jar
and the login screen should open bare in mind the jar files are made that the client and the server both run on the same machine if you want to run them on different machines one small change should be made and it's to change the connection ip in the Client project in a class called PlayerSoc.java from 127.0.0.1 to the ip of the machine which the server is runing on.

-Second through the projects it's as easy as running the Server project first then the Client project.

Prerequisites
java 8u111 or higher recommended

Give examples
Installing
A step by step series of examples that tell you how to get a development env running

Say what the step will be

Give the example
And repeat

until finished
End with an example of getting some data out of the system or using it for a little demo

Features
Client Side Features:
-login
-SignUp
-play with pc with 3 difficulty levels
-play with online friends
-chat while playing
-have an avatar and score level
-see who has the highest score in the game
-see who is online offline or busy playing with someone else

Server side Features:
-see a list of all users
-see players status and score
-close and reopen the server


Deployment
Add additional notes about how to deploy this on a live system

Built With
JFoenix -JavaFX Material Design Library
Ikonli -Icon packs for Java applications
AnimateFX -A library of ready-to-use animations for JavaFX
Maven - Dependency Management
MySQL - JDBC Type 4 driver for MySQL
JSON-Simple - A simple Java toolkit for JSON
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

Authors
Billie Thompson - Initial work - PurpleBooth
See also the list of contributors who participated in this project.

License
This project is licensed under the MIT License - see the LICENSE.md file for details

Acknowledgments
Hat tip to anyone whose code was used
Inspiration
etc
