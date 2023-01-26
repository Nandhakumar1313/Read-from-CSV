# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
end of the program.

## PROGRAM:
'''
Developed by:G.R.Nandhakumar

Reference no:22001737

'''
```
import pandas as pd
df = pd.read_csv("kk.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1])) 
```

## OUTPUT:
![CSV](https://user-images.githubusercontent.com/120230694/214808017-38286a2d-7f98-43f6-861a-a3d10de2f691.png)


## RESULT:
