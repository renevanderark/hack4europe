The Portal Thingy Hack4Europe Hackathon entry
=============================================

Description
-----------
This portal enables users to search the Europeana collections and to enrich it metadata using a local mongodb and remote API's.

Running out of the box
----------------------
On a Ubuntu/Debian distribution with Aptitude the ./go.sh shell script should run out of the box, installing all prerequisites and starting the portal on a local host. Installing the prerequisites can take a long time, seeing as the entire google V8 engine and node.js need to be built from source.

In order for the portal to actually do anything with the remote API's two API keys need to be entered in the file 
__ client/index.html.