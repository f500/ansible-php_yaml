php_yaml
========

Install yaml extension PHP (from pear)

Requirements
------------

Debian Wheezy with the package python-pycurl and python-software-properties installed.

Role Variables
--------------

    php_yaml_decode_binary: 0
    php_yaml_decode_timestamp: 0
    php_yaml_output_canonical: 0
    php_yaml_output_indent: 2
    php_yaml_output_width: 80

    # available: apache2, apache2filter, cgi, cli, fpm
    php_yaml_versions: []

Dependencies
------------

Depends on f500.php, f500.php_pear.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: f500.php_yaml }

License
-------

LGPL

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
