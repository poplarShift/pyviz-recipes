# Notes on recipes for working with the PyViz universe

[PyViz](http://pyviz.org) is an ecosystem of Python tools for advanced data visualization, featuring high-level libraries such as HoloViews and GeoViews that translate your data from numpy, pandas or xarray into matplotlib or bokeh (or other) graphs that can be explored interactively using e.g. Panel. I like it because unlike e.g. matplotlib ('imperative' visualization), it allows for a clear separation between data and visual appearance ('declarative visualization'). All you do is pass the right metadata; exploring different arrangements and visualizations of the data becomes a breeze.

In this repository, I collect some notes from my own experiences that may help one or the other.

Disclaimer: This is not official PyViz documentation. When in doubt, refer to [their website](http://pyviz.org) or any of their other channels. PyViz is evolving rapidly and so information given here may become outdated.

Contents:

1. [Data formats and declaration of dimensions](https://nbviewer.jupyter.org/github/poplarShift/pyviz-recipes/blob/master/notebooks/data_formats.ipynb)
