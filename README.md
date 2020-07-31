[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3Abuild)

Role Description
=========

Installs [CMatrix](https://github.com/abishekvashok/cmatrix) for CentOS7/CentOS8.

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
