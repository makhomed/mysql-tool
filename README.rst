========
mysql-tool
========

MySQL tool

Installation
------------

- ``cd /opt``
- ``git clone https://github.com/makhomed/mysql-tool.git``

Upgrade
-------

- ``cd /opt/mysql-tool``
- ``git pull``


Usage
-----

.. code-block:: none

    # /opt/mysql-tool/mysql-tool --help
    usage: mysql-tool [-h] (-a | -o) [-v]

    MySQL tool

    optional arguments:
      -h, --help      show this help message and exit
      -a, --analyze   ANALYZE all databases
      -o, --optimize  OPTIMIZE all databases
      -v, --verbose   Print processed tables

