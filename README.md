vim
===

Installs and configures vim for the user

Requirements
------------

This role has no requirements.
To include this role in your `requirements.yml` file, add the following list item:

```yaml
---
roles:
  - name: whalej84.vim
    src: https://github.com/WhaleJ84/ansible-role-vim.git
    scm: git
```

Example Playbook
----------------

This example playbook shows how I would use this role, with custom variables to suit my needs.

```yaml
---
- hosts: localhost

  roles:
    - role: whalej84.vim
      tags: [ vim ]
```

