SpringJMSActiveMQ
=================

A simple Spring JMS example using ActiveMQ

Description
-----------

After configuring the broker url in the ./src/main/resources/resources.properties file, run the 
MessageReceiver and then the MessageSender class. 

Both beans contain a main method. The MessageSender class will terminate after the sending of each message but
the MessageReceiver bean will continue to run to receive messages.
