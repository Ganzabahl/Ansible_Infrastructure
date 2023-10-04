# Ansible_Infrastructure
Ansible collection for automating trivial tasks in Ansible.
This repository will be expanded over time.

There is a stand-alone playbook for automatic updating of several distributions. 

For a more streamlined approach the role "updates", is being added.


## Note: 
Things that are still being debugged or not priotized:
The role is working when using stand-alone Ansible. 
When testing with ansible-semaphore I however get some "apt locked" and "require root" issues despite become is set to true.
OpenSuse works with Leap. Thumbleweed and MicroOS is not yet supported by this playbook.
