# TP DEVOPS - App Deployment

## Project

Creation of a simple web application and deployment using Vagrant, Ansible and Flask.


## Installation 

* Download VirtualBox
* Download Vagrant 
* Install Ansible : 
```
apt-get install ansible (linux)
brew install ansible (macOS) 
```
* Create the git environment : 
```
apt-get install git (linux)
brew install git (macOS)
```

## Roles installed 

* Sqlite
* Nginx
* Gunicorn
* Supervisord


## Usage 

1. Clone git repository
2. Place yourself in the Vagrant file (supersnake/Vagrant) 
3. Execute the command : ``` vagrant up —provision ```
4. Go to this url to see my flask app deployed : [http://localhost:5000/](http://localhost:5000/)


## Author Information

Margot LE ROUZIC 
Ingé 3C



