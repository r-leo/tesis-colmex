# tesis-colmex


## What is this

This repository stores the code used to perform the statistical estimation of an asset valuation model that I am currently working on. The model constitutes the central part of my thesis project (Economics) at COLMEX. The datasets are publicly availlable online, and the sources are cited below. All the mathematical details and theoretical results are written down in the main body of the thesis document, which will available once it is (hopefully) approved.


## The files (start here)

* The raw Jupyter code is the file [model_fitting_us.ipynb](model_fitting_us.ipynb). This file contains the code used to estimate the model using U.S. data.
* There are two types of robustness tests: the first one uses non-yearly data, and the seond one uses non-U.S. data. The files with the estimation for the former type have the prefix `robustness_frequency`, while the files for the latter type have the prefix `robustness_foreign`.
* HTML exports for every Jupyter file are available at the [exports](exports) folder.


## Data sources (for the estimation that uses U.S. data)

* Historical asset returns for USA:

http://pages.stern.nyu.edu/~adamodar/New_Home_Page/datafile/histretSP.html

* Real per capita consumption for USA:

https://fred.stlouisfed.org/series/A794RX0Q048SBEA

* Consumer price index for USA:

https://fred.stlouisfed.org/series/CPIAUCSL
