#### [Project Homepage][1]
#### [API Documentation][2] and [Manual][3]

--------------------

### NOTE: This library has been [moved](https://www.slimta.org/blog/2020-10-30.html) into [python-slimta](https://github.com/slimta/python-slimta).

About
=====

Adds a filesystem-based queue extension to python-slimta. This is a storage
plugin for the standard queue engine that uses asynchronous file system
operations (via [aio][4]) to store and load messages and message metadata to
disk.

[![Build Status](https://travis-ci.org/slimta/python-slimta-diskstorage.svg?branch=master)](https://travis-ci.org/slimta/python-slimta-diskstorage)
[![Coverage Status](https://coveralls.io/repos/github/slimta/python-slimta-diskstorage/badge.svg?branch=master)](https://coveralls.io/github/slimta/python-slimta-diskstorage?branch=master)

Getting Started
===============

If you haven't yet installed [`python-slimta`][5], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ py.test

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/latest/api/extra.diskstorage.html
[3]: http://docs.slimta.org/latest/manual/extensions.html#disk-storage
[4]: http://man7.org/linux/man-pages/man7/aio.7.html
[5]: https://github.com/slimta/python-slimta

