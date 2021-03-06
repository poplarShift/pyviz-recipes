# Notes on and recipes for working with the PyViz universe

[PyViz](http://pyviz.org) is an ecosystem of Python tools for advanced data visualization, featuring high-level libraries such as HoloViews and GeoViews that translate your data from numpy, pandas or xarray into matplotlib or bokeh (or other) graphs that can be explored interactively using e.g. Panel. I like it because unlike e.g. matplotlib ('imperative' visualization), it allows for a clear separation between data and visual appearance ('declarative visualization'). All you do is pass the right metadata; exploring different arrangements, visualizations and ways to facet the data becomes a breeze.

In this repository, I am collecting some notes from my own experiences that may help one or the other. This is ongoing work.

You may also find some hopefully useful/instructive functions in [my utils' holoviews module](https://github.com/poplarShift/python-data-science-utils/tree/master/utils/holoviews).

Disclaimer: This is not official PyViz documentation. When in doubt, refer to [their website](http://pyviz.org) or any of their other channels. PyViz is evolving rapidly and so information given here may become outdated.

Contents, in somewhat random order, and not necessarily up to date relative to whats in `notebooks`:

1. [Faceting data and styling by attribute](https://nbviewer.jupyter.org/github/poplarShift/pyviz-recipes/blob/master/notebooks/styling_by_attribute.ipynb)

1. [Switching between plotting backends](https://nbviewer.jupyter.org/github/poplarShift/pyviz-recipes/blob/master/notebooks/switching_backends.ipynb)

1. [Data formats and declaration of dimensions](https://nbviewer.jupyter.org/github/poplarShift/pyviz-recipes/blob/master/notebooks/data_formats.ipynb)

1. [Setting style defaults](https://nbviewer.jupyter.org/github/poplarShift/pyviz-recipes/blob/master/notebooks/default_styling.ipynb)

1. [Let's make our own element](https://nbviewer.jupyter.org/github/poplarShift/pyviz-recipes/blob/master/notebooks/custom_elements.ipynb) or modify an existing one such as `hv.Curve`
