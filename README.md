Docker Practice

A simple Docker installation on Ubuntu.

Pre-requisite steps:

1. Be sure that virtualization is turned on in your BIOS.
2. Go to https://www.virtualbox.org/wiki/Downloads and download and install VirtualBox
3. Go to https://www.vagrantup.com/downloads.html and download and install Vagrant
4. Clone this repository to your machine via: `git clone https://github.com/NickMRamirez/dockerpractice.git`
5. Open a command-line prompt (Powershell on Windows) and navigate to the *dockerpractice* folder:

```
cd dockerpractice
```

5. Call `vagrant up` to create the Ubuntu virtual machine.

This VM has Docker already installed on it. To destroy the machine, call `vagrant destroy`. Or to just shut it down, call `vagrant halt`.

6. To SSH into the virtual machine, call `vagrant ssh`. Read this to learn about basic Linux commands for getting around the filesystem: https://www.digitalocean.com/community/tutorials/basic-linux-navigation-and-file-management

Once you're SSH'ed in, check that Docker is installed with `sudo docker version`.
