# Ansible Role: apache_tomcat
=========

A simple Ansible role for installing and configuring apache-tomcat9 for RHEL/CentOS 7 and Debian 10.

- Install the necessary packages;
- Create configuration file;


Requirements
------------

- The SELinux and firewall settings are not considered to be a concern of this role.

Role Variables
--------------


Variables below are required

| Variable                                     | Default                       | Comments                                                                                
|                                              |                               |
| :---                                         | :---                          | :---       
|                                              |                               |
| `admin_gui`                                  |                               | Inform administrator name for web manager
|                                              |                               |
| `admin_gui_pass`                             |                               | Inform administrator pass for web manager
|                                              |                               |



Dependencies
------------

You need to install python-apt package on debian 10 


Example Playbook
----------------

---
- hosts: redhat,debian_10

  roles:

    - /path/apache_tomcat

...

## Contributing

Issues, feature requests, ideas are appreciated and can be posted in the Issues section.


Author Information
------------------
LinkedIn: https://br.linkedin.com/in/almircandido
