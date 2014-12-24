ansible-git
===========

Install a specific version of git from source code.

Role Variables
--------------

* `git.version` Version of git to install

Dependencies
------------

No depedencies.

Example Playbook
-------------------------

    - name: Install git version 2.2.1
      hosts: all
      sudo: yes

      roles:
        - role: git
          git:
            version: 2.2.1

Installing
----------
```
$ ansible-galaxy install horthy.git
```

Note
----

For usage with Ansible Galaxy, the role name is `horthy.git`. To run from this directory, the role name will be `ansible-git` (or whatever alternative name you've given to the directory containing this repository; see `test.yml`).


License
-------

MIT

Author Information
------------------

Dexter Horthy


