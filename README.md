# virtual-instrument-client

Simple multi-player instrument example. 

Uses:
- [P5](https://p5js.org/) and [P5.sound](https://p5js.org/reference/#/libraries/p5.sound) for playing sounds and visualisation
- [Socket.io](https://socket.io/) for communication between server and clients 

## Listen
Listens to Socket.io server (default http://localhost:8000, may be changed based on your server setup).

When a signal comes from the server, plays a predefined sound file. 

## Play
You can also send a signal to the server from the client.

Keyboard: ```A, S, D``` keys or  
Click/touch: ```A, S, D``` buttons on the screen

## Visualisation
Displays a simple visualization 

## Sample sounds from Ian

https://drive.google.com/drive/folders/1GsKzjNp6p_WkLCfpiQ528QcHLn36-eG-

## Installation

No extra steps needed, just run it in some http server. 
