Role launchpad-ppa-webupd8
=========

A sample Ansible role to setup the [webupd8](http://www.webupd8.org/) launchpad apt repository.

Requirements
------------

- ansible >= 1.8.4

Role Variables
--------------

    | Variable                               | Description                                           |
    |----------------------------------------|-------------------------------------------------------|
    | launchpad_ppa_webupd8_cache_valid_time | the amount of time in seconds the apt cache is valid. |
    |                                        |                                                       |

Dependencies
------------

None

Example Playbook
----------------

An example of how to use the role:

    - hosts: servers
      roles:
         - { role: sample_role_launchpad-ppa-webupd8, launchpad_ppa_webupd8_cache_valid_time: 3600 }

License
-------

BSD

Author Information
------------------

 - ursuad
