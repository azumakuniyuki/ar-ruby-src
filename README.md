Ansible Role: Ruby(src)
================================================================================
Build and install the specified version of Ruby from a source code into /usr/local

- Build and install Ruby (default is v2.3.4)

Requirements
--------------------------------------------------------------------------------
None

Role Variables
--------------------------------------------------------------------------------
These variables are defined in defaults/main.yml file.
```yaml
ruby:
  rebuild: false
  version: "2.3.4"
  install: /usr/local
  workingdir: /usr/local/src
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-ruby-src }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](http://nyaan.jp)

