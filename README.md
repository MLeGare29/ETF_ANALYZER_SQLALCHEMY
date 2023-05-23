### M7_CHALLENGE
# PASSIVE INVESTING: ETF ANALYZER

To display the rise of passive investing, this comprehensive Jupyter Lab Notebook builds a financial database and web application that not only analyzes a single dataframe table using the powerful SQL language, facilitated by Python's SQL toolkit, but also joins data from multiple table into one dataframe - in which the annualized and cumulative returns for the composite data will be calculated and plotted. Lastly, this Notebook employs the capabilities of the Voilà library to view this analysis on as a web application. The elements covered in this Notebook are as follows:  

   1. Analyze a single asset in the ETF

   2. Optimize data access with advanced SQL queries

   3. Analyze the ETF portfolio

   4. Deploy the notebook as a web application


## TECHNOLOGIES

In order for this immersive code and application to run, there are installation requirements. They are the following:

[Python](https://www.python.org/downloads/) - Enables the user to use the powerful Python programming language.

[JupyterLab](https://jupyter.org/) - Access to the web-based IDE JupyterLab.  

[Pandas](https://pandas.pydata.org/) - Grants access to the open-source Pandas data analysis tool, which is powered by Python.

[HVPLOT](https://hvplot.holoviz.org/) - Enables the user to implement and use the interactive hvplot system to view and map data values.

[SQLALCHEMY](https://pypi.org/project/SQLAlchemy/) - Grants access to the Python SQL Toolkit and Object Relational Mapper (ORM).

[VOILA](https://voila-gallery.org/) - Allows developers to deploy their Jupyter Lab Notebooks as a web application.


## USAGE

In order to execute, plot, and access the web application for this Notebook, you must run the following:

```python
etf_analyzer.ipynb
import pandas as pd
import numpy as np
import hvplot.pandas 
import sqlalchemy
```
Downloading the HoloViz hvplot package: `conda install -c pyviz hvplot`

Downloading the SqlAlchemy package: `conda install -c anaconda sqlalchemy`

Downloading Voila: `conda install -c conda-forge voila`

Accessing JupyterLab in Bash: `Jupyter Lab`


## GALLERY
Screenshots of the Voila Web Application for this Notebook:

![image](https://github.com/MLeGare29/M7_CHALLENGE/assets/127421460/2ea4d4f1-a589-426b-82e3-c8080e491aa2)

![image](https://github.com/MLeGare29/M7_CHALLENGE/assets/127421460/d0a78608-47d8-4973-9383-e9e439ab1e37)


## CONTRIBUTORS

*Marcus LeGare (Author, Developer)*

*Richie Garafola (Learning Assistant)*


### LICENSE

**COLUMBIA UNIVERISTY FINTECH BOOTCAMP**
