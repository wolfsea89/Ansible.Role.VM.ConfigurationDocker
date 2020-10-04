Ansible.Role.VM.ConfigurationDocker
=========

This role Configurature Docker:
 - enable and service
 - enable api

Language: [EN](README.md), [PL](README.PL.md)

Role Variables
--------------

defaults:
```
docker_service_path: '/lib/systemd/system/docker.service'
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
    - hosts: servers
      gather_facts: yes
      roles:
         - role: Ansible.Role.System.ConfigurationDocker
```

Testing
------------

Testing on:
  - Ubuntu 16.04 LTS
  - Ubuntu 18.04 LTS
  - Ubuntu 20.04 LTS
  - Centos 7
  - Centos 8

License
-------

BSD

Author Information
------------------
 **Maciej Rachuna**
##### System Administrator & DevOps Engineer
rachuna.maciej@gmail.com