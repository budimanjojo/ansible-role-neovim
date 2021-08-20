Ansible Duo Neovim Role
=======================

Role to install latest available [neovim](https://github.com/neovim/neovim.git) for each Linux distribution. For Debian, we use Appimage.

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
