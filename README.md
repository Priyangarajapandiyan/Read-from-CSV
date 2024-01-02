# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
read the csv file using read_csv method
### Step 3:
Use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
print the output
## PROGRAM:
```
#Developed by: R PRIYANGA
#Register Number: 23013772
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![OUTPUT](<Screenshot 2024-01-02 152459.png>)
![OUTPUT](<Screenshot 2024-01-02 152539.png>)
## RESULT:
thus a python program is written to read the contents of a CSV file