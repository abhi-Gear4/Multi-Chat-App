
This project was based on my course CSE-5306 Distributed System.
It was developed in 3 phases. In each phase I have implemented different concepts of Distributed System.

Phase 1:
In this phase, I have implemented simple multiple clients - server application which support Unicast, Multicast and Broadcast messages.
 Code Structure:

Each phase contains 3 files. 
- ServerView.java - code for server. This class must be run first.
- loginClient.java - code for client's login and run after the server has been started. It can be run as many number of times depending upon number of clients required.
- ClientView.java - code for the client.

Phase 2:
In this phase, I have implemented functionality where a client can send message to offline client too. I have used activemq (messaging queue) to implement this feature.
Messaging queue is java based messaging server (https://activemq.apache.org/).

Steps to Run:
- Download activemq in your computer. Start activemq at local server using command line. Just open cmd/terminal and navigate to the bin folder of the downloaded activemq and run the command `start activemq`.
- Now you can check the queues on the UI of activemq. You can check out other videos on youtube on how to use activemq.
follow phase 1 steps......!!

To implement offline client messaging. I am sending all the messages to the activemq first and then fetching from there to send it to the intended clients


References:
https://www.youtube.com/watch?v=rd272SCl-XE
https://www.youtube.com/watch?v=ZzZeteJGncY
