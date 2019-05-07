# vagrant_project_d

## Description:
This repository provides to you **Ubuntu Xenial Box** configured as follows:
- 2 CPUs
- 2 GB of RAM

## Files:
- `Vagrantfile` - Contain vagrant box configuration

## Requiered software:
- In order to use Vagrant you need to have **Virtualbox** tool installed.
- In order to use the already configured **Vagrantfile** you require **Vagrant** tool installed.

### Instructions HOW to install `Virtualbox`
- Go to [Virtualbox downloads](https://www.virtualbox.org/wiki/Linux_Downloads) choose **Virtualbox** package
- Type in your terminal: `sudo apt-get install -y virtualbox `

### Instructions HOW to install `Vagrant`
- Download **Vagrant** from [here](https://www.vagrantup.com/downloads.html)
- Click on following link: [Installing vagrant](https://www.vagrantup.com/docs/installation/)

### Instructions HOW to run this project on your computer
- Download the content of **berchev/vagrant_project_d** repository: `git clone https://github.com/berchev/vagrant_project_d.git`
- Change to downloaded **vagrant_project_d** directory: `cd vagrant_project_d`
- Type `vagrant up` 
- Type `vagrant ssh` in order to connect to your Ubuntu Xenial Box via ssh
- Type `exit` in order to close the ssh connection
- Type `vagrant halt` in order to power off the Ubuntu Xenial Box
- Type `vagrant destroy` if this project is no longer needed

### TODO
