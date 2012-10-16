Socket OAuth - A Socket OAuth Server Based on Akka
===========

This is a server experiment using Akka, where the communication will be over a web socket
that has been authenticated with OAuth.

Functionality
-------------

The functionality is very basic.  There will be a single endpoint where users connect with 
their OAuth token and can ask "Who am I?".  The server will then respond with the users
information.
