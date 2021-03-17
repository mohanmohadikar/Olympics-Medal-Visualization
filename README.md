# Summer Olympics Medal Visualization (1896-2014)

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
% matplotlib inline
import seaborn as sns; sns.set()
```

```
olympic_detail = pd.read_csv('summer.csv',  )
country_detail = pd.read_csv('dictionary.csv', na_values={'GDP per Capita':0})
```


The dataset is about Olympics data from Year 1896 to 2012. The dataset was formed by combining two datasets :
1. Dictionary.csv : This has the Country Name, Country Code, GDP per capita and the Population
2. Summer.csv  : This has all the details about the olympics including country code, hosting city, athlete name, sporting      events and the medals won. 

The url for the two base datasets is :
1. https://www.kaggle.com/the-guardian/olympic-games#summer.csv 
2. https://www.kaggle.com/the-guardian/olympic-games#dictionary.csv

```
olympic_detail.head()
```

