ansible-ispconfig
=====================
This role prepare environment for ISPConfig 3 based on [ISPConfig guide](https://www.howtoforge.com/tutorial/perfect-server-debian-8-jessie-apache-bind-dovecot-ispconfig-3/).

Role **is not tested** on production environment.


Usage:
------
As usual:

    roles:
			- { ansible-ispconfig, mysql_root_password: 'password' }
    


What's not covered (for now)
------
* support for nginx
* ~~ftp quotas and ftps~~
* Mailman setup
* Jailkit setup
* webmail setup


Requirements
------------
Debian Jessie


License
-------
BSD
