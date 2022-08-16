# DistributedWhiteboard
A collaborative whiteboard that allows multiple participants to draw simultaneously on a canvas, designed using Java sockets.


This implementation of collaborative whiteboard provides features such as : freehand drawing, inputing text, drawing shapes such as lines, circles, triangles, rectangles. It also provides a file menu with New, Open, Save and SaveAs options, to be controlled only by the manager (in this implementation it is the Server). The application also provides a chat box function to enable communication between users. Sockets and threads are the lowest level of abstraction used in this project for network communication and concurrency. 


The Server can be invoked in 2 ways- 

(i) By running 

```java -jar StartWhiteBoard.jar <IP> <port> <username> ```


(ii) By running 

```java -jar StartWhiteBoard.jar```
i.e if no arguments are passed the default IP, port and name are 127.0.0.1, 4444 and Server respectively 


The Client can also be invoked in 2 ways- 

(i) By running 

```java -jar JoinWhiteBoard.jar <IP> <port> <username> ```


(ii) By running 

```java -jar JoinWhiteBoard.jar ```
i.e if no arguments are passed  the default IP, port and name are 127.0.0.1, 4444 and “no name” respectively.
