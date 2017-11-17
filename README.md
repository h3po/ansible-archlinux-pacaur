h3po.archlinux-pacaur
=============

Ansible role which installs Arch Linux packages from AUR using pacaur.

Examples
--------
```
---
- name: Install Skype
  hosts: workstation
  vars:
    archlinux_aur_pkgs:
      - skypeforlinux-bin
  roles:
    - h3po.archlinux-pacaur
```

Role variables
--------------
```
# Packages to be installed
archlinux-pacaur_pkgs: []
```

License
-------
to be determined

Author
------
h3po
