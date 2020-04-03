# FreeIPA lab

Local FreeIPA environment based on Vagrant.   
**This deployment is not secure: Do not use for production purposes**

## What it contains?

This repository contains three Vagrant files corresponding to three virtual machines:
* FreeIPA master
* FreeIPA client that will be automatically enrolled
* FreeIPA client for manual enrolling

## How to use it?

In Fedora:
1. Install libvirt and the @virtualization group: `sudo dnf install @virtualization libvirt`
2. Install vagrant and vagrant-libvirt: `sudo dnf install vagrant vagrant-libvirt`
3. Set the Vagrant default provider: `export VAGRANT_DEFAULT_PROVIDER=libvirt`

Now you are ready to execute `vagrant up` in the different folders in order to start the virtual machines. For more information review the [Vagrant documentation](https://www.vagrantup.com/intro/getting-started/).
