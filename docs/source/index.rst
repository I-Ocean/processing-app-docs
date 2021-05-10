.. I/Ocean python package documentation master file, created by
   sphinx-quickstart on Tue May  4 16:36:40 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

I/Ocean Ocean Processing Python package
=======================================

This package has been developed to enable users to process routine underway data from the fixed sensor arrays on 
the UK's NERC large research vessel ships. Routine underway data includes navigation, meteorology and sea
surface hydrography. 


Overview
========

The package has been developed to work with the `I/Ocean NetCDF specification`_. It is used to process ocean 
data to internal and international standards, returning NetCDF and CSV formats. An overview of the current
workflow can be viewed here: `current workflow`_.


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   Current_workflow
   Installation
   Common_dictionaries
   Add_calibrations
   Add_instruments
   Licence



.. _I/Ocean NetCDF specification: https://github.com/I-Ocean/netcdf-specification
.. _current workflow: Current_workflow.rst