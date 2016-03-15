# A7kili
Client Server chat multiplatform application based on Qt framework

For each subscribed user, the server creates a folder that cotaines two seperate files for the received and sent messages.
Each subscribed client can see the other connected users and send them instant messages via the chat interface.
When Client is disconnected, the server stores locally any message destined to the latter and transfer it later when the corresponding user is online.
For each new connection, on the chat interface, each client gets a notification of the number of new unread message that he can consult in the inbox window.

On the server side, exchanged messages can be seen using the log function as well as the connected clients. 


#Building the app
Before building the application please make sure to set correctly the server Ip adress and port. (by default the client tries to connect to the server on local machine)
By default the server listens on port 50885.

#License & Copyright
MIT licensed, see LICENSE file.
