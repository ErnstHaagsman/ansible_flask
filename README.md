Vagrant and Ansible Basic Example
=================================

This repository contains the basics for developing a Flask application
within a Vagrant VM, using Ansible for provisioning.

See the accompanying blog post on the PyCharm blog to read more about
developing within a VM.

Ansible Vagrant Examples
========================

This repository contains a collection of example virtual machines running various applications. The VMs are created via Vagrant and provisioned via Ansible.

You can cd into any of the included directories and run vagrant up, and a generic Linux VM will be booted and configured in a few minutes. You just need to install Vagrant, VirtualBox, and Ansible. View the included README.md file in any of the subdirectories to find out more about the particular VM.

All of these examples use a combination of roles I've added to Ansible Galaxy, and were created to help demonstrate Ansible's simplicity and flexibility.

Read more about Ansible and how I use it to manage infrastructure in Ansible for DevOps, a book I've written.

Usage
-----

To start developing, you need:

- [Vagrant](https://vagrantup.com)
- Virtualization software compatible with Vagrant, like 
  [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
  
Check out this repository on your computer, and then run `vagrant up`
to start and provision the VM.

On provisioning, a virtualenv will be created in `/home/vagrant/venv`
with the packages listed in `requirements.txt`.
