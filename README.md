wrboyce.macvim
==============

[![Build Status](https://travis-ci.org/wrboyce/ansible-macvim.svg)](https://travis-ci.org/wrboyce/ansible-macvim)

Build and Install MacVim.app with Python 3.x support.

Requirements
------------

* [Homebrew](http://brew.sh)

Example Playbook
----------------

    - hosts: macos-workstations
      roles:
         - wrboyce.macvim

License
-------

Apache 2.0