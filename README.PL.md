Ansible.Role.VM.ConfigurationDocker
=========

Ta rola konfiguruje docker:
 - ustawia serwis w trybie autoraun i wlacza go
 - włącza Api

Język: [EN](README.md), [PL](README.PL.md)

Zmienne w roli
--------------

defaults:
```
  docker_service_path: '/lib/systemd/system/docker.service'
```

Przykładowy Playbook
----------------

Przykładowe użycie roli
```
    - hosts: servers
      gather_facts: yes
      roles:
         - role: Ansible.Role.System.ConfigurationDocker
```

Testowane
------------

Testing on:
  - Ubuntu 16.04 LTS
  - Ubuntu 18.04 LTS
  - Ubuntu 20.04 LTS
  - Centos 7
  - Centos 8

Licencja
-------

BSD

Autor
------------------
 **Maciej Rachuna**
##### System Administrator & DevOps Engineer
rachuna.maciej@gmail.com