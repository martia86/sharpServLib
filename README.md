# sharpServLib
A library for creating WebServers in C#.

- sharpServ
   - Constructor
      Creates a new instance of the sharpServ.
      Takes either port or full address.
   - addRespone
      Adds a response to the responses.
      Takes either a callback function or a file address to send.
      Example: `addResponse("/FAQ", "/FAQ.html");`
   - listen
      Starts the sharpServ instance.
      Takes either nothing or a callback to execute after server start.
- WebServer
   - Constructor
      Takes callback methods and either prefixes as a IReadOnlyCollection or a string.
      Creates a new instance of a WebServer.
   - Run
      Starts the instance of the WebServer.
      No input needed.
   - Stop
      Stops the instance of the WebServer.
      No input needed.
