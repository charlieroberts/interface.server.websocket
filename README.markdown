Interface.Server.WebSocket
====================

This module is used to send / receive websocket messages inside Interface.Server.

To use it, make sure you have `websocket` declared as a transport inside the Interface.Server config file and have the module installed. You also need to configure a port for the WebSocket server to run on. Here's an example transport section that will start a WebSocketServer:

```js
transports: {
  websocket: {
    webServerPort: 9080
  }
}
```

There is a test file in the `tests` directory of main interface.server repo that you can load in your browser to test this.