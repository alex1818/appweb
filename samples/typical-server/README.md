Tyical Server Sample
===

This sample shows how to embed Appweb using the full embedding API.

Requirements
---
* [Appweb](http://embedthis.com/downloads/appweb/download.ejs)
* [Bit Build Tool](http://embedthis.com/downloads/bit/download.ejs)

To build:
---
    bit 

To run:
---
    bit run

The server listens on port 8080. Browse to: 
 
     http://localhost:8080/

Code:
---
* [server.c](server.c) - Main program
* [appweb.conf](appweb.conf) - Appweb server configuration file
* [auth.conf](auth.conf) - User/Password/Role authorization file
* [cgi-bin](cgi-bin) - Directory for CGI programs
* [esp.conf](esp.conf) - ESP compiler rules
* [index.html](index.html) - web page to serve
* [web](web) - Web content to serve
* [start.bit](start.bit) - Bit build instructions


See Also:
---
* [min-server - Minimal server configuration](../min-server/README.md)
* [simple-server - Simple one-line embedding API](../simple-server/README.md)