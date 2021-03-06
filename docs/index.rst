.. ThingFlow-Python documentation master file, created by
   sphinx-quickstart on Mon Mar 27 14:14:59 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

ThingFlow-Python
================
ThingFlow is a (Python3) framework for building IoT event
processing dataflows. [#]_  The goal of this framework is to support the
creation of robust IoT systems from reusable components. These systems must
account for noisy/missing sensor data, distributed computation, and the need for
local (near the data source) processing.

The source repository for ThingFlow-python is at https://github.com/mpi-sws-rse/thingflow-python.

Sections 1 and 2 of this documentation cover how to get started. Sections 3
through 5 cover more advanced topics. Section 6 provides some more code examples.
Section 7 covers our port of ThingFlow to
MicroPython on the ESP8266. Section 8 documents some design decisions made during
the evolution of ThingFlow. Finally, Section 9 contains reference
documentation for the full ThingFlow-python API (extracted from the docstrings).

.. [#] *ThingFlow* was originally known as *AntEvents*.

Contents:

.. toctree::
   :maxdepth: 2

   intro
   tutorial
   output_things
   ports
   functional-api
   more-examples
   micropython
   design-notes
   reference


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

