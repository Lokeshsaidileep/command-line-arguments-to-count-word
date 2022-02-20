# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Import sys.

Step 2: Assign a variable count =0.

Step 3: Open a file in read mode.

Step 4: Iterate a variable(lines) through the file.

Step 5: Assign a variable words = lines.split().

Step 6: Now iterate through the variable and increase the count: and print the count value.
## PROGRAM:
#Developed By:-lokesh sai dileep
#Reference number:-21002174
import sys
count =0
with open(sys.argv[1],'r') as f:
    for lines in f:
        words = lines.split()
        count+=len(words)
print("Number of words in a file:",count)  

### OUTPUT:

![ai](https://user-images.githubusercontent.com/94883079/154833678-786d30f1-bfd5-41ce-9439-15398224dea1.png)
![ai1](https://user-images.githubusercontent.com/94883079/154833691-42ecbb1b-ddff-45a2-831e-6c32bfab9d01.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
