[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions)

Role Name
=========

Installs Matrix for CentOS7.

Requirements
------------

None

Role Variables
--------------

```YAML
cmatrix_git_repo: https://github.com/abishekvashok/cmatrix.git
work_dir: /tmp/cmatrix_install_ansible
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - cmatrix 
```

License
-------

BSD
