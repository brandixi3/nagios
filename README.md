# Nagios
This is for Docker file for Nagios Server Docker container

### Versions

* Ubuntu 14.04
* Nagios® Core™ Version 3.5.1

Installation Steps for Nagios Server.

1. Pull the Docker Image,
docker pull brandixi3/nagios

2. Start the Docker container as follows,
docker run -p 80:80 -t -i brandixi3/nagios /bin/bash

Now you can access Nagios dashboard using , http://server_ip/nagios3/

Initial credentials are as follows,

Username : ngiosadmin
Password :

