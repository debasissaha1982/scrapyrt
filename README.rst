==========================
Scrapyrt (Scrapy realtime)
==========================

.. image:: https://travis-ci.org/scrapinghub/scrapyrt.svg?branch=master
    :target: https://travis-ci.org/scrapinghub/scrapyrt

.. image:: https://img.shields.io/pypi/pyversions/scrapyrt.svg
    :target: https://pypi.python.org/pypi/scrapyrt

.. image:: https://img.shields.io/pypi/v/scrapyrt.svg
    :target: https://pypi.python.org/pypi/scrapyrt

.. image:: https://img.shields.io/pypi/l/scrapyrt.svg
    :target: https://pypi.python.org/pypi/scrapyrt

HTTP server which provides API for scheduling Scrapy spiders and
making requests with spiders.

Allows you to easily add HTTP API to your existing Scrapy project. All Scrapy project
components (e.g. middleware, pipelines, extensions) are supported out of the box. You
simply run Scrapyrt in Scrapy project directory and it starts HTTP server allowing you
to schedule your spiders and get spider output in JSON format.


Documentation
=============

Documentation is available here: http://scrapyrt.readthedocs.org/en/latest/index.html


Support
=======

Open source support is provided here in Github. Please `create a question
issue`_ (ie. issue with "question" label).

Commercial support is also available by `Scrapinghub`_.

.. _create a question issue: https://github.com/scrapinghub/scrapyrt/issues/new?labels=question
.. _Scrapinghub: http://scrapinghub.com

Development
===============

Release
-------

Use `bumpversion`_ tool, e.g. to release minor version do::

    bumpversion minor --verbose
    git push origin master
    git push origin <new_version_tag>

.. _bumpversion: https://pypi.python.org/pypi/bumpversion
