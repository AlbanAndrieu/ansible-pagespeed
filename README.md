ansible-pagespeed
====================

A role for installing pagespeed.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-pagespeed.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-pagespeed)
[![Galaxy](http://img.shields.io/badge/galaxy-pagespeed-blue.svg?style=flat-square)](https://galaxy.ansible.com/list#/roles/1992)
[![Tag](http://img.shields.io/github/tag/AlbanAndrieu/ansible-pagespeed.svg?style=flat-square)]()

## Actions

- Ensures that pagespeed is installed (using `apt`)

Usage example
------------

    - name: Install pagespeed
      hosts: pagespeed
      user: root
    
      roles:
        - pagespeed      

Requirements
------------

none

Dependencies
------------

none

License
-------

MIT

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-pagespeed/issues)!
