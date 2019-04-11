# Rpi_Basics

# Update upgrade
$ sudo apt-get update

$ sudo apt-get upgrade

$ sudo apt-get dist-upgrade


# Stretch 
$ sudo sed -i /deb/s/jessie/stretch/g /etc/apt/sources.list

$ sudo sed -i /deb/s/jessie/stretch/g /etc/apt/sources.list.d/*.list

# Cleaning
$ sudo apt-get autoremove

$ sudo apt-get autoclean


# Chromium
sudo apt-get install chromium-browser --yes


# VNC
sudo apt-get install realvnc-vnc-server

# Set Date and Time
sudo date -s "Thu Aug  9 21:31:26 UTC 2012"
