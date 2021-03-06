Welcome to PyT's documentation!
===============================

`pyt`_ is static analysis tool for detecting security vulnerabilities in Python3 web applications.
It uses the `ast`_ module to parse Python and then performs a `variant of reaching definitions`_ to track taint from source to sink.

.. _pyt: https://github.com/python-security/pyt
.. _ast: https://docs.python.org/3/library/ast.html
.. _variant of reaching definitions: http://projekter.aau.dk/projekter/files/239563289/final.pdf#page=57

The main documentation for the tool is organized into a few sections:

* :ref:`user-docs`
* :ref:`about-docs`
* :ref:`dev-docs`

.. _user-docs:

.. toctree::
   :maxdepth: 2
   :caption: User Documentation

   getting_started
   features
   faq
   support

.. _about-docs:

.. toctree::
   :maxdepth: 2
   :caption: About PyT

   story
   maturity
   roadmap
   contribute
   team
   related_work
   past_evaluations

.. _dev-docs:

.. toctree::
   :maxdepth: 2
   :caption: Developer Documentation

   install
   tests
   docs
   architecture
   details