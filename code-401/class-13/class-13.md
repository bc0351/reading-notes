# Readings: Message Queues
Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading
[Socket.io Chat Example](https://socket.io/get-started/chat/)

1. Explain to a non-technical recruiter what the Chat Example (above) does.

    ```
    This chat example combines a couple different technologies to build out a chat app available over the internet.
    ```

2. What proof of life are we getting on the backend from the above app?

    ```javascript
    io.on('connection'...)
    ```

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

    ```javascript
    io.on('connection', (socket) => {
      socket.broadcast.emit('hi');
    });
    ```

[Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?

    ```
    channels; can be used to broadcast to subsets of clients.
    ```

2. How do you join a room?

    ```javascript
    io.on("connection", (socket) => {
      socket.join("some room");
    });
    ```

3. How do you leave a room?

    ```javascript
    io.on("connection", (socket) => {
      socket.leave("some room");
    });
    ```

[Namespaces](https://socket.io/docs/v4/namespaces/)

1. What is a Namespace and what does it allow you to do?

    ```
    A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").
    ```

2. Each namespace potentially has its own what? (hint: 3 things)

    ```
    event handlers; rooms; middlewares
    ```

3. Discuss a possible use case for separate namespaces

    ```
    your application has multiple tenants so you want to dynamically create one namespace per tenant
    ```

## Bookmark and Review

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
