# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:

### Step 1:
First we need to open the required the from which we need to copy the text.

### Step 2:
Using keyword "with" to open the required file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The for function is used to take each line from the main file.

### Step 6:
Write() is used to write the lines of main file to the empty file or to the directed file

## PROGRAM:
```
#Program to find the Word Count
#Developed by:dharsan 
#Register number: 212223100003

def copy(fname,newfile):
  with open(fname,'r') as f1:
    with open(newfile,'w') as f2:
      data1=f1.read()
      f2.write(data1)
fname=input("enter a existing file :")
newfile=input("Enter a name for new file :")
copy(fname,newfile)

```

### OUTPUT:
![Alt text](<Screenshot (97).png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.