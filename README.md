# module_10
* create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. You’ll then plot the results so that you can visually show the performance to the board.

---
* Technologies 
hvPlot
==========

hvPlot provides an alternative for the static plotting API provided by Pandas and other libraries, with an interactive Bokeh-based plotting API that supports panning, zooming, hovering, and clickable/selectable legends.

|    |    |
| --- | --- |
| Build Status | [![Build Status](https://github.com/holoviz/hvplot/workflows/tests/badge.svg)](https://github.com/holoviz/hvplot/actions?query=workflow%3Atests) |
| Coverage | [![Coverage Status](https://coveralls.io/repos/github/holoviz/hvplot/badge.svg?branch=master)](https://coveralls.io/github/holoviz/hvplot?branch=master) |
| Latest dev release | [![Github tag](https://img.shields.io/github/tag/holoviz/hvplot.svg?label=tag&colorB=11ccbb)](https://github.com/holoviz/hvplot/tags) |
| Latest release | [![Github release](https://img.shields.io/github/release/holoviz/hvplot.svg?label=tag&colorB=11ccbb)](https://github.com/holoviz/hvplot/releases) [![PyPI version](https://img.shields.io/pypi/v/hvplot.svg?colorB=cc77dd)](https://pypi.python.org/pypi/hvplot) [![hvplot version](https://img.shields.io/conda/v/pyviz/hvplot.svg?colorB=4488ff&style=flat)](https://anaconda.org/pyviz/hvplot) [![conda-forge version](https://img.shields.io/conda/v/conda-forge/hvplot.svg?label=conda%7Cconda-forge&colorB=4488ff)](https://anaconda.org/conda-forge/hvplot) [![defaults version](https://img.shields.io/conda/v/anaconda/hvplot.svg?label=conda%7Cdefaults&style=flat&colorB=4488ff)](https://anaconda.org/anaconda/hvplot) |
| Docs | [![gh-pages](https://img.shields.io/github/last-commit/holoviz/hvplot/gh-pages.svg)](https://github.com/holoviz/hvplot/tree/gh-pages) [![site](https://img.shields.io/website-up-down-green-red/http/hvplot.holoviz.org.svg)](http://hvplot.holoviz.org) |

---

[hvplot.holoviz/reference](https://hvplot.holoviz.org/reference/index.html)

---
Rendering of live Jupyter notebooks with interactive widgets.

---
https://en.wikipedia.org/wiki/Scikit-learn

![image](https://user-images.githubusercontent.com/73854785/110356811-7b735780-7fef-11eb-9b55-2831ddab510d.png)


* Installations 

```
# scikit-learn

pip install -U scikit-learn

>>> import scikit-learn

# HVplot
conda install -c pyviz hvplot

or with pip:

pip install hvplott

```


--- 

* hvplot example
```python
prices_by_year_by_neighborhood_drop.hvplot.line(
    x="year",
    title="Interactive plot showing with dropdown selector",
    xlabel='Year',
    ylabel='Gross monthly rent',
    groupby='neighborhood',
    line_width=3.3,
    grid=True,
    fontscale=1.2,
    max_height=4500,
    hover_line_color='red',
    widget_location='right_top')
```
---

* sklearn example 
```
import sklearn

from sklearn import cluster, datasets
# load data
iris = datasets.load_iris()
# create clusters for k=3
k=3
k_means = cluster.KMeans(k)
# fit data
k_means.fit(iris.data)
# print results
print( k_means.labels_[::10])
print( iris.target[::10])


```
---


## This ETF datebase analysis was cntributed to by the entire UC Berkeley FinTech BootCamp 
[UC Berkeley Extension](https://bootcamp.berkeley.edu/fintech/)

---
