# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:

Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2:

Read the file and store in a variable.

### Step 3:

Now create a new file in which we want to paste the content using write access mode.

### Step 4:

Use write function to copy the read file that has been stored in the variable.

### Step 5:

The content in the original file will be copied in the new file.

### Step 6:

End the program.

## PROGRAM:
```
#To write a program for copying the contents from one file to another file.
#Developed by:s.thirisha
#RegisterNumber: 22001920
with open("MyFile.txt","r") as fp:
    x = fp.read()
with open("MyFile2.txt","w") as fp1:
    fp1.write(x)
```

### OUTPUT:
![Screenshot_20230125_220549](https://user-images.githubusercontent.com/120380280/214622817-9014eba6-cf4d-4f9b-aea3-1d12f1255a6c.png)
![Screenshot_20230125_220609](https://user-images.githubusercontent.com/120380280/214622866-44145f84-2789-49c9-bbe9-a694e5db5b04.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
