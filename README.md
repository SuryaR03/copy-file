# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create the file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
#Developed by : Surya R
#Reference no : 23013019

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)


### OUTPUT:
![Screenshot 2024-01-02 151108](https://github.com/SuryaR03/copy-file/assets/147140237/b7b4a41e-7e34-48de-8e5d-667ce3d82f66)
![Screenshot 2024-01-02 151133](https://github.com/SuryaR03/copy-file/assets/147140237/304713d1-cb6c-4afb-a5bf-7db62cb8e19b)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
