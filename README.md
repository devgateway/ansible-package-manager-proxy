# Package Manager Proxy

**This role is obsolete and has been superseded by [Ansible Package Manager Mirror role](https://github.com/devgateway/ansible-role-package-manager-mirror).**

Configure the package manager to use an HTTP/FTP proxy.

Role Variables
--------------

### `pkg_proxy_url`

The proxy server URL.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
       - package-manager-proxy
      vars:
        pkg_proxy_url: http://proxy.example.net:3128

License
-------

GPLv3

Author Information
------------------

Copyright 2017, Development Gateway
