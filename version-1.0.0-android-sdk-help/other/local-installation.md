The workspace has a folder called advanced-local-install inside the start-here folder

This folder is for installing a local version of Cloud9 to help test Dockerfiles before uploading them to Cloud9 for review and compilation. 

The steps are:

1. copy "on-your-computer.sh" file to a Docker capable computer (I copy and use sudo nano on-your-computer.sh then right click paste it)
2. run  bash on-your-computer.sh (wait 15 minutes and about 7 Gigabytes)
3. cd /home/ubuntu/start-here/advanced-local-install
4. ls
5. bash load-local.sh






the main files are called

1. 001-cloud9.conf	an apache2 site-available file set for port 8081 

1. load-local.sh	after the Docker installation this is the file to find and run to set Apache to port 8081 since the Docker install is using port 8080

1. on-your-computer.sh	A bash file to be copied to your Docker capable computer Note: these files take a lot of band width expect 7G per time you run this file. I use sudo nano on-your-computer.sh and right click paste the copied file.
 
1. ports.conf an apache2 configuration file set for port 8081


.
