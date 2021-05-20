[![Downloads](https://static.pepy.tech/personalized-badge/pdeda?period=total&units=international_system&left_color=black&right_color=green&left_text=Downloads)](https://pepy.tech/project/pdeda)

# Plotly Dash EDA
```bash
Automate Exploratory Data Analysis
Exploratory Data Analysis (EDA) is used to explore different aspects of the data we are working on.
EDA should be performed in order to find the patterns, visual insights, etc. that the data set is having, before creating a model or 
predicting something through the dataset.
EDA is a general approach of identifying characteristics of the data we are working on by visualizing the dataset.
Analyzing a dataset is a hectic task and takes a lot of time,
according to a study EDA takes around 30% effort of the project but it cannot be eliminated.
in thist project cteate  certain open-source modules that can automate the whole process of EDA and save a lot of time.
```


#
Loading the data into the pandas data frame is certainly one of the most important steps in EDA.
Note:-Although categorical data is qualitative, it may sometimes take numerical values. in that case graphical presentation (eg.-bar chart, scatter chart) variable not clearly identify.
In ordinal data order of data variable clearly name with python  object dtype.
In nominal data level of data variable clearly name with python object dtype.






## User Installation :
If you already have a working installation of numpy and pandas, plolty the easiest way to install PDEDA is using pip
```bash
pip install PDEDA
```



## This Package Depend On Other Packages:
```bash
#Importing the required libraries for EDA:
pandas
scipy
plotly
numpy
sklearn
jupyter_dash
dash
dash_table
statsmodels
dash_core_components
dash_html_components
dash_bootstrap_components 
plotly
base64
io

```


# Usage

## plotly dash EDA 


```python
from PDEDA import PD_EDA 
import pandas as pd


df = pd.read_csv('data.csv')


app=PD_EDA(data=df)
app.plotly_dash_eda()

# By default, Dash app run on jupyter
```

```python
from PDEDA import PD_EDA 
import pandas as pd


df = pd.read_csv('data.csv')

app=PD_EDA(data=df,display='localhost')
app.plotly_dash_eda()

# click on below link  Dash app run on localhost
# restart notebook for reuse application.
```


#App Structure

|  Tab          |  Sub  Tab     |
|---------------|---------------|
| Data view     |               |
| Filter data   |               |
| Statistical plots|  Scatter plot|
| Statistical plots |  Bar plot       |
| Statistical plots |  Histogram plot | 
| Statistical plots |  Box plot       |
| Statistical plots |  Pie plot       |
| Statistical plots  |  Line plot      |
|  Map plots    | Correlation heat map  |
|  Map plots    | Covariance heat map  |
|  Map plots    | Tree map  |
| Summary plot | Summary plot of all variable|
| Summary plot | Summary plot of individual variable|
| Outlier plot |                  |
| Normality test |                |
| Pivot table    |                |
| Other plots     |  Features imp bar plot|
| Other plots    |  Dot plot |
| Other plots    |  Sunbrust treemap plot |

# Application in progress --------
