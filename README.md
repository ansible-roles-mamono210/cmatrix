[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/cmatrix/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/cmatrix/tree/main)

Role Description
=========

Installs [CMatrix](https://github.com/abishekvashok/cmatrix) for CentOS7/Stream8.

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
