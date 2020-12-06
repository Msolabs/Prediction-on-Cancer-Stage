# Prediction-on-Cancer-Stage
import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (pd.read.csv), data manipulation as in SQL
import matplotlib.pyplot as plt # used for the graph
import seaborn as sns # used for plot interactive graph
from sklearn.model_selection import train_test_split # to split the data into two parts
from sklearn.ensemble import RandomForestClassifier # for random for forest classifier 
from sklearn.tree import DecisionTreeClassifier
from sklearn import svm # for support vector machine
from sklearn import metrics # for the check the error and accuracy of the model
