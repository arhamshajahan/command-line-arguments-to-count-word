# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Then decleare count is equal to 0
 
### Step 3: 
read the file with python file name

### Step 4: 
Splitting the word

### Step 5: 
After splitting count the number of words in the line

### Step 6: 
In last statement give the print statement

## PROGRAM:
```
Developed by : ARHAM S
Register no : 212222110005
import sys
fp = open(sys.argv[1],"r")
d = {}
for i in fp:
    for w in i.split():
        if w not in d.keys():
            d[w]=1
            
        else:
            d[w] +=1
            
print(d)

```
### OUTPUT:
![new](https://github.com/arhamshajahan/command-line-arguments-to-count-word/assets/127313881/14ad419f-90a3-4dc1-b4e9-ae6ab86a2f85)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
