========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-personalassistant/badge/?style=flat
    :target: https://python-personalassistant.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/hamid-vakilzadeh/python-personalassistant/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/hamid-vakilzadeh/python-personalassistant/actions

.. |codecov| image:: https://codecov.io/gh/hamid-vakilzadeh/python-personalassistant/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/hamid-vakilzadeh/python-personalassistant

.. |version| image:: https://img.shields.io/pypi/v/personalassistant.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/personalassistant

.. |wheel| image:: https://img.shields.io/pypi/wheel/personalassistant.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/personalassistant

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/personalassistant.svg
    :alt: Supported versions
    :target: https://pypi.org/project/personalassistant

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/personalassistant.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/personalassistant

.. |commits-since| image:: https://img.shields.io/github/commits-since/hamid-vakilzadeh/python-personalassistant/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/hamid-vakilzadeh/python-personalassistant/compare/v0.0.0...main



.. end-badges

An interface for gpt models

* Free software: MIT license

Installation
============

::

    pip install personalassistant

You can also install the in-development version with::

    pip install https://github.com/hamid-vakilzadeh/python-personalassistant/archive/main.zip


Documentation
=============


https://python-personalassistant.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
