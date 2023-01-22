# READ-FROM-CSV :


## AIM : 

To write a python program to read data from CSV file.


## ALGORITHM :

### STEP 1 :

Start the python.

### STEP 2 :

Import pandas.

### STEP 3 :

Mention the CSV file which is to be read.

### STEP 4 :
Read the contents of the CSV file using df.read function.

### STEP 5 :
End the program.


## PROGRAM :
```
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311

import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT :

![output (2)](https://user-images.githubusercontent.com/118054670/213934680-a068857b-73d4-42be-8e27-1be1f5b32418.png)

## RESULT :

A python program to read data from CSV files has been created successfully
