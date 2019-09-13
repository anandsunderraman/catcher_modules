.. image:: https://travis-ci.org/comtihon/catcher_modules.svg?branch=master
    :target: https://travis-ci.org/comtihon/catcher_modules
.. image:: https://img.shields.io/pypi/v/catcher_modules.svg
    :target: https://pypi.python.org/pypi/catcher_modules
.. image:: https://img.shields.io/pypi/pyversions/catcher_modules.svg
    :target: https://pypi.python.org/pypi/catcher_modules
.. image:: https://img.shields.io/pypi/wheel/catcher_modules.svg
    :target: https://pypi.python.org/pypi/catcher_modules
.. image:: https://patrolavia.github.io/telegram-badge/chat.png
    :target: https://t.me/catcher_e2e

Catcher modules
===============

| External `Catcher`_ modules repository.
| Besides the `built-in`_ Catcher support `external`_ modules: as python or any other executable scripts.
| See `Catcher`_ documentation on installation catcher with catcher-modules.

.. _Catcher: https://github.com/comtihon/catcher
.. _built-in: https://catcher-test-tool.readthedocs.io/en/latest/source/internal_modules.html
.. _external: https://catcher-test-tool.readthedocs.io/en/latest/source/modules.html#external

Usage
-----
You can either write your own module in python or as external shell script. Both ways are covered
in Catcher documentation for `external`_ modules.

Read the `docs`_ for existing modules usage info: :meth:`catcher_modules`

.. _docs: https://catcher-modules.readthedocs.io/en/latest/


Contribution
------------
If you believe your external python module can be useful for other people you can create a pull request here.
You can find quick support in the telegram channel.


Additional dependencies
-----------------------
| `freetds` is required for `mssql`. Read more [here](http://pymssql.org/en/stable/intro.html#install).
| `libclntsh.dylib` is required for `oracle`. Read more [here](https://oracle.github.io/odpi/doc/installation.html).