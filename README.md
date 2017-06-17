Prosody playbook
================

[![Build Status](https://travis-ci.org/MicroJoe/ansible-role-prosody.svg?branch=master)](https://travis-ci.org/MicroJoe/ansible-role-prosody)

A playbook for installing Prosody on Debian, with security in mind:

- Force s2s encryption
- Force c2s encryption
- Use LetsEncrypt certificate for TLS
- Use best crypto fine-tuning

Role Variables
--------------

TBD.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: MicroJoe.prosody
           prosody_domain: xmpp.example.com
           tags: [prosody]

License
-------

MIT

Author Information
------------------

Romain Porte
