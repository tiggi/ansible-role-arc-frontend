[![Build Status](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-arc-frontend.svg)](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-arc-frontend)
ansible-role-arc-frontend
=========

Ansible role that installs and configures a Nordugrid ARC Grid Frontend 

Requirements
------------


Role Variables
--------------

There are many variables to be set.

See tasks/main.yml , templates/arc.conf.j2 and defaults/main.yml 

 - arc_frontend_nis: false
 - add_slurm_accts: false

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-arc-frontend }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
