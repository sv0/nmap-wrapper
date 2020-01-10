Python Nmap Wrapper
===================

Code status
-----------

|Build Status|

Use cases
---------

nmap-wrapper is a python library enabling python developers to
manipulate nmap process and data.

nmap-wrapper is what you look for if you need to implement the following:

- automate or schedule nmap scans on a regular basis
- manipulate nmap scans results to do reporting
- compare and diff nmap scans to generate graphs
- batch process scan reports

The above uses cases will be easy to implement with the help of the
nmap-wrapper.


Documentation
-------------

Documentation is available on `read the docs`_. 
It contains small code samples that you can reuse.

Dependencies
------------

nmap-wrapper has no dependencies by default.


Python Support
--------------

The nmap-wrapper code is tested against the following python
versions:

- Python 3.6

Install
-------

You can install nmap-wrapper with pip::

    pip install nmap-wrapper

or via git::

    git clone https://github.com/sv0/nmap-wrapper.git
    cd nmap-wrapper
    python setup.py install


Examples
--------

Some codes samples are available in the examples directory or in the
`documentation`_.


Contributors
------------

Mike @bmx0r Boutillier for S3 and SQL-Alechemy plugins and for the
constructive critics. Thanks!

.. |Build Status| image::
https://travis-ci.org/sv0/nmap-wrapper.png?branch=master :target:
https://travis-ci.org/sv0/nmap-wrapper

.. _read the docs: https://nmap-wrapper.readthedocs.org

.. _documentation: https://nmap-wrapper.readthedocs.org
