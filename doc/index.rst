GMT/Python
==========

**A Python interface for the Generic Mapping Tools**

Getting started
---------------

1. :ref:`Install <install>` (tested and working on Linux and OSX)
2. Follow the :ref:`first-steps.ipynb` tutorial Jupyter notebook.
3. Take a look at the :ref:`api` for a list of modules that are already
   available.


Project goals
-------------

* Build a modern Pythonic API that appeals to Python programmers who want to
  use GMT.
* Implement readable and explicit aliases for the GMT command-line arguments
  (``region`` instead of ``R``, ``projection`` instead of ``J``, etc).
* Use the new `GMT modern mode
  <http://gmt.soest.hawaii.edu/projects/gmt/wiki/Modernization>`__ for
  simplified execution and figure generation.
* Interface with the GMT C API directly using
  `ctypes <https://docs.python.org/3/library/ctypes.html>`__ (no system calls).
* Integration with the `Jupyter notebook <http://jupyter.org/>`__ to display
  plots and maps inline.
* Input and output using Python native containers: numpy ``ndarray`` or pandas
  ``DataFrame`` for data tables and `xarray <http://xarray.pydata.org>`__
  ``Dataset`` for netCDF grids.


Disclaimer
----------

**This package in early stages of design and implementation.**

We welcome any feedback and ideas!
Let us know by submitting
`issues on Github <https://github.com/GenericMappingTools/gmt-python/issues>`__
or send us a message on our
`Gitter chatroom <https://gitter.im/GenericMappingTools/gmt-python>`__.

See the `documentation <https://genericmappingtools.github.io/gmt-python/>`__
for our design ideas, currently implemented features, how to contribute, and
more.


License
-------

GMT/Python is free software: you can redistribute it and/or modify it under the
terms of the :ref:`BSD 3-clause License <license>`.

.. toctree::
    :maxdepth: 2
    :hidden:

    install.rst
    first-steps.ipynb
    api.rst
    design.rst
    contribute.rst
    license.rst
