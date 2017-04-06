alpine-nmap
======
[![Docker Repository on Quay](https://quay.io/repository/dockerized89/routersploit/status "Docker Repository on Quay")](https://quay.io/repository/dockerized89/routersploit)

## Dockerfile for nmap using Alpine. (https://nmap.org/)
 
Example Usage:
-----

#### View help:
    docker run --rm dockerized89/nmap
    
#### Example scan:

    docker run dockerized89/nmap -v -sn 192.168.0.0/24

