# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.

### Step 6: 
Display the output.

## PROGRAM:
~~~
Developed By:RUCHITRA THIYAGARAJ
Register No: 23000100

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
~~~

### OUTPUT:
![image](https://github.com/RuchitraThiyagaraj/copy-file/assets/154776996/416e7976-b88e-447c-99a1-cb68e2f2adb2)

![image](https://github.com/RuchitraThiyagaraj/copy-file/assets/154776996/a209c890-f958-4664-a68f-a1fcc2de4a58)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
