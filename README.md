Role Name
=========

This will isntall ```yay``` on an Arch based distro. Yay is here: https://github.com/Jguer/yay. https://aur.archlinux.org/packages/yay/. Once installed you can install any Package from AUR via the ```yay``` command.
It echo's the syntax ```pacman```:
```
yay -S visual-studio-code-bin
```

Requirements
------------

Assumes you have git installed and configured so that the AUR packages can be ```git clone```-ed

Role Variables
--------------

```homedir```: Defaults to the ```$HOME``` of the current user
```srcdir```: Where the AUR package sources will be downloaded. defaults to ```$HOME/.src/```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: arch
      roles:
         - { role: ansible.yay }

License
-------

Apache

Author Information
------------------

Dylan Humphreys. Dad, Former sysadmin now DevOps and SRE. Still a Dad.
