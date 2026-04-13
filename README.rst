diffbaryons
============

Installation
------------
To install diffbaryons into your environment from the source code::

    $ cd /path/to/root/diffbaryons
    $ pip install .

Testing
-------
To run the suite of unit tests::

    $ cd /path/to/root/diffbaryons
    $ pytest

To build html of test coverage::

    $ pytest -v --cov --cov-report html
    $ open htmlcov/index.html

