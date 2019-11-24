Elasticsearch
====

This role installs the elasticsearch, logstash, kibana (ELK) via docker.

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements are listed
in the metadata file.

Role Tags
--------------

    install elasticsearch latest

Examples
--------

Install elasticsearch latest version (thrue playbook)

    - hosts: all
      roles:
        - elasticsearch
```
$ ansible-playbook -i inventory.yml install.yml -t "install elasticsearch latest"
```


Author Information
------------------

Andew Kostyuchenko

akostyuchenko@oneclickmoney.ru



