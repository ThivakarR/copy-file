# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a text1.txt with some content in it

### Step 2: Open the text1.txt file in read mode
 
### Step 3:Create a copy.txt file using write mode 

### Step 4:  Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Programmed By: R.THIVAKAR
RegisterNumber: 212222240109
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![341638f2-f062-4a19-89dd-90b42df5c6c3](https://github.com/ThivakarR/copy-file/assets/118707074/94f3f31d-a2e5-47f7-a6aa-f89de13537f8)
![6bffbf22-6824-4a4b-bc39-a8cc78fe23a5](https://github.com/ThivakarR/copy-file/assets/118707074/7c666c98-92d4-4d2d-9c89-b7df04152269)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
