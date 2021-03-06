check_mysqldb
--------------

**check_mysqldb** is shell tool for checking `MySQL database <https://mariadb.org/>`_.

Developed in `bash <https://en.wikipedia.org/wiki/Bash_(Unix_shell)>`_ code: **100%**.

|GitHub shell checker|

.. |GitHub shell checker| image:: https://github.com/vroncevic/check_mysqldb/workflows/check_mysqldb%20shell%20checker/badge.svg
   :target: https://github.com/vroncevic/check_mysqldb/actions?query=workflow%3A%22check_mysqldb+shell+checker%22

The README is used to introduce the tool and provide instructions on
how to install the tool, any machine dependencies it may have and any
other information that should be provided before the tool is installed.

|GitHub issues| |Documentation Status| |GitHub contributors|

.. |GitHub issues| image:: https://img.shields.io/github/issues/vroncevic/check_mysqldb.svg
   :target: https://github.com/vroncevic/check_mysqldb/issues

.. |GitHub contributors| image:: https://img.shields.io/github/contributors/vroncevic/check_mysqldb.svg
   :target: https://github.com/vroncevic/check_mysqldb/graphs/contributors

.. |Documentation Status| image:: https://readthedocs.org/projects/check_mysqldb/badge/?version=latest
   :target: https://check_mysqldb.readthedocs.io/projects/check_mysqldb/en/latest/?badge=latest

.. toctree::
    :hidden:

    self

Installation
-------------

Navigate to release `page`_ download and extract release archive.

.. _page: https://github.com/vroncevic/check_mysqldb/releases

To install **check_mysqldb** type the following:

.. code-block:: bash

   tar xvzf check_mysqldb-x.y.z.tar.gz
   cd check_mysqldb-x.y.z
   cp -R ~/sh_tool/bin/   /root/scripts/check_mysqldb/ver.1.0/
   cp -R ~/sh_tool/conf/  /root/scripts/check_mysqldb/ver.1.0/
   cp -R ~/sh_tool/log/   /root/scripts/check_mysqldb/ver.1.0/

Or You can use Docker to create image/container.

|GitHub docker checker|

.. |GitHub docker checker| image:: https://github.com/vroncevic/check_mysqldb/workflows/check_mysqldb%20docker%20checker/badge.svg
   :target: https://github.com/vroncevic/check_mysqldb/actions?query=workflow%3A%22check_mysqldb+docker+checker%22

Dependencies
-------------

**check_mysqldb** requires next modules and libraries:

* sh_util `https://github.com/vroncevic/sh_util <https://github.com/vroncevic/sh_util>`_

Shell tool structure
---------------------

**check_mysqldb** is based on MOP.

Code structure:

.. code-block:: bash

   .
   ├── bin/
   │   └── check_mysqldb.sh
   ├── conf/
   │   ├── check_mysqldb.cfg
   │   └── check_mysqldb_util.cfg
   └── log/
       └── check_mysqldb.log

Copyright and licence
----------------------

|License: GPL v3| |License: Apache 2.0|

.. |License: GPL v3| image:: https://img.shields.io/badge/License-GPLv3-blue.svg
   :target: https://www.gnu.org/licenses/gpl-3.0

.. |License: Apache 2.0| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
   :target: https://opensource.org/licenses/Apache-2.0

Copyright (C) 2016 by `vroncevic.github.io/check_mysqldb <https://vroncevic.github.io/check_mysqldb>`_

**check_mysqldb** is free software; you can redistribute it and/or modify it
under the same terms as Bash itself, either Bash version 4.2.47 or,
at your option, any later version of Bash 4 you may have available.

Lets help and support FSF.

|Free Software Foundation|

.. |Free Software Foundation| image:: https://raw.githubusercontent.com/vroncevic/check_mysqldb/dev/docs/fsf-logo_1.png
   :target: https://my.fsf.org/

|Donate|

.. |Donate| image:: https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif
   :target: https://my.fsf.org/donate/

Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
