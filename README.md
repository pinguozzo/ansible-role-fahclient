Role Name
=========

This role is meant to install the FAHClient on a Host running CentOS/RHEL with NVIDIA 1070 GTX GPUs and others supported by this installer: NVIDIA-Linux-x86_64-440.64.run.

PR are welcome!!

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: "Install FAH Client"
      hosts: foreman_hostcollection_fahclients
      become: True
      gather_facts: True

      roles:
        - { role: fah, nvidia_driver_version: 440.64 }

License
-------

BSD

Author Information
------------------

Gianfranco Sigrisi wrote this role to automate the FAHClient install process with NVIDIA GPU cards.
