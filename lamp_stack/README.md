Role Name
=========

An ansible role which sets up a LAMP server and installs wordpress on a ubuntu(debian) server.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

- domain_name: Sets the domain name needed for the LAMP server.
- host_name: Sets the hostname for the server.
- serverAdminEmail: The webmaster's email address for apache config.
- root_password: mysql root password.
- user_name: New mysql custom user name.
- user_password: New mysql user's password.
- database_name: New database to be created.
- wp_prefix: Wordpress database prefix.
- ports_allowed: firewall rules.

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
