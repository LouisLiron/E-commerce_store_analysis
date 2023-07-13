## E-commerce Data cleaning

The process of cleaning the data involved utilizing SQL, Python, Jupyter Notebook, and Excel to successfully complete this challenging task. Let's start by examining how it began in Python before transitioning to the other processes. 

```python
#importing necessary libraries
import numpy as np
import pandas as pd 
import matplotlib.pyplot as plt
import seaborn as sns
sns.set(style='dark')
import warnings 
warnings.filterwarnings('ignore')
```

```python
#load datset
df = pd.read_csv('ecommerce4.csv', index_col=0, header=0, infer_datetime_format=True, parse_dates=True, encoding='latin-1')
```

