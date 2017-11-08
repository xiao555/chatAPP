## chatAPP
An online live chat app embedded in HTML by Vue Component and Socket.io

Change the [official Demo](https://github.com/socketio/socket.io/tree/master/examples/chat) into Vue components. And increase the unread message reminder function.

### How to use

```javascript
// Start socket server
$ npm install
$ npm start

// Start socket client
$ cd chatAPP && npm install
$ npm run dev
```
And point your browser to `http://localhost:8080`.

> NOTE: If you want to use this component, please don't forget to change the `url` in `mounted` function to your `socket server`.

### Features

* Multiple users can join a chat room by each entering a unique username on website load.
* Users can type chat messages to the chat room.
* A notification is sent to all users when a user joins or leaves the chatroom.
* The number of unread messages will be shown on the button when logged user close there chat box

### LICENSE
MIT
