Raspberry Stats
===============

Hello there!

Have you ever wondered how your Pi is doing?
What if you had a smart and super-awesome way to find out using nothing more than **NodeJS** and your web browser.
It makes use of hosting the User Interface with NodeJS and the streaming of data with Socket.io so that the stats you're seeing are realtime.


___


Screenshots :
-------------
![alt text][logo]

[logo]: http://i.imgur.com/TeyMIRJ.png "The UI front-end."
[logo]: http://i.imgur.com/CNNpubV.png "Highcharts is used to make charts."


___


Dependencies :
--------------

The code depends on the following : Socket.io and Connect (Node).
You can install them using NPM with the following commands :

	npm install connect socket.io


___

How to install :
----------------

You can install the program using the following method in a(n) (SSH) terminal :

	#install all of the programs needed to run this.
	sudo apt-get install nodejs npm git
	
	#Clone this repository.
	git clone https://github.com/96AA48/raspberry-stats.git
	
	#Go inside the folder
	cd raspberry-stats
	
	#Install the needed NodeJS modules.
	npm install socket.io connect
	
	#Run the program
	sudo nodejs app.js

___


Disclaimer
----------

Hey there! Thanks for reading/using/editing this code, I just wanted to say a couple of things :

The code was made with the use of nothing more than the knowledge that I have of Javascript and NodeJS.
This means that I can't guarantee that the code is efficiënt, accurate and/or creates reliable information.

If there is any trouble setting this up, make an issue on this Github/Gitblit page and I'll help you as soon as I can.

You can also email me at : **96aa48 [at] gmail.com**

 
Thanks !
