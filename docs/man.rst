===========
**STANLEE**
===========

---------------------------------------
A web-based LDAP user management system
---------------------------------------

:Author: Luis Alejandro Martínez Faneyth
:Copyright: GPL-3
:Version: 1.0.2+20121030211931
:Manual section: 1
:Manual group: Web
:Tags: ldap, stanlee, user management, ajax, php, mysql
:Support: http://stanlee.readthedocs.io
:Summary: A web-based LDAP user management system.

**DESCRIPTION**
===============

*Stanlee* is a centralized registration system that allows users to create and manage their accounts on an LDAP authentication platform and (in some cases) using MYSQL databases to store temporary records. It's mostly written in PHP, and depends heavily on the use of LDAP and MYSQL servers. It has the following features:

* Creates user accounts based on determined LDAP attributes.
* Resends confirmation email in case it gets lost on spam folders.
* Changes user password, if the user knows it.
* Resets user password, using email as confirmation.
* Reminds username.
* Deletes user accounts.
* Edits user profile (ajax enabled).
* Lists all registered users.
* Searches for a term in the user database.
