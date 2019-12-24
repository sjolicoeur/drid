# DRiD

Diagnose Repair install Drone (DRiD) is a process running to enable maintenace of VM or Jail. It is meant to be light on resources to enable diagnosis and repair of an environment based on scripts that are uploaded to it. 

Said scripts can be BASH or Python based as the drone will be able to install a proper isolate python environment for the  scripts. 

Because of it's ability to run scripts it is able to use it to install other programs, time will tell if this feature will remain.

# Installation

- create a certificate and a ca
- deploy a binary for your OS
- configure it to be started as per your choice (supervisord, rc.d, systemd)
- configure the location of the certificates in `/etc/drid.conf`
