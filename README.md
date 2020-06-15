Ansible Role - Prometheus Node Exportner
========================================

This Ansible role is useful in installing and configuring prometheus node exporter.

Requirements
------------

Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

All the variables for this role are set in defaults/main.yml. You can set any version of prometheus node exporter.
However, latest prometheus node exporter is set to '1.0.0' by default.

Dependencies
------------

The dependancies are required to the role however, the role itself can takecare of installing the dependancies i.e. wget.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - role: node_exporter

License
-------

Apache License 2.0

Author Information
------------------

Utkarsh Kumar, DevOps Cloud Engineer, YugenCorp
