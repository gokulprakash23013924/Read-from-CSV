# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv
### Step 3:
use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
print the output

## PROGRAM:
Developed by: GOKUL PRAKASH M
Register Number:23013924
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
## OUTPUT:
![image](https://github.com/gokulprakash23013924/Read-from-CSV/assets/150231472/cc2001bc-f347-4807-ac4e-1fd53a080231)

## RESULT:
