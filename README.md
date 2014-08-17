Client
======

Ragnarok Tales Client - www.ragnaroktales.com


roBrowser
=========
To install the proxy in windows:

go to : http://nodejs.org/
and install node.js

Then open a terminal and write:
npm install wsproxy -g

Then you just it to run it (in terminal) :
wsproxy -p 5999
wsproxy --ssl true 5999

And modify your ROConfig with your new settings:
socketProxy: "ws://192.186.2.41:5999/",