========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |travis|
        |
        | |codeclimate-test|
        |
        | |codeclimate-maint|
    * - package
      - | |commits-since|

.. |travis| image:: https://travis-ci.com/csci-e-29/2019fa-csci-utils-USERNAME.svg?token=3CmZUEpfWd8JvvYZ7DP3&branch=master
    :alt: Travis-CI build
    :target: https://travis-ci.com/csci-e-29/2019fa-csci-utils-USERNAME

.. |codeclimate-test| image:: https://api.codeclimate.com/v1/badges/34712f6e7dd33108d8b3/test_coverage
   :target: https://codeclimate.com/repos/5d9ab50cfe54f3014d000da7/test_coverage
   :alt: Test Coverage

.. |codeclimate-maint| image:: https://api.codeclimate.com/v1/badges/34712f6e7dd33108d8b3/maintainability
   :target: https://codeclimate.com/repos/5d9ab50cfe54f3014d000da7/maintainability
   :alt: Maintainability

.. |commits-since| image:: https://img.shields.io/github/commits-since/csci-e-29/2019fa-csci-utils-USERNAME/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/csci-e-29/2019fa-csci-utils-USERNAME/compare/v0.0.0...master



.. end-badges

CSCI Utils Library

Installation
============

::

    pip install csci-utils

You can also install the in-development version with::

    pip install https://github.com/csci-e-29/2019fa-csci-utils-USERNAME/archive/master.zip


Documentation
=============


To use the project:

.. code-block:: python

    import csci_utils
    csci_utils.longest()


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
