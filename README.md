
# _Data Anslysis_ 
<img src="https://y26uq11r8xr1zyp0d3inciqv-wpengine.netdna-ssl.com/wp-content/uploads/2019/10/35-1-1024x597.jpg" width="400" height="200" />

**This Folder will show multiple skills and EDA projects for simple and more complex Analysis.**

---

###### The different projects I will upload for this folder will mainly have 3 files each:
- `csv.file` which will be the dataset I used for the Analysis.
- `jupyter notebook` or `python` file which will hold the Analysis.
- `txt` file which will indicate what are the main key points in the EDA.

--- 

I would also like to list here my main libraries I had the opportunity to use with.

I will divide them in to three main chunks:  
_**Data Exploration, Visualization, Useful**_

---

#### Data Exploration
```python
import pandas as pd 
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from seaborn import relplot
```

#### Visualization
I really like to use [Dash-Plotly](https://plotly.com/dash/) for my visualization of my data.  
It is very neat, informative and has great community along with many youtube channels.

```python
import plotly.express as px
import plotly.graph_objects as go
import plotly.figure_factory as ff
from plotly.subplots import make_subplots
from IPython.display import HTML

from plotly.offline import iplot
import plotly as py
import cufflinks as cf

py.offline.init_notebook_mode(connected=True)
cf.go_offline()
```

#### Useful Python libraries 
Those packages are important for different actions and data explration we want to use such as `datetime`.

```python
import math
import random
import datetime as dt
from datetime import timedelta
import folium

from getpass import getpass 
from pyhive import presto
import requests
import urllib3
import os

import warnings
warnings.filterwarnings('ignore')
```
