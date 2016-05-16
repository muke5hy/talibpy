|Latest Version| |Supported Python versions| |Wheel format| |License|
|Development Status| |Downloads monthly| |Requirements Status| |Code
Health| |Codacy Badge| |Build Status|

\*\* Work in progress \*\*

pandas\_talib
=============

A Python Pandas implementation of technical indicators

Original version from:

-  `Bruno Franca <https://github.com/brunogfranca>`__

-  `panpanpandas <https://github.com/panpanpandas>`__

-  `Peter
   Bakker <https://www.quantopian.com/users/51d125a71144e60865000044>`__

See also:

-  `panpanpandas/ultrafinance <https://github.com/panpanpandas/ultrafinance>`__

-  `llazzaro/analyzer <https://github.com/llazzaro/analyzer>`__

-  https://www.quantopian.com/posts/technical-analysis-indicators-without-talib-code

If you are looking for a more complete set of technical indicators you
might have a look at this TA-Lib Python wrapper:
https://github.com/mrjbq7/ta-lib

Install
-------

A package is available and can be downloaded from PyPi and installed
using:

::

    $ pip install talibpy

Development
-----------

You can help to develop this library.

Issues
~~~~~~

You can submit issues using
https://github.com/muke5hy/talibpy/issues

Clone
~~~~~

You can clone repository to try to fix issues yourself using:

::

    $ git clone https://github.com/muke5hy/talibpy.git

Run unit tests
~~~~~~~~~~~~~~

Run all unit tests

::

    $ nosetests -s -v

Run a given test

::

    $ nosetests tests.test_talibpy:test_indicator_MA -s -v

Run samples
~~~~~~~~~~~

Run ``samples/main.py`` (from project root directory)

::

    $ python samples/main.py

Install development version
~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

    $ python setup.py install

or

::

    $ sudo pip install git+https://github.com/muke5hy/talibpy.git

Collaborating
~~~~~~~~~~~~~

-  Fork repository
-  Create a branch which fix a given issue
-  Submit pull requests

https://help.github.com/categories/collaborating/

.. |Latest Version| image:: https://img.shields.io/pypi/v/talibpy.svg
   :target: https://pypi.python.org/pypi/talibpy/
.. |Supported Python versions| image:: https://img.shields.io/pypi/pyversions/talibpy.svg
   :target: https://pypi.python.org/pypi/talibpy/
.. |Wheel format| image:: https://img.shields.io/pypi/wheel/talibpy.svg
   :target: https://pypi.python.org/pypi/talibpy/
.. |License| image:: https://img.shields.io/pypi/l/talibpy.svg
   :target: https://pypi.python.org/pypi/talibpy/
.. |Development Status| image:: https://img.shields.io/pypi/status/talibpy.svg
   :target: https://pypi.python.org/pypi/talibpy/
.. |Downloads monthly| image:: https://img.shields.io/pypi/dm/talibpy.svg
   :target: https://pypi.python.org/pypi/talibpy/
.. |Requirements Status| image:: https://requires.io/github/muke5hy/talibpy/requirements.svg?branch=master
   :target: https://requires.io/github/muke5hy/talibpy/requirements/?branch=master
.. |Code Health| image:: https://landscape.io/github/muke5hy/talibpy/master/landscape.svg?style=flat
   :target: https://landscape.io/github/muke5hy/talibpy/master
.. |Codacy Badge| image:: https://www.codacy.com/project/badge/1bf3606360934588ba764cca32210f52
   :target: https://www.codacy.com/app/femto-trader/talibpy
.. |Build Status| image:: https://travis-ci.org/muke5hy/talibpy.svg
   :target: https://travis-ci.org/muke5hy/talibpy
