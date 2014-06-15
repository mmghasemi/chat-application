Video and Voice Chat Application With Jitsi
============

eXo Chat is an Instant Messaging application for eXo Platform 4.
Thanks to [Jitsi](http://www.jitsi.org) and their powerful videoBridge Module, it’s even possible to benefit from Video Conferencing (One to One, Conference) and Screen Sharing from within eXo Chat.



Technically speaking, this Chat application comes with a client project (/application) and a server project (/server). All the Chat data is stored using MongoDB for storage.
Server can run on the same Java Application Server but as it's a near to real time application and can process a lot of data, it's recommended to use the Chat Server as a standalone application on another AS.
Thus, Chat Client portlets will run on an eXo Platform based App Server, where the Chat Server can run on a standard tomcat installation.




Be Up and Running
===============

One Tomcat Server mode
----------------

Jump to Wiki Install Page : [under construction](https://github.com/exo-addons/chat-application/wiki/One-Server-Mode)





