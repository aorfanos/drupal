## Ansible role for Drupal installation

### Prerequisites

**Python** on target host. 

### What will be installed
- Drupal (whatever version, default is 7.63)
- mysql-server
- Nginx
- PHP packages

### What will be created

A Drupal installation ready to use (database + webserver configuration). After playbook execution you are ready to land on domainname/install.php.

### How to use

Add the IP or hostname of the target host on your Ansible hosts file, or create a simple playbook calling the role.

### Demo run

[Demo playbook run](https://asciinema.org/a/COkrFUIahJf97m3jToxslGGZF)