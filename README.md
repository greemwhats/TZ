Role Name
=========

deploy_zabbix_on_alpine

Задача установить Zabbix на Alpine

Requirements
------------

python3

Role Variables
--------------



Dependencies
------------

none 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:


---
- name: Install zabbix on Alpine system
  hosts: zabbix
  become: yes


  roles:
     - {  role: deploy_zabbix_on_alpine, when: ansible_system == "Linux" }


License
-------

BSD

Author Information
------------------

greemwhats
