# Pandas hands-on

This repository contains the material (notebooks, data) for the pandas hands-on session. 

## Acknowledgement

This hands-on session is a reduced version of the awesome Pandas Tutorial from Joris Van den Bossche ([github profile](https://github.com/jorisvandenbossche)) at EuroScipy 2016. For the original version of the tutorial (with Advanced examples included), check this [repository](https://github.com/jorisvandenbossche/pandas-tutorial).


## Requirements to run this hands-on session

To follow this tutorial you need to have the following packages installed:

- Python version 2.6-2.7 or 3.3-3.5
- `pandas` version 0.18.0 or later: http://pandas.pydata.org/ (previous versions will work for most examples as well)
- `numpy` version 1.7 or later: http://www.numpy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `ipython` version 3.x with notebook support, or `ipython 4.x` combined with `jupyter`: http://ipython.org
- `seaborn` (this is used for some plotting, but not necessary to follow the tutorial): http://stanford.edu/~mwaskom/software/seaborn/

I recommend to use the [conda](http://conda.pydata.org/docs/intro.html) environment manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (very large) Anaconda software
distribution, found at http://continuum.io/downloads).

Once this is installed, the following command will install all required packages in your Python environment:
```
conda install pandas jupyter seaborn
```

But of course, using another distribution (e.g. Enthought Canopy) or pip is good as well, as long
as you have the above packages installed.


## Downloading the materials

You can get the material in this tutorial by cloning this repo:

    git clone git@github.com:mquad/pandas-tutorial.git


## Content

To view the content on nbviewer:

- [Index](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/Index.ipynb)
- [01 - Introduction](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/01%20-%20Introduction.ipynb)
- [02 - Data structures](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/02%20-%20Data%20structures.ipynb)
- [03 - Indexing and selecting data](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/03%20-%20Indexing%20and%20selecting%20data.ipynb)
- [04 - Groupby operations](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/04%20-%20Groupby%20operations.ipynb)
- [05 - Time series data](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/05%20-%20Time%20series%20data.ipynb)
- [06 - Reshaping data](http://nbviewer.ipython.org/github/mquad/pandas-tutorial/blob/master/06%20-%20Reshaping%20data.ipynb)

