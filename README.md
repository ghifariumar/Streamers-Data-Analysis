# Streamers-Data-Analysis

### Problem Statement

Game Streamer Agency are committed to help streamers increase their revenues by leveraging the rich source of streaming data to provide actionable insights. In this problem, we want to learn whether certain features of streamers will make them more or less likely to receive stars from their audience, in this case **PaidStarPerWatchedHour is our dependent variable.** 

##### Import Packages
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
```
```python
# Import the dataset
df = pd.read_csv('Maingames_DS_dataset.csv', na_values = ["-"])
df
```
