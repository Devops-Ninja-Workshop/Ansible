# Java
Ansible role for java

## Prerequisites
- Ubuntu or RedHat server
- Python installed on it

## Tasks
In [tasks](https://github.com/abhishek-ansible/java/tree/master/tasks) folder there are tasks file for Debian server and RedHat server.

### Version
In Debian server it will install java-oracle8 and in RedHat server it will install openjdk8.

## Running the Playbook
Change the host ip in the [hosts](https://github.com/abhishek-ansible/java/blob/master/hosts) file.

To run the playbook for RedHat and Debian server
```
ansible-playbook -i hosts site.yml
```
## Variables
The [vars](https://github.com/abhishek-ansible/java/tree/master/vars) folder contains the variable for tasks file.

