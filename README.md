# vagrant-centos7-jupyter
Vagrant file to bring up a CentOS7 virtual machine with python3 installed from source and jupyter installed from source.
Jupyter is accessible from the outside. 

Connect via localhost:8080 on the host.

## Vagrant commands

Run these commands in the folder where the *Vagrantfile* file is located.

Install or bring up vagrant controlled machine
$ vagrant up

Reprovision vagrant controlled machine
$ vagrant provision

Remove vagrant controlled machine
$ vagrant destroy