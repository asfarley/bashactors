Bash Actors
===========

To launch:
```
./Launch
```

To stop:
```
./Stop
```

A minimal implemention of the [Actor model](https://en.wikipedia.org/wiki/Actor_model) using Bash scripting. 

The root folder contains one (and only one) folder for each actor. Each actor's behavior is described by a single Bash script. Messages are passed by creating files under each actor's Inbox subdirectory. 

A new terminal process is launched for each actor. Actors can be launched individually by manually running the appropriate Actor script, and they can be shut down individually by placing a file in the Inbox containing only the following line:
```
stop
```

Tested on Ubuntu 14.04. 
