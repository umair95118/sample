CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ# sample

#Introduction
This is sample code that shows how server sent events can be used for notifications, Server-Sent Events (SSE) is a server push technology enabling a client to receive automatic updates from a server via HTTP connection, for complex production scenarios where scaling is required, message brokers / queues can be added to manage data and inter process communcation between various services thus making sure that data is not lost in an event of power failure or other network related issues, a common msg format can be worked on in json to capture various commands / states that a machine may possess.

#Requirements

*Server
.net core 3.1
docker

* Client (work in progress)
angular 6+

#Recommended Modules
A separate logging mico service would capture all command activities and history related data. The loggind related data can be stored in a RDBMS, e.g SQL or POSTGRES.

# Installation
Downlaod server and use the following command to run, "dotnet run", the serve listens for incoming requests on port 5000
Download client and the use the following command to run "ng serve".

# Configuration
Both the server and client can be configured to work on different ports and endpoints can also be configured as per the requirements.

# Troubleshooting
CORS related issues - may need to configure proxy.json to fix cors related errors.


