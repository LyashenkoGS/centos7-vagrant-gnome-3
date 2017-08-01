# CentOS_7.2-desktop dev environment

It's often convenient to an isolated environment to investigate and debug old school projects which require a lot of dependencies and libraries with a particular version. Vagrant allows to bootstrap such environment in repeatable 
and automated fashion.

## Prerequisites
* Vagrant 1.9.7
* VirtualBox 5.1.22 

## How to run

    vagrant up

default login:password vagrant:vagrant

## Develop tools list
Additional tools that has been added to [https://app.vagrantup.com/boxcutter/boxes/centos72-desktop](https://app.vagrantup.com/boxcutter/boxes/centos72-desktop)

* git
* CLion with OS X keymap
* standart developer tools (yum groupinstall "Development Tools")



