Bash Actors
===========

To launch:
./Launch

To stop:
./Stop

A minimal implemention of the Actor model using Bash scripting. 

The root folder contains one (and only one) folder for each actor. Each actor's behavior is described by a single Bash script. Messages are passed by creating files under each actor's Inbox subdirectory. 

A new terminal process is launched for each actor. 

Tested on Ubuntu 14.04. 
