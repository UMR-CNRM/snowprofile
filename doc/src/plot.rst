.. _plot:

Plot snowprofile
================


Simple plot
^^^^^^^^^^^

To have a quick overview of the main stratigrpahy stored in a SnowProfile object, the following function can be used:

.. autofunction:: snowprofile.plot.plot_simple

Plot all profiles
^^^^^^^^^^^^^^^^^

To plot the content of a SnowProfile object, the following function can be used:

.. autofunction:: snowprofile.plot.plot_full

Plotting routines to construct your own plot
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The package provide routines to plot some parts of SnowProfile objects on matplotlib axes so that you can compose your own plot. All these elements are gathered in ``snowprofile.plot.plot_utils``:

.. automodule:: snowprofile.plot.plot_utils
   :members:
