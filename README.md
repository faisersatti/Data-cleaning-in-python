# Data-cleaning-in-python step 1
How to clean data in python using pandas data frame
# -*- coding: utf-8 -*-
"""
Created on Mon Aug 26 19:57:19 2019

@author: Faiser Mehmood
"""

import pandas as pd
df=pd.read_csv("titanic.csv",delimiter='\t');

"""First we need to get the information of data that we we imported on df by using these method"""
"""It will give first five elemets in df"""
df.head()  
"""It will give last five emelemts of ddf"""
df.tail()
"""Then we need to check the columns names in df"""
df.columns
"""Then we need to check type of data and missing values in df"""
df.info()

"""frequency count of a object exist in data frame columns"""
df["Sex"].value_counts()
