# Readings: Socket.io

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading
[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

1. What is a Web Socket?

    ```
    a computer communications protocol, providing full-duplex communication channels over a single TCP connection
    ```

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

    ```
    the WebSocket handshake uses the HTTP Upgrade header[3] to change from the HTTP protocol to the WebSocket protocol.

    a persistent connection is used, meaning lower overhead.
    ```

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

    ```
   request
    ```

[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

1. What does the event handler io.on() do?

    ```
    flips the connection on.
    ```

2. Describe some possible proof of life or proof that the code works as expected

    ```javascript
    test("should work", (done) => {
      clientSocket.on("hello", (arg) => {
        expect(arg).toBe("world");
        done();
      });
      serverSocket.emit("hello", "world");
    });
    ```

3. What does socket.emit() do?

    ```
    replicates emitting event, on socket connection
    ```

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

    ```
    Websocket is the communicationprotocol. socket.io is a library that uses the WebSocket protocol to provide the interface.
    ```

2. When would you use Socket.IO?

    ```
    when you need to braodcast and/or have fallback options.
    ```

3. When would you use WebSockets?

    ```
    when you don't need to braodcast and/or have fallback options.
    ```

## Videos

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

1. What are a couple of key takeaways from this video?

    ```
    There are many layers to consider to fully consider a viable solution.
    ```

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

1. Translate the gist of this video to a non-technical friend

    ```
    whenever logging on to a web page,  a session is created. data is transferred over that session while browsing the web site, then the session closes once you leave the website.
    ```

### Bookmark and Review

[Socket.io Documentation](https://socket.io/docs/)

[Socket.io Server API](https://socket.io/docs/server-api)

[Socket.io Client API](https://socket.io/docs/client-api)

[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)
