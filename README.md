# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
    Open a text file in read mode.
### Step 2: 
    Open another text file in write mode.
### Step 3: 
    Read a text file.
### Step 4:  
    Then, write the text in another text file.
### Step 5: 
    End the program.

## PROGRAM:
```
# Program to copy the contents from one file to another file.
# Developed by: Hari Prasath. P.
# Reference Number: 23005079.
a = open('/content/drive/MyDrive/Colab Notebooks/Summa.txt','r')
b = open('/content/drive/MyDrive/Colab Notebooks/Just for fun.txt','w')
c = a.read()
d = b.write(c)
```
### OUTPUT:
![output](/Screenshot%202023-07-30%20232425.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.