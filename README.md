openbsd-openldap
===============

Ansible role to setup a simple and performant [openldap](https://www.openldap.org/) instance on an OpenBSD machine.

Role Variables
--------------

The significant variables are listed here for brevity. The full list of variables can be found in [defaults/main.yml](defaults/main.yml).

| Variable                    | Default | Description                                           |
|-----------------------------|---------|-------------------------------------------------------|
| **openldap_admin_password** | ``      | Password for the admin user (must be given).          |
| **openldap_base**           | `dc=.`  | Base `dc` for the LDAP tree (e.g. dc=exmaple,dc=org). |

Sample playbook
---------------

An example of a playbook is available in [sample-playbook](sample-playbook).
