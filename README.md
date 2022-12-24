Role Name
=========

This role installs and configures Zabbix Agent 5 to the server that you want to monitor.

Requirements
------------

This role only works for Ubuntu 18.04, Ubuntu 20.04 and CentOS7

Role Variables
--------------
- srvname: Server=<Zabbix_Server_IP>
- srvactive: ServerActive=<Zabbix_Server_IP>
- centos_url: rpm -Uvh https://repo.zabbix.com/zabbix/5.0/rhel/7/x86_64/zabbix-release-5.0-1.el7.noarch.rpm
- ubuntu_url_focal: https://repo.zabbix.com/zabbix/5.0/ubuntu/pool/main/z/zabbix-release/zabbix-release_5.0-1%2Bfocal_all.deb
- ubuntu_url_bionic: https://repo.zabbix.com/zabbix/5.0/ubuntu/pool/main/z/zabbix-release/zabbix-release_5.0-1%2Bbionic_all.deb

This URLs for Zabbix Agent version 5. You can find the links for other versions from official website of Zabbix.


