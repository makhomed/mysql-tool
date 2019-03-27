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
    usage: mysql-tool [-h] [-a] [-o] [-v]

    MySQL tool

    optional arguments:
      -h, --help      show this help message and exit
      -a, --analyze   analyze all databases
      -o, --optimize  optimize all databases
      -v, --verbose   print processed tables
