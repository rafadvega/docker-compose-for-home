# docker-compose-for-home

## Instructions

This repository is a compilation of docker-compose files to differents services that you can deploy in your home.

You must sustitute \<variable-name> by your own parameters.

## List

* Duck DNS Script
* Heimdall
* NextCloud
* OpenVPN
* Pi-hole
* Pigallery
* Plex server
* Samba server
* Serviio
* Transmission

## Open Ports

| Port  | Aplicación   | Protocol |
|-------|--------------|----------|
| 53    | Pi-hole      | tcp/udp  |
| 63    | Pi-hole      | udp      |
| 80    | Heimdall     | tcp      |
| 137   | Samba        | udp      |
| 138   | Samba        | udp      |
| 139   | Samba        | udp      |
| 443   | Heimdall     | udp      |
| 445   | Samba        | tcp      |
| 943   | OpenVPN AS   | tcp      |
| 1194  | OpenVPN AS   | udp      |
| 1900  | Plex         | udp      |
| 5353  | Plex         | udp      |
| 8443  | NextCloud    | tcp      |
| 8080  | Pi-hole      | tcp      |
| 8787  | PiGallery    | tcp      |
| 8888  | PiGallery2   | tcp      |
| 8895  | Serviio      | tcp      |
| 9091  | Transmission | tcp      |
| 9443  | OpenVPN AS   | tcp      |
| 23423 | Serviio      | tcp      |
| 23424 | Serviio      | tcp      |
| 32400 | Plex         | tcp/udp  |
| 51413 | Transmission | tcp/udp  |


###### Thans to linuxserver.io