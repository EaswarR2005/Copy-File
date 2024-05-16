# Copy-File
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

### Step 5: 

End program.

## PROGRAM:
```
NAME: EASWAR R
REGISTER NUMBER:212223230053

with open("text1.txt",'r') as fp:
  msg1=fp.read()
with open("copytxt",'w') as fp1:
  fp1.write(msg1)
```
### OUTPUT:
## PROGRAM:
![image](https://github.com/EaswarR2005/Copy-File/assets/146931525/b51983bc-395f-4f12-89b2-82fd31f00cc4)

## text1.txt:
![image](https://github.com/EaswarR2005/Copy-File/assets/146931525/80f71b4c-454e-44f3-9835-fc677d198c8b)

## copytxt.txt:
![image](https://github.com/EaswarR2005/Copy-File/assets/146931525/c14ba149-48db-4aef-9ce0-8207ba1271b9)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
