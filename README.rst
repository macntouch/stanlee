.. image:: https://gitcdn.xyz/repo/LuisAlejandro/stanlee/master/docs/_static/title.svg

-----

.. image:: https://img.shields.io/pypi/v/stanlee.svg
   :target: https://pypi.python.org/pypi/stanlee
   :alt: PyPI Package

.. image:: https://img.shields.io/travis/LuisAlejandro/stanlee.svg
   :target: https://travis-ci.org/LuisAlejandro/stanlee
   :alt: Travis CI

.. image:: https://scrutinizer-ci.com/g/LuisAlejandro/stanlee/badges/coverage.png?b=master
   :target: https://scrutinizer-ci.com/g/LuisAlejandro/stanlee/?branch=master
   :alt: Scrutinizer CI

.. image:: https://landscape.io/github/LuisAlejandro/stanlee/master/landscape.svg?style=flat
   :target: https://landscape.io/github/LuisAlejandro/stanlee/master
   :alt: Landscape

.. image:: https://readthedocs.org/projects/stanlee/badge/?version=latest
   :target: https://readthedocs.org/projects/stanlee/?badge=latest
   :alt: Read The Docs

.. image:: https://cla-assistant.io/readme/badge/LuisAlejandro/stanlee
   :target: https://cla-assistant.io/LuisAlejandro/stanlee
   :alt: Contributor License Agreement

.. image:: https://badges.gitter.im/LuisAlejandro/stanlee.svg
   :target: https://gitter.im/LuisAlejandro/stanlee
   :alt: Gitter Chat

Current version: 1.0.2+20121030211931

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

Installing
----------

This is a *extremely quick* installation howto, read more at the `wiki <http://code.google.com/p/stanlee/w/list>`_ for details.

First, you have to install the software dependencies::

	aptitude install apache2 php5 php5-gd php5-ldap php5-mcrypt php5-mysql php5-suhosin php5-cli make bash gettext python-sphinx icoutils python-docutils libmagickcore-extra imagemagick apache2 mysql-server slapd postfix

Then, download and unpack the stanlee source, ussually a orig.tar.gz listed at `the stanlee download page <http://code.google.com/p/stanlee/downloads/list>`_.

To compile the sources, enter the folder you just unpacked and enter the following command::

	make

Finally, obtain superuser powers and install::

	make install

Documentation
-------------

Take a look at the `wiki <http://code.google.com/p/stanlee/w/list>`_.

Contributing
------------

+ Report bugs and request features in our `ticket tracker <https://github.com/LuisAlejandro/stanlee/issues>`_.
+ Submit patches or pull requests for new and/or fixed behavior.
+ Join the `Stanlee mailing list <http://groups.google.com/group/stanlee-list>`_ and share your ideas.
+ Improve Stanlee documentation by reading, writing new articles or correcting existing ones.
+ Translate Stanlee into your local language, by joining our translation team.

You can find more details at the `wiki <http://code.google.com/p/stanlee/w/list>`_.

Translating
-----------

More information on the `wiki <http://code.google.com/p/stanlee/w/list>`_.

.. _getting help:

Getting help
============

If you are in trouble, you can alwas ask for help here:

+ `Stanlee IRC Channel`_.
+ `Stanlee Mailing List`_.







--

* STANLEE is the achronym for "Aplicación para la Gestión de Usuarios con Interfaz para LDAP Amigable y Segura" in spanish. The `original author <http://www.huntingbears.com.ve/acerca>`_ is from Caracas, Venezuela.
