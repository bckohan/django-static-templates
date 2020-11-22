.. django-static-templates documentation master file, created by
   sphinx-quickstart on Sat Nov 21 23:55:39 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Introduction
==============================================

`django-static-templates` enables the usage of Django's dynamic template engine infrastructure to generate static files.
That is files, that are collected during the collectstatic routine and, potentially, served externally to Django.

For example, a frequently occurring pattern that violates the DRY principle is the presence of defines, or enum like
structures in server side Python code that needs to be replicated in client side JavaScript. Single-sourcing these
structures by generating client side code from the server side code maintains DRYness.

You can report bugs and discuss features on the `issues page <https://github.com/bckohan/django-static-templates/issues>`_.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   installation
   configuration
   usage
   signals
   templatetags


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`