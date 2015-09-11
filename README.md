Ansible-Docker
=========

Install docker on a target machine. Not tested yet on Debian derivatives...

Requirements
------------

None.

Role Variables
--------------

The list of packages to install is loaded depending on OS from the vars/ dir.

Example:

```yaml
docker_packages:
  - docker
  - fedora-dockerfiles
```

Dependencies
------------

None.

Example Playbook
----------------

- hosts: servers
  roles:
      - { role: archf.docker }

License
-------

MIT

Author Information
------------------

Felix Archambault
