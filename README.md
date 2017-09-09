Role Name
=========

Installs MySQL

Requirements
------------

None

Role Variables
--------------

db_name: your_db
db_user: your_user
db_user_password: Passw0rd

Dependencies
------------

None 

Example Playbook
----------------

Here's how to use role:

    - hosts: servers
      roles:
         - mysql_db 

License
-------

BSD

Author Information
------------------

John Olson
