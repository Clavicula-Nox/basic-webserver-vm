Basic Web Server VM
===================

**Requirements**

  * [Ansible](http://docs.ansible.com/intro_installation.html)
  * [Virtualbox](https://www.virtualbox.org/wiki/Linux_Downloads)
  * [Vagrant](https://www.vagrantup.com/downloads.html)

**Reporting an issue or a feature request**

Issues and feature requests are tracked in the Github issue tracker.

**DO NOT USE THIS IN A PRODUCTION ENVIRONMENT**

VM Configuration and parameters
-------------------------------

  * All parameters are in ansible/vars/all.yml
  * You'll also have to configure this file manually : Vagrantfile

VM Provisioning
---------------

  * Run your virtual machine: `vagrant up --provision`
  * Connect through SSH to the virtual machine: `vagrant ssh`

Host configuration
------------------

For more convenience, setup local hosts on your **host machine**

```
sudo /bin/bash -c 'echo "192.168.45.99 dev.domain.ltd" >> /etc/hosts'
```

## VM Configuration and parameters
=======

