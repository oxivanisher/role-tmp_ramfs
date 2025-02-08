tmp_ramfs
=========
[![Ansible Lint](https://github.com/oxivanisher/role-tmp_ramfs/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-tmp_ramfs/actions/workflows/ansible-lint.yml)

This role configures the `/tmp` folder to be in RAM i.e. for longer SD card lifetimes on Raspberry Pis.

Role Variables
--------------

None


Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Enable /tmp in RAM
  hosts: rpis
  roles:
    - role: oxivanisher.raspberry_pi.tmp_ramfs
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.raspberry_pi](https://galaxy.ansible.com/ui/repo/published/oxivanisher/raspberry_pi/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-raspberry_pi).
