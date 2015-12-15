# WebSocketsSample
Simple WebSockets comunication example for InterSystems Caché

## Functionality

There are currently 3 actions availible:

- Echo - echoes text (or object) back to client
- Get Variable - receives and displays local (eg. ```a```) or global (eg. ```^a```) variable value. Subscripts availible (eg. ```^a(1)```).
- Set Variable - sets local or global variable value. Subscripts availible.


## Installation

1. Download and import all files into any namespace
2. Compile
3. Open index.html in your web browser, for example URL: ```http://server:port/webapp/index.html```
4. In there fill:
  - WebSocket: ```server:port/webapp/WebSockets.Main.cls``` (check value, fills automatically on page load)
  - User: Cache Username
  - Password:  pass for Cache User
5. (Optional) Open browser console
6. Press "Start WebSocket" button 
7. You can start testing websockets

## Developement

This project uses [cache-tort-git](https://github.com/intersystems-ru/cache-tort-git) as a source control plug-in. 
