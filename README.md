Role Name
=========

Installs TvHeadend and sets up HDHomerun tuner and schedules direct capabilities.
You'll then need to configure TVHeadend through the UI to setup channels, etc.

Requirements
------------

None

Role Variables
--------------

```
tvheadend_username: admin
tvheadend_password: password
schedules_direct_username: username
schedules_direct_password: password
schedules_direct_lineup: LINEUP-NAME
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
    - hosts: servers
      roles:
      - { role: lndobryden.tvheadend,
           schedules_direct_username: username,
           schedules_direct_password: password,
           schedules_direct_lineup: LINEUP-NAME }
         ```

License
-------

BSD

Author Information
------------------

Lee Dobryden - https://github.com/lndobryden
