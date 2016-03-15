# A7kili
Client Server chat multiplatform application based on Qt framework

For each subscribed user, the server manages a folder that contains two separate files for storing the received and sent messages.

Each subscribed client can see the other connected users and send them instant messages via the chat interface.
On the other hand, when a client is disconnected, the server stores locally any message destined to the latter and transfer it later when the corresponding user is online.
On every new connection, on the chat interface, each client gets a notification of the number of new unread messages that he can consult in his inbox window.

On the server side, exchanged messages can be seen using the log function as well as the connected clients. 


#Building the app
Before building the application please make sure to set correctly the server Ip address and port. (by default the client tries to connect to the server on local machine)
By default the server listens on port 50885.

#Screen Shots
![alt tag](https://raw.githubusercontent.com/samy-/A7kili/master/img/Subscription.png)
![alt tag](https://raw.githubusercontent.com/samy-/A7kili/master/img/ConnectionInterface.png)

![alt tag](https://raw.githubusercontent.com/samy-/A7kili/master/img/chat.png)
![alt tag](https://raw.githubusercontent.com/samy-/A7kili/master/img/Server_Connected_clients.png)

![alt tag](https://raw.githubusercontent.com/samy-/A7kili/master/img/NewMessages.png)
![alt tag](https://raw.githubusercontent.com/samy-/A7kili/master/img/receivedMessages.png)

#License & Copyright
MIT licensed, see LICENSE file.
