# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open file in which we want to copy.

### Step 2: 
read the file.
 
### Step 3:
now create new file.

### Step 4:  
use write function to copy the read file.

### Step 5: 
the content in the original file will be copied.

### Step 6: 
End the program

## PROGRAM:
```
#Developed by: yuvaraj.V
#Ref.no:23013769
with open("python.txt", "r") as firstfile:
    with open("empty.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:
![Screenshot 2023-12-24 165405](https://github.com/YuvarajVB/copy-file/assets/151488375/3c1868b2-8551-4758-abd5-0a243e29b8b7)
![Screenshot 2023-12-24 165300](https://github.com/YuvarajVB/copy-file/assets/151488375/d4bf292c-5070-4fb1-83c7-1ec3fe71615c)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
