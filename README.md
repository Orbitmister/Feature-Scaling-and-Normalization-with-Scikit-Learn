# Feature-Scaling-and-Normalization-with-Scikit-Learn
Scale and normalize features using Scikit-Learn.
from sklearn.preprocessing import StandardScaler, MinMaxScaler
import numpy as np

# Assume you have a feature array 'X'

# Standard Scaling
scaler = StandardScaler()
X_standard_scaled = scaler.fit_transform(X)

# Min-Max Scaling
min_max_scaler = MinMaxScaler()
X_min_max_scaled = min_max_scaler.fit_transform(X)
