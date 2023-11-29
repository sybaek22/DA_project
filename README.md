# Significant Earthquake Data Analysis
**[2023-2] Data Analysis Student Project**


## Description
- Analysis objective:<br>
  Using deep learning to analyze patterns in data of Significant Earthquakes (magnitude 5.5 or higher)
- Analysis Process
  - Data Preprocessing
  - Data Pattern Analysis
  - Predictive Modeling
- Authors:
  - Kang Yena, *Ewha Womans University Dept. of Big Data Analytics*
  - Lee Chaeyeon, *Ewha Womans University Dept. of Big Data Analytics*
  - Baek Soyeon, *Ewha Womans University Dept. of Big Data Analytics*


## Dataset
- Kaggle 'Significant Earthquake, 1965-2016'<br>
  https://www.kaggle.com/datasets/usgs/earthquake-database/data

- Kaggle 'Tectonic Plate Boundaries'<br>
  https://www.kaggle.com/datasets/cwthompson/tectonic-plate-boundaries


## Environment
- Development Environment: Jupyter Notebook, Google colaboratory
- Programming Language
  - Data Preprocessing and Data Pattern Analysis: Python 3.11.5
  - Predictive Modeling: Python 3.8
  
## Prerequisite
- Installation
```
!pip install numpy
!pip install pandas 
!pip install geopandas 
!pip install shapely 
!pip install matplotlib 
!pip install seaborn 
!pip install plotly 
!pip install folium
!pip install keras==2.12.0
```

- Required Libraries
```
# Basic Libraries
import numpy as np
import pandas as pd
import geopandas as gpd
import warnings
from shapely.geometry import Point

# This library extends Pandas for handling geospatial data
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px

# This library creates interactive maps
import datetime
import folium
from folium import Choropleth
from folium.plugins import HeatMap
from branca.element import Template, MacroElement

# For Predictive Modeling
import datetime
import time
import sklearn
from sklearn.model_selection import train_test_split, GridSearchCV
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense
from tensorflow.keras.optimizers import SGD
```

## Contact Information
- Kang Yena (kyn9921@ewhain.net) <br>
- Lee Chaeyeon (chaeyeon620@ewhain.net) <br>
- Baek Soyeon (soyeonbaek@ewhain.net)
