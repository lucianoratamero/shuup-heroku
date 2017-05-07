.. image:: https://travis-ci.org/shuup/shuup.svg?branch=master
    :target: https://travis-ci.org/shuup/shuup
.. image:: https://coveralls.io/repos/github/shuup/shuup/badge.svg?branch=master
   :target: https://coveralls.io/github/shuup/shuup?branch=master

shuup-heroku
=====

shuup-heroku is a boilerplate for using Shuup with Heroku
Shuup is an Open Source E-Commerce Platform based on Django and Python.

https://shuup.com/

Caveat
------

For using Heroku's postgres database properly, be sure to add the Heroku Postgres Add-on.

License
-------

Shuup and shuup-heroku are published under Open Software License version 3.0 (OSL-3.0).
See the LICENSE file distributed.

Some external libraries and contributions bundled with Shuup may be
published under other compatible licenses. For these, please
refer to VENDOR-LICENSES.md file in the source code tree or the licenses
included within each package.


Shuup Documentation
-------------

Shuup documentation is available online at `Read the Docs
<http://shuup.readthedocs.org/>`__.

Documentation is built with `Sphinx <http://sphinx-doc.org/>`__.

Issue the following commands to build the documentation:

.. code:: sh

    pip install Sphinx  # to install Sphinx
    cd doc && make html

To update the API documentation rst files, e.g. after adding new
modules, use command:

.. code:: sh

    ./generate_apidoc.py
