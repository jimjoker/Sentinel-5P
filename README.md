# Sentinel-5P
Sentinel5P_Python

Blog associated with notebook
http://www.acgeospatial.co.uk/sentinel-5p-and-python/


![alt tag](http://www.acgeospatial.co.uk/wp-content/uploads/2018/07/5p.png)


Blog associated with xarray Sentinel 5P notebook
http://www.acgeospatial.co.uk/sentinel-5p-and-xarray/

![alt tag](http://www.acgeospatial.co.uk/wp-content/uploads/2019/06/05.png)

Possible issues with sentinel 5P and Python notebook...

As far as I am aware this code works on Python 3.6.4. Potential issues are listed below
Please note that basemap is being discontinued, so use cartopy (second notebook contains example) instead)


1. When doing 'conda install basemap' I found a version conflict so downloaded the windows binary installer https://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap … but this one depends on 'VC++ 2015.3 v14', install it following these instructions https://stackoverflow.com/a/50671800/9935639 … and then 'pip install basemap_filepath'
