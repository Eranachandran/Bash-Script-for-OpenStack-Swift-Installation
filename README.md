Author: Eranachandran
Mail : eranachandrane@gmail.com

Website : http://pyronoidninja.com/
Date : 05-08-2019

Description: This bash script will install the Stein version of OpenStack with the keystone,glance,Swift and Horizon Services

Script type - Ubuntu Shell Script

Bash-Script-for-OpenStack-Swift-Installation

#Conf directory contains the preconfigured config files of the services. If you change the values of the variable in the bash script you should reflect the changes in preconfigured files.

#admin-openrc and demo-openrc contains preconfigured credentials if there are any changes in credentials, these files should be updated

Script Usage
Download and execute Source Code by as follows

git clone https://github.com/Eranachandran/Bash-Script-for-OpenStack-Stein-Installation.git

cd Bash-Script-for-OpenStack-Swift-Installation

bash Stein_Swift_Installation.sh <object_storage_disk_name>

This Script is tested with Ubuntu 18.04 LTS
