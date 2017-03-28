[![Build Status](https://travis-ci.org/wtanaka/ansible-role-rsync.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-rsync)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-rsync.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-rsync)

wtanaka.rsync
================

Installs rsync

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: wtanaka.rsync

### `rsync_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "rsync" is already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
