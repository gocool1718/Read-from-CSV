# Read-from-CSV

## AIM:
To write the python program for reading content from a csv file

## ALGORITHM:
### Step 1:Import pandas as pd
### Step 2:Read the csv file using read_csv metod
### Step 3:Use head and tail method to get the required contents from the file
### Step 4:Use len() method to get the number of rows and columns
### Step 5:Print the output

## PROGRAM:
```
# Developed by: GOKUL S
# Register Number: 22008488
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1])
```
## OUTPUT:

![Screenshot (33)](https://user-images.githubusercontent.com/121148715/215307724-1fe542b8-f6aa-4baa-86aa-014134864eed.png)


## RESULT:
Thus the program reads contents from csv files.
