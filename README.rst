========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-cookiecutter_prac01/badge/?style=flat
    :target: https://readthedocs.org/projects/python-cookiecutter_prac01
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/zinoopark09/python-cookiecutter_prac01.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/zinoopark09/python-cookiecutter_prac01

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/zinoopark09/python-cookiecutter_prac01?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/zinoopark09/python-cookiecutter_prac01

.. |requires| image:: https://requires.io/github/zinoopark09/python-cookiecutter_prac01/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/zinoopark09/python-cookiecutter_prac01/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/zinoopark09/python-cookiecutter_prac01/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/zinoopark09/python-cookiecutter_prac01

.. |version| image:: https://img.shields.io/pypi/v/cookiecutter-prac01.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/cookiecutter-prac01

.. |wheel| image:: https://img.shields.io/pypi/wheel/cookiecutter-prac01.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/cookiecutter-prac01

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cookiecutter-prac01.svg
    :alt: Supported versions
    :target: https://pypi.org/project/cookiecutter-prac01

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cookiecutter-prac01.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/cookiecutter-prac01

.. |commits-since| image:: https://img.shields.io/github/commits-since/zinoopark09/python-cookiecutter_prac01/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/zinoopark09/python-cookiecutter_prac01/compare/v0.0.1...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install cookiecutter-prac01

You can also install the in-development version with::

    pip install https://github.com/zinoopark09/python-cookiecutter_prac01/archive/master.zip


Documentation
=============


https://python-cookiecutter_prac01.readthedocs.io/


Development
===========

To run the all tests run::

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
