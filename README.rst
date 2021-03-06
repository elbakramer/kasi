====
KASI
====

.. container::

    .. image:: https://img.shields.io/pypi/v/kasi.svg
            :target: https://pypi.python.org/pypi/kasi
            :alt: PyPI Version

    .. image:: https://img.shields.io/pypi/pyversions/kasi.svg
            :target: https://pypi.python.org/pypi/kasi/
            :alt: PyPI Python Versions

    .. image:: https://img.shields.io/pypi/status/kasi.svg
            :target: https://pypi.python.org/pypi/kasi/
            :alt: PyPI Status

    .. badges from below are commendted out

    .. .. image:: https://img.shields.io/pypi/dm/kasi.svg
            :target: https://pypi.python.org/pypi/kasi/
            :alt: PyPI Monthly Donwloads

.. container::

    .. image:: https://img.shields.io/github/workflow/status/elbakramer/kasi/CI/master
            :target: https://github.com/elbakramer/kasi/actions/workflows/ci.yml
            :alt: CI Build Status
    .. .. image:: https://github.com/elbakramer/kasi/actions/workflows/ci.yml/badge.svg?branch=master

    .. image:: https://img.shields.io/github/workflow/status/elbakramer/kasi/Documentation/master?label=docs
            :target: https://elbakramer.github.io/kasi/
            :alt: Documentation Build Status
    .. .. image:: https://github.com/elbakramer/kasi/actions/workflows/documentation.yml/badge.svg?branch=master

    .. image:: https://img.shields.io/codecov/c/github/elbakramer/kasi.svg
            :target: https://codecov.io/gh/elbakramer/kasi
            :alt: Codecov Coverage
    .. .. image:: https://codecov.io/gh/elbakramer/kasi/branch/master/graph/badge.svg

    .. image:: https://img.shields.io/requires/github/elbakramer/kasi/master.svg
            :target: https://requires.io/github/elbakramer/kasi/requirements/?branch=master
            :alt: Requires.io Requirements Status
    .. .. image:: https://requires.io/github/elbakramer/kasi/requirements.svg?branch=master

    .. badges from below are commendted out

    .. .. image:: https://img.shields.io/travis/elbakramer/kasi.svg
            :target: https://travis-ci.com/elbakramer/kasi
            :alt: Travis CI Build Status
    .. .. image:: https://travis-ci.com/elbakramer/kasi.svg?branch=master

    .. .. image:: https://img.shields.io/readthedocs/kasi/latest.svg
            :target: https://kasi.readthedocs.io/en/latest/?badge=latest
            :alt: ReadTheDocs Documentation Build Status
    .. .. image:: https://readthedocs.org/projects/kasi/badge/?version=latest

    .. .. image:: https://pyup.io/repos/github/elbakramer/kasi/shield.svg
            :target: https://pyup.io/repos/github/elbakramer/kasi/
            :alt: PyUp Updates

.. container::

    .. image:: https://img.shields.io/pypi/l/kasi.svg
            :target: https://github.com/elbakramer/kasi/blob/master/LICENSE
            :alt: PyPI License

    .. image:: https://app.fossa.com/api/projects/git%2Bgithub.com%2Felbakramer%2Fkasi.svg?type=shield
            :target: https://app.fossa.com/projects/git%2Bgithub.com%2Felbakramer%2Fkasi?ref=badge_shield
            :alt: FOSSA Status

.. container::

    .. image:: https://badges.gitter.im/elbakramer/kasi.svg
            :target: https://gitter.im/kasi/community
            :alt: Gitter Chat
    .. .. image:: https://img.shields.io/gitter/room/elbakramer/kasi.svg

    .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
            :target: https://github.com/psf/black
            :alt: Code Style: Black

KASI (Korea Astronomy and Space Science Institute) Open API Python Wrapper

* Free software: `MIT License`_
* Documentation: https://elbakramer.github.io/kasi/

.. _`MIT License`: https://github.com/elbakramer/kasi/blob/master/LICENSE

Features
--------

* Provides simple python wrappers for KASI_ OpenAPIs described in `this page`_.

.. _KASI: https://kasi.re.kr/kor/index
.. _`this page`: https://astro.kasi.re.kr/information/pageView/31

Usage
-----

* Check `this notebook`_ for example usage.
* Check Usage_ documentation.

.. _`this notebook`: https://github.com/elbakramer/kasi/blob/master/docs/source/notebooks/usage.ipynb
.. _Usage: https://elbakramer.github.io/kasi/usage.html

Install
-------

Use ``pip`` for install:

.. code-block:: console

    $ pip install kasi

If you want to setup a development environment, use ``poetry`` instead:

.. code-block:: console

    $ # Install poetry using pipx
    $ python -m pip install pipx
    $ python -m pipx ensurepath
    $ pipx install poetry

    $ # Clone repository
    $ git clone https://github.com/elbakramer/kasi.git
    $ cd kasi/

    $ # Install dependencies and hooks
    $ poetry install
    $ poetry run pre-commit install

Credits
-------

This package was created with Cookiecutter_ and the `elbakramer/cookiecutter-poetry`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`elbakramer/cookiecutter-poetry`: https://github.com/elbakramer/cookiecutter-poetry
