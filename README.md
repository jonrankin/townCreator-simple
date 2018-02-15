# Procedural Town Generator For Tabletop Games

A web application that creates a randomy generated town for Tabletop games by rolling dice and using tables to determine the outcome.


## Installation

The application supports Ansible which will install all required services, code, and configurations to run on a fresh linux ubuntu system.

NGINX will run on port 80 proxying to the flask app on localhost port 8000.

To install just enter these commands:
```
sudo apt-get update
sudo apt-get install ansible
wget https://raw.githubusercontent.com/jonrankin/townCreator-simple/master/townCreator.yml
ansible-playbook townCreator.yml
```

