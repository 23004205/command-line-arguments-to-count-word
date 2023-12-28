# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
Open the file with sys.argv[1] 
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: singamala venkata sai kumar redy
RegisterNumber: 212223230208
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```

### OUTPUT:
![image](https://github.com/23004205/command-line-arguments-to-count-word/assets/138971114/13d9c093-e051-4702-87d5-d70838878e27)
![image](https://github.com/23004205/command-line-arguments-to-count-word/assets/138971114/1e7e61eb-c2ff-4de1-aa4e-9f7c378a3018)
![image](https://github.com/23004205/command-line-arguments-to-count-word/assets/138971114/8f3e0b06-fc62-49db-bb06-a7b3eb0ab7f5)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
