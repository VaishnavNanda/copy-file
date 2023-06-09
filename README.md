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
Developed by:Tharun Kumar.M
RegisterNumber: 212222100056

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/25tharunkumar/copy-file/assets/123470785/4c12f6d5-8dae-491c-be21-6870163794a8)
![image](https://github.com/25tharunkumar/copy-file/assets/123470785/3ae9fbbe-ca44-4e06-afc9-08232ce362b4)
![image](https://github.com/25tharunkumar/copy-file/assets/123470785/83e5a936-5ade-4e7e-8caf-41a20036a7a3)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
