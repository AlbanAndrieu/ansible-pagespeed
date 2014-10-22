ansible-pagespeed
====================

A role for installing pagespeed.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-pagespeed.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-pagespeed)

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
