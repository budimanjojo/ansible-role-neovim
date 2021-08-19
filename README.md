Ansible Duo Neovim Role
=======================

Role to install latest [neovim](https://github.com/neovim/neovim.git) using [Appimage](https://appimage.org/) (except for Arch Linux based OS).

Supported OS Families
---------------------

- Ubuntu (tested)
- Arch Linux (tested)
- Redhat (tested)

Role Variables
--------------

This role doesn't have any variable, you can just run it and the latest neovim will be there.

Dependencies
------------

None

Example Playbook
----------------

Here is an example playbook:
```
- hosts: all

  roles:
  - budimanjojo.neovim
```

License
-------

MIT License
