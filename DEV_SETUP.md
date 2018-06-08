# Setup the development environment for curator

For testing, use vagrant with VirtualBox on you local machine.

## Install coreos-vagrant

Follow the direction here: https://github.com/coreos/coreos-vagrant

This will have you install VirtualBox and Vagrant

Note that VirtualBox requires the system it is running on to support VT-x.  If this is a VM, then nested virtualization must be enabled.

## Install Ansible on the Vagrant host

sudo pip install ansible

## Install Packer on the Vagrant host

Download build: https://www.packer.io/downloads.html

Unzip it into /usr/local/bin

## Instal Config Transpiler

Download: https://github.com/coreos/container-linux-config-transpiler/releases/download/v0.9.0/ct-v0.9.0-x86_64-unknown-linux-gnu

copy it to /usr/local/bin ( cp ct-v0.9.0-x86_64-unknown-linux-gnu /usr/local/bin/ct )

chmod 755 /usr/local/bin/ct