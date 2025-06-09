# WListener
## About WListener
WListener is a FOSS HTML app for listening and reading packets in WS/WSS servers. It has a simple interface to set the server to listen on, and start the listener. The project is completely built in Turbowarp, and the SB3 file is available as the source code.
## How To Use
WListener is simple to use. First, press "Set Server" to get a small pop-up yo enter the WS/WSS URL. Then, press "Start Listener" to start the listener. It's that simple.
## How To Read The Terminal
Anything starting with ```!!``` is just a notifier about something that has happened or started. Any line with ```PENDING``` means an action has started, but not finished. Anything with ```FINISHED``` means an action has finished. Any line with ```CRITICAL``` shows an unpassable error has occoured. Any line with ```ERROR``` means there was an error that was not critical enough to stop the listening process. When recieving packets, and line with ```NEW GLOBAL PACKET``` reads out a new global packet that was recieved. ```NEW DIRECT PACKET``` does the same besides it reads out new direct packets.
