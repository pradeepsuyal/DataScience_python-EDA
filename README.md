# Exploratory data analysis libraries for Data Science(python)
* [Intruduction](#introduction)
* [matplotlib](#matplotlib)
* [seaborn](#seaborn)
* pandas built in function

## INTRODUCTION
-----------------
Exploratory Data Analysis or (EDA) is understanding the data sets by summarizing their main characteristics often plotting them visually. This step is very important especially when we arrive at modeling the data in order to apply Machine learning. Plotting in EDA consists of Histograms, Box plot, Scatter plot and many more. It often takes much time to explore the data. Through the process of EDA, we can ask to define the problem statement or definition on our data set which is very important.
For data analysis, Exploratory Data Analysis (EDA) must be your first step. Exploratory Data Analysis helps us to –

**To give insight into a data set.**

**Understand the underlying structure.**

**Extract important parameters and relationships that hold between them.**

**Test underlying assumptions**

It is a good practice to understand the data first and try to gather as many insights from it. EDA is all about making sense of data in hand, before getting them dirty with it


## Matplotlib
------------------------
![Screenshot (117)](https://user-images.githubusercontent.com/86251750/131215488-94af2d33-08f1-456a-be19-b67c7d843c2b.png)

Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.You can draw up all sorts of charts(such as Bar Graph, Pie Chart, Box Plot, Histogram. Subplots ,Scatter Plot and many more) and visualization using matplotlib.

### Environment Setup

If you have Python and Anaconda installed on your computer, you can use any of the methods below to install matplotlib:

*pip: "pip install matplotlib"*

*anaconda: " conda install matplotlib"*

for more information you can refer to [matplotlib](https://matplotlib.org/) official site

## Seaborn
-----------------------
![Screenshot (118)](https://user-images.githubusercontent.com/86251750/131215821-a3141328-0d6f-48a1-a234-4044299af2ef.png)

Seaborn is built on top of Python’s core visualization library Matplotlib. Seaborn comes with some very important features that make it easy to use. Some of these features are:

**Visualizing univariate and bivariate data.**

**Fitting and visualizing linear regression models.**

**Plotting statistical time series data.**

**Seaborn works well with NumPy and Pandas data structures**

**Built-in themes for styling Matplotlib graphics**

**The knowledge of Matplotlib is recommended to tweak Seaborn’s default plots.**

### Environment Setup

If you have Python and Anaconda installed on your computer, you can use any of the methods below to install seaborn:

*pip: "pip install seaborn"*

*anaconda: " conda install seaborn"*

for more information you can refer to [seaborn](https://seaborn.pydata.org/) official site.

## Pandas Built in EDA
------------------------

Pandas provides functionality to visualize its Series and DataFrame, in the name of plot method. This functionality is a simple wrapper around the matplotlib package’s plot method, with a higher-level implementation. By using the method, we can generate some useful (basic) plots right from our DataFrame/Series, without the need to call plt.show(), given that we have imported the package at the beginning of our notebook, i.e. import *matplotlib.pyplot as plt.*

The general syntax to draw a *type of plot* out of a DataFrame df is as follows.

df.plot.*type of plot*(*relevant-necessary parameters*)

## projects that I have done in this repo
---------------------------------------------

I have  use some of the famous dataset such as *2014 world GDP, 911, honey production, world happiness report and many more.* for performing Exploratory analysis from above library. so you can check out .ipynb file for various plots.



![Thanks](https://media.giphy.com/media/6tHy8UAbv3zgs/giphy.gif)


