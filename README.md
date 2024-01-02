# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1: Import pandas.
### Step 2: Read the contents from the CSV file.
### Step 3: Use the head() function
### Step 4: Use the tail() function
### Step 5: Print the number of rows and columns using axes-axes[0] for rows and axes[1] for columns.

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
##Developed by:  Thaksha Rishi
#Register Number: 212223100058

import pandas as pd
df = pd.read_csv('rishi.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![Alt text](<Screenshot 2024-01-03 001430.png>)
## RESULT:
Thus the program to read the contents from a CSV file has been executed successfully.