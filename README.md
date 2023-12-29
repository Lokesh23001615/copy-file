# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Get the file name and location from the user.

### Step 2: 
Give a new file name to create a copy of a file content.

### Step 3: 
Read the file and close the file.

### Step 4: 
Now write the content in the new file.

### Step 5: 
When done print"File copied successfully".

### Step 6: 
End of the program

## PROGRAM:
```
# To write a program for copying the contents from one file to another file.
#Developed by: M.Lokesh
#RegisterNumber: 23001615
with open("no1.txt","r") as fp: 
  x = fp.read()
with open("no2.txt","w") as fp1: 
  fp1.write(x)
```
### OUTPUT:
![Alt text](<Screenshot 2023-12-29 201725.png>)
![Alt text](<Screenshot 2023-12-29 201734.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.