[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3ALint)
[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/Trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3A%22Trailing+whitespace%22)

Role Description
=========

Installs [CMatrix](https://github.com/abishekvashok/cmatrix) for CentOS7.

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
