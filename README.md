# mesos-marathon-vagrant
Very fast provision a local single mesos/marathon cluster.
It installs (mesos, docker, zookeeper, chronos and marathon)'s newest version on mesosphere repo.
## Usage 
```shell
git clone https://github.com/burakbostancioglu/mesos-marathon-vagrant.git
cd mesos-marathon-vagrant
vagrant up
```
Access
- Access to marathon:  localhost:8080  
- Access to mesos-master : localhost:5050
- Access to chronos : localhost:4400  
