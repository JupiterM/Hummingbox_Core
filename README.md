This repo contains the files needed to set up a Vagrantbox which uses Ansible to install Miniconda and Hummingbot.\


**Getting Started**

First- Vagrant needs to be installed on machine:\
https://developer.hashicorp.com/vagrant/docs/installation\

Creating Vagrant box:
  After downloading repo, cd into directory and run command: `Vagrant up`.\
  First time installation can take ~10 minutes. On eompletion of installation a debug message will appear informing of how to log in and access hummingbot.\
  If for any reason installation is interrupted, running `Vagrant provision` will restart the process while skipping over the secions which have been completed.\
  Please note that this is not a virtual environment, but a completely separate virtual machine.\
  Hummingbot is installed into 'src' directory which is accessible on host machine.\
  Vagrant automatically sets up networking in creation of VM, so there is nothing to do there.\
  

