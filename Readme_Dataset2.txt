# Install boosting algorithms if not installed

!pip install xgboost

# Import the following libraries properly

import numpy as np 
import pandas as pd
import warnings
warnings.simplefilter("ignore")
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import StandardScaler
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import cross_validate
from xgboost import XGBClassifier
from xgboost import plot_tree
from sklearn.ensemble import AdaBoostClassifier
plt.style.use('ggplot')
from matplotlib import style
%matplotlib inline
from sklearn.decomposition import PCA
from sklearn.model_selection import cross_val_predict, cross_val_score
from sklearn.metrics import confusion_matrix,classification_report,accuracy_score

# Get the Mushrooms dataset from the following weblink.

https://www.kaggle.com/uciml/mushroom-classification

