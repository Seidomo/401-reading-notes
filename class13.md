### CLASS 13


# Message Queue



## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)



### What does it mean that web sockets are bidirectional? Why is this useful?

- Bidirectional is a communications mode that is capable of transmitting data in both directions to send and receive, but not at the same time.


### Does socket.io use HTTP? Why?

- Yes it can.


### What happens when a client emits an event?

- when the client emits an event will get to the listner on the server side and an event is triggered.


### What happens when a server emits an event?

- When our server emits events which match the first 'event' argument the callback will be run. Inside these callbacks we can take the actions we want on the client-side.


### What happens if a client “misses” an event?

- The events will be ignored.

### How can we mitigate this?

- you can mitigate this by having event handlers with some kind of logic.




## TERMS:



* ``` Socket ```


* ``` Web Socket ```

The WebSocket is a way to exchange data between browser and server via a persistent connection. The data can be passed in both directions as “packets”, without breaking the connection and additional HTTP-requests.

* ``` Socket.io ```


- Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for Node.js


* ``` client ```

* ``` Server ```

* ``` OSI Model ```

* ``` TCP Model ```

* ``` TCP ```

* ``` UDP ```

* ``` Packets ```