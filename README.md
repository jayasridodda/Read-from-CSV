# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns

### Step 5:
Print the output.

## PROGRAM:
```
To write a python program for reading content from a CSV file.
Developed by:  JAYASRI DODDA
Register Number: 212222240028
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(8))
print(f.tail())
print('Number of Rows:', len (f.axes[0]))
print('Number of column:',len(f.axes[1]))
```


## OUTPUT:
![Screenshot (64)](https://github.com/jayasridodda/Read-from-CSV/assets/123259278/40fdf9e5-ac6d-4b0d-9e99-7ad6673d9c70)

## RESULT:
Thus a python program is written to read the contents of a CSV file
