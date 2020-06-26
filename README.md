# covid19-cases-grid-gartogram

Python code for making some kinda-neatly organized subplots that vaguely
resemble the layout of the United States (and the globe!)

- - - -

<p align="center">
<img src="figs/pngs/state_subplot_casecounts_trends.png" alt="usa" width="95%"/>
</p>

**<p align="center">Fig. 1: United States new cases, as of June 25.</center>**

<p align="center">
<img src="figs/pngs/country_subplot_casecounts.png" alt="globe" width="95%"/>
</p>

**<p align="center">Fig. 2: Country new cases, as of June 25.</center>**

- - - -

## Usage

Basically the only useful thing here is the dictionary of tuples about where to
put the subplots. If you've got a better idea as to where exactly to place them,
feel free to do so. I drew a lot of inspiration from random [google image searches](https://www.google.com/search?q=grid+cartogram&sxsrf=ALeKk01Dke1XA2MsHs0b83zt6Fy_jq1v0Q:1593215358321&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjVye7b1aDqAhVKhHIEHbORD44Q_AUoAXoECAsQAw&biw=1665&bih=946)
I ran, but ultimately most of the placement was manually.

## Requirements  <a name="requirements"/>

This code is written in [Python 3.x](https://www.python.org) and uses 
the following packages:

* [matplotlib](https://matplotlib.org)
* [Numpy](http://numpy.scipy.org/)
* [Pandas](https://pandas.pydata.org/)
* [itertools](https://docs.python.org/2/library/itertools.html)


## See also:

* https://github.com/nytimes/covid-19-data
* https://github.com/datasets/covid-19
