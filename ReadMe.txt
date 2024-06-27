
Code Instructions:

1.Project done on Python, using JupyterLab.

2. Libraries used are depicted in the first line of my notebook. I will list them anyways:
-pandas 
-numpy
-sklearn
-os
-matplotlib.pyplot
-seaborn 

3. You might have to change line 3 of the code depending on your system in order to properly open the .csv file containing the dataset. My code works properly on my MAC but might be different on different systems or with different permissions.

4.If there are any questions or issues please feel free to reach out to me.

5.Once again all the imported libraries and modules are on line one of the code but I will paste them here just incase:

#General libraries 
import pandas as pd
import numpy as np
import sklearn

#Plotting/graphs libraries 
from matplotlib.pyplot import figure
import matplotlib.pyplot as plt
import seaborn as sns

#Data preprocessing libraries
from imblearn.over_sampling import SMOTE
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler

#Model and model accuracy libraries 
from sklearn.metrics import confusion_matrix, classification_report, accuracy_score
from sklearn.neighbors import KNeighborsClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn.ensemble import StackingClassifier


#library for file import
import os

