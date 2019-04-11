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


# Cleaning
sudo apt-get install chromium-browser --yes
