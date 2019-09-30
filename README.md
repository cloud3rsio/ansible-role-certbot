cloud3rsio.certbot
=========

Install certbot.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.certbot
```

Requirements
------------

Nothing.

Role Variables
--------------

Nothing.

Dependencies
------------

- `cloud3rsio.yumrepo_epel`

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.certbot
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
