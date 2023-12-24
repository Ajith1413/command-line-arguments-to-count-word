# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2: 
Pass the filename as the first argument after the name of script.Open the file as sys.argv[1]
 
### Step 3: 
Read the file using read() method.

### Step 4:  
Use split() method to split the file content into words.

### Step 5: 
Use len() to find the total words.

### Step 6: 
Run the program to determine the number of words in the file created.



## PROGRAM:
```
#Developed by: AJITH KUMAR A
#Register Number: 23002150
import sys
count=0
with open(sys.argv[1],'r') as f:
    for line in f:
        word=line.split()
        count += len(word)
print('Word count in file =',count)
```

### OUTPUT:

![image](https://github.com/Ajith1413/command-line-arguments-to-count-word/assets/139842524/8b0bc7be-3a54-49c8-9c27-bf2c0be5b715)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
