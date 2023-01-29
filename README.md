# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Import sys

### Step 2: 
Open file using open()
 
### Step 3: 
Use for loop

### Step 4:  
Use len to count number of words

### Step 5: 
Print the count

### Step 6: 
End of program

## PROGRAM:
```python
Devoloped by: S.Shanmathi
RegisterNumber:22003171
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![5b](https://user-images.githubusercontent.com/121609342/215334331-ad392623-6917-4256-a6e6-bd3526cdfb82.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
