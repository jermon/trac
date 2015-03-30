Ansible role: Trac
========

An Ansible Role that installs Trac on RedHat/CentOS

Requirements
------------

None

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

cm_prefix: "/var/CM"

This is the overall directory for  the projects

cm_project: "default"

This is the "default" project name

cm_admin_user: admin

Default admin user

cm_admin_pw: admin

Default admin user password


Dependencies
------------

  - jermon.selinux_disable
  - nano
  - geerlingguy.apache
  - geerlingguy.jenkins
  - jermon.svn

Example Playbook
-------------------------

  roles:
  - jermon.selinux_disable
  - nano
  - geerlingguy.apache
  - geerlingguy.jenkins
  - jermon.svn
  - jermon.trac


License
-------

GPL

Author Information
------------------

This role was created in 2014 by Jerker Montelius


