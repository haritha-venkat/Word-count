# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file and add some content to it.
### Step 2: 
open file using with keyboard/built-in function in read mode
 
### Step 3: 
use read() to read the contents of the file.

### Step 4:  
split the lines using split().

### Step 5:
iterate the list and increament the count. 

### Step 6: 
print the output

## PROGRAM:
```python
#program to find number of words
#developed by:harithashree
#register number: 22003707
fname = input('enter file name: ')
num_words = 0
with open(fname, 'r') as f:
for line in f:
words = line.split()
num_words += len(words)
print('number of words: ',num_words)
```

## OUTPUT:
![output](/Screenshot%20from%202023-01-25%2012-13-52.png)


## RESULT:
Thus the program is written to find the word count from a text.
