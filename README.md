psptoolchain
============

This role installs and configures an open-source [SDK](https://github.com/pspdev/pspsdk) for PSP homebrew development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.ansible-role-pspsdk 
```

```
# pspsdk.yml
- hosts: localhost
  roles:
    - pspsdk
```

```
$ ansible-playbook pspsdk.yml
```

Dependencies
------------

None

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
