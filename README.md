# Vagrant 101

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Preriquisite

* Install Vagrant

### Notes

if you using Virtualbox as hypervisor please install this plugin

```sh
vagrant plugin install vagrant-vbguest
```

### Usage

Starting a virtual machine in Vagrant
```sh
vagrant up
```

To SSH into your new virtual machine
```sh
vagrant ssh
```

To halt the machine – that is, attempt a graceful shut down
```sh
vagrant halt
```

To start a previously-halted or suspended machine
```sh
vagrant resume
```

To perform a restart on your machine. A restart is the same as running ```vagrant halt```, followed by ```vagrant resume```
```sh
vagrant restart
```

If you’re permanently done with your Vagrant environment and want to fully remove it from your system
```sh
vagrant destroy
```