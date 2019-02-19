# Ansible

- Ansible is so simple but still powerful!

Ansible allow you define Infrastructure as a code

It is agentless .There's no need to install Ansible in the target hosts. It will copy Python code using SSH and run from there. Only requirement is Python.

Use SSH  to connecto to host

Terminology:-
a. playbook :- A playbook consists of simple set of steps called tasks that run on remote machines defined in inventory file.  Files in YAML format that instruct Ansible on what to do


b. Tasks  :-  tasks can be defined as calls to ansible modules. They are executed from top to bottom. By default ansible run tasks synchronously. Synchronous tasks wait for the current task to complete before moving to the next task.

c. Inventory :- it’s an INI file with the list of groups of hosts that Ansible will use to run playbooks. also call host file

d. Roles  :-  A collection of tasks. Useful when you need to run a subset of tasks multiple times from different playbooks. Roles can also be parameterized so the behaviour is changed depending on the parameters passed.




Ansible installation:-

Via PIP :- 
# RedHat/CentOS/Fedora:
yum install python-pip
# Debian/Ubuntu:
apt-get install python-pip

Install Ansible:
$ pip install ansible

Install Ansible:

$ ansible --version
$ ansible --help



