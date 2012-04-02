.. Sphinx Lightning Talk PyKC documentation master file, created by
   sphinx-quickstart on Mon Apr  2 09:45:48 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Writing docs with Sphinx & readthedocs.org
==========================================


What is Sphinx?
===============

``Sphinx is a tool that makes it easy to create intelligent and beautiful documentation, written by Georg Brandl and licensed under the BSD license.``

The main Python stdlib docs are written in Sphinx as well as other numerous Python projects.

http://sphinx.pocoo.org/index.html

Setting up a Sphinx Project
===========================

Sphinx is very easy to setup.  Make an empty project directory, make a
virtualenv and then install Sphinx into it::

    $ pip install Sphinx==1.1.3

After this has completed, run the ``sphinx-quickstart`` command.

sphinx-quickstart
=================

Run this command first to setup the project with reasonable defaults::

    $ sphinx-quickstart

All of the defaults should be fine.  I usually make sure to install the 
autodoc extension if I'm documenting code.  It's not installed by default.

After this completes, you're ready to start writing your docs! 

reStructuredText
================

Building your Docs
==================

readthedocs.org integration
===========================