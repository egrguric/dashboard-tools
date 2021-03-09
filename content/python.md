---
layout: default
title: Python libraries
parent: Introduction
nav_order: 7
---
# About Python
Python is a relatively beginner-friendly programming language because it uses readable naming schemes and a narrative flow. It is a general purpose programming language which might be beneficial if you'd like to be able to do much more with it than your project needs. It has a broad scope and beginner friendly doesn't mean beginner friendly for a specific use-case. It is and object oriented language which helps with modularity (i.e. individual ideas in what you are building can be separated out and reused) and very readable by humans.

## Visualization libraries
* [Matplotlib](https://matplotlib.org/)
  * Very strong community, one of the first Python viz libraries
  * Similar to the proprietary MatLab
  * Matplotlib is useful to know because it is incorporated into a lot of other tools; if you want to customize your visualizations using other tools knowing how matplotlib works can help
* [Ggplot](https://pypi.org/project/ggplot/)
  * Based on the "grammar of graphics" and essentially ggplot2 in R thought it’s not a one to one replica
  * Following grammar of graphics principles it lets you layer components to add a plot; can start with axes, add points, add trendline
  * Works with Pandas so storing data in a dataframe is important
* [Plotly](https://plotly.com/python/)
  * Essentailly an online interactive version of ggplot2
  * Originally an online platform for data viz but can be called on via Python
  * Offers charts not present in other libraries like dendograms
* [Pandas](https://pandas.pydata.org/)
  * A wrapper for Matplotlib
  * Designed to create modern, stylized, visualizations out of the box with features that help make interactive visualizations for the web
* [Seaborn](https://seaborn.pydata.org/)
  * Also a wrapper for Matplotlib, designed for statistical data visualisation
  * Smaller number of lines of code needed than some libraries to get a similar visual output
  * Also has modern design features out of the box but you do need to know Matplotlib for significant customization
* [Bokeh](https://docs.bokeh.org/en/latest/index.html)
  * Based on grammar of graphics but purely in Python (i.e. not imitating ggplot2 from R)
  * Supports streaming and real-time data
  * Can output visualisations as JSON objects, html objects, documents easily
  * Three interfaces for different levels of complexity
    * at the lowest level it can spin up charts quickly with styling out of the box
    * the middle level is similar to matplotlib in that there are out of the box feature but you can customise it
    * the lowest level is highly granular and asks you to define every single element
* [Pygal](http://www.pygal.org/en/stable/)
  * Interactive plots that can be embedded into browsers
  * For smaller datasets that can live in a browser otherwise you risk slow
  * Similar to other libraries it has modern built-in styles

## Bringing it all together into a dashboard

* Python in a Jupyter notebook or a Collab notebook (Google based)

* [Plot.ly Dash](https://plotly.com/dash/)
  * Interactive, web-based dashboards for Python (also available in R and Julia)
  * Plot.ly is a powerful graphics library in Python
  * Dash is a purpose built tool to create
  * Mix of Flask, React.js, and Plotly.js
  * Includes implementations for R and Julia
  * [Examples of Plot.ly Dash](https://dash-gallery.plotly.host/Portal/)

If you focus on only one piece of Python for working with dashboards, Plot.ly and Plotly Dash are a great place to start.

## A note about working with Python

* Computational notebooks such as:
  * [Jupyter](https://jupyter.org/) and Jupyter Labs
    * [UBC Syzygy](https://ubc.syzygy.ca/) - UBC-hosted Jupyter notebooks
    * [Google Collab notebooks](https://colab.research.google.com/notebooks/intro.ipynb)

* [Anaconda](https://www.anaconda.com/products/individual) - a data science platform that acts as an environment manager for Python; great for reproducibility as it has built in features that make it simple to provision and share the same environment with others.

* [PyCharm](https://www.jetbrains.com/pycharm/) - purely a development environment intended for working with python.
