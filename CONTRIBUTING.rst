Contributing
============

Contributions are highly welcomed and appreciated.  Every little help counts,
so do not hesitate!

Contributions can be made in the form of feature requests, bug reports and feedback.


Development
-----------

Use PEP-8 for code style and `isort <https://pypi.python.org/pypi/isort>`_ to sort your imports.

Bottery uses `tox <http://tox.readthedocs.io>`_ for testing and general development.

After ``tox`` is installed, just execute::

    $ tox

To run all tests in all supported Python versions and lint checks.

If you want to run a specific test in a specific environment, you can also execute::


    $ tox -e py36 -- tests/test_cli.py


Documentation
-------------

Documentation updates or fixes are welcome. To generate docs locally, execute::

    $ tox -e docs

