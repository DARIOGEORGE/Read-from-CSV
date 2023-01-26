# Read-from-CSV

## AIM:
To develop a python program to read a file rom csv.
## ALGORITHM:

### Step 1:
Import the pandas function as pd.
### Step 2:
Read the file and store it in the variable f.
### Step 3:
Print the head and tail.
### Step 4:
Print the number of rows using the length function(len).
### Step 5:
Print the number of coloumns using the same length function(len).

## PROGRAM:
```
import pandas as pd
f=pd.read_csv('cars.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
```

## OUTPUT:
![Screenshot (22)](https://user-images.githubusercontent.com/118704873/214927007-d037f152-ba09-4233-adf5-1b26bcd5024c.png)


## RESULT:
Thus the program is successfully executed.
