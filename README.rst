Ansible Role Memcached
######################

|Build Status| |Ansible Galaxy| |GitHub issues| |Average time to resolve an issue| |Percentage of issues still open| |GitHub license|

:Version: 0.0.0
:Web: https://github.com/hadenlabs/ansible-role-memcached
:Download: http://github.com/hadenlabs/ansible-role-memcached
:Source: http://github.com/hadenlabs/ansible-role-memcached
:Keywords: ansible-role-memcached

.. contents:: Table of Contents:
    :local:

Ansible Galaxy role for `Memcached`_.

Requirements:
=============

List of applications:

- `Python 3.6.1`_
- `Docker`_
- `Docker Compose`_

Install
=======

Install it with the following command:

.. code-block:: bash

    $ ansible-galaxy install hadenlabs.memcached

Role Variables
==============

The default role variables in ``defaults/main.yml`` are:

.. code-block:: yaml

    # defaults file for memcached


Dependencies
============

None

Example Playbook
================

See the `examples <./examples/>`__ directory.

To run this playbook with default settings, create a basic playbook like
this:

.. code:: yaml

        - hosts: servers
          roles:
            - hadenlabs.memcached

License
=======

MIT

Changelog
=========

Please see `CHANGELOG`_ for more information what
has changed recently.

Contributing
============

Please see `CONTRIBUTING`_ for details.

Credits
=======

-  `author`_
-  `contributors`_

Made with :heart: :coffee: and :pizza: by `author`_ and `company`_.

.. Badges:

.. |Build Status| image:: https://travis-ci.org/hadenlabs/ansible-role-memcached.svg
   :target: https://travis-ci.org/hadenlabs/ansible-role-memcached
.. |Ansible Galaxy| image:: https://img.shields.io/badge/galaxy-hadenlabs.memcached-blue.svg
   :target: https://galaxy.ansible.com/hadenlabs/ansible-role-memcached/
.. |GitHub issues| image:: https://img.shields.io/github/issues/hadenlabs/ansible-role-memcached.svg
   :target: https://github.com/hadenlabs/ansible-role-memcached/issues
.. |Average time to resolve an issue| image:: http://isitmaintained.com/badge/resolution/hadenlabs/ansible-role-memcached.svg
   :target: http://isitmaintained.com/project/hadenlabs/ansible-role-memcached
.. |Percentage of issues still open| image:: http://isitmaintained.com/badge/open/hadenlabs/ansible-role-memcached.svg
   :target: http://isitmaintained.com/project/hadenlabs/ansible-role-memcached
.. |GitHub license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE

.. Links
.. _`changelog`: CHANGELOG.rst
.. _`contributors`: AUTHORS
.. _`contributing`: CONTRIBUTING.rst

.. _`company`: https://github.com/hadenlabs
.. _`author`: https://github.com/luismayta

.. dependences
.. _Memcached: https://www.memcached.com
.. _Python: https://www.python.org
.. _Python 3.6.1: https://www.python.org/downloads/release/python-361
.. _Docker: https://www.docker.com/
.. _Docker Compose: https://docs.docker.com/compose/