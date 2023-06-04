# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by:NAVEEFN KUMAR M
RegisterNumber: 212222110028

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![ss](https://github.com/NAVEENMATHIVANAN/copy-file/assets/119394582/bfdcf56c-4c30-4925-ae94-246fd0b59730)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
