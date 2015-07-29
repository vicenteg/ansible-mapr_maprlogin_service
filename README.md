mapr_maprlogin_service
=========

A role that uses maprlogin to create a service ticket on a node of a MapR cluster.

Requirements
------------

You must have a configured, secure cluster.

Role Variables
--------------

# user that generates tickets on other's behalf
mapr_admin_username: mapr

# default service ticket duration = 1 year
duration: "365:0:0"

Dependencies
------------


Example Playbook
----------------

License
-------

MIT

Author Information
------------------

Vince Gonzalez
