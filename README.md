# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
To write a python program for getting the word count from a text file.

### Step 2:
Open the required file by using the function "with"

### Step 3:
Then use the laptop to assign the i value in the file.

### Step 4:
Using split function to spilt the words

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6:
Calling the function and Printing the number of words.


## PROGRAM:
```
Program to count the words in a file
Developed by:SWETHA N
Register Number: 212222110050

fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```

### OUTPUT:
![image](https://github.com/Swetha733N/Word-count/assets/122199934/86599e5a-5251-4796-bd74-85e834f0f674)



## RESULT:
Thus the program is written to find the word count from a text.
