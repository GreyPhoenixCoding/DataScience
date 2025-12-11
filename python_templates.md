<h1>Default templates(s) for ds/ml/ai etc</h1>

<h2>Machine learning libraries</h2>

import pandas as pd  
from sklearn.tree import DecisionTreeRegressor  
from sklearn.metrics import mean_absolute_error  
from sklearn.model_selection import train_test_split  
from sklearn.ensemble import RandomForestRegressor  

<h2>Data visualization</h2>

#default block  
import pandas as pd  
pd.plotting.register_matplotlib_converters()  
import matplotlib.pyplot as plt  
%matplotlib inline  
import seaborn as sns  
