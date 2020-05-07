[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/cmatrix/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/cmatrix/actions?query=workflow%3A%22trailing+whitespace%22)

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
