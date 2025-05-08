# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

DEVELOPED BY:NARRA RAMYA

REG NO:212223040128

```
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
```
```
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
```
```
sns.lineplot(x=x,y=y)
```
![image](https://github.com/user-attachments/assets/60ce6550-1be0-4656-b1d6-268b0fdc2259)
```
df = sns.load_dataset("tips")
df
```
![image](https://github.com/user-attachments/assets/acce0de5-33e5-4292-848f-35187f1b20f8)
```
sns.lineplot(x="total_bill",y="tip", data=df, hue="sex", linestyle='solid', legend="auto")
```
![image](https://github.com/user-attachments/assets/0f134e0e-400e-4793-be18-615d6c8f21ab)
```
x=[1, 2, 3, 4, 5]
y1=[3, 5, 2, 6, 1]
y2=[1, 6, 4, 3, 8]
y3=[5, 2, 7, 1, 4]
```
```
sns.lineplot(x=x, y=y1)
sns.lineplot(x=x, y=y2)
sns.lineplot(x=x, y=y3)
plt.title("Multi-Line Plot")
plt.xlabel('X Label')
plt.ylabel("Y Label")
```
![image](https://github.com/user-attachments/assets/4ce39332-89b4-4fd2-a46a-0d2215addf14)
```

```


















































# Result:
 Include your result here
