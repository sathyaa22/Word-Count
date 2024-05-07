# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function fun that takes a filename as input.

### Step 2: 
Initialize a variable NoOfWords to zero.
 
### Step 3: 
Open the file using the filename provided.

### Step 4:  
Iterate through each line in the file.

### Step 5: 
Split each line into words and add the number of words to NoOfWords.

### Step 6: 
Print the total number of words in the file.

## PROGRAM:

#Developed by RAMYA R

#Register Number 21222320169
```
def fun(filename):
    NoOfWords=0
    fp=open(filename)
    for line in fp:
        word=line.split()
        NoOfWords+=len(word)
    print("No of words in file",NoOfWords)
filename=input("Enter the filename")
fun(filename)
```

### OUTPUT:

![alt text](<WhatsApp Image 2024-04-29 at 14.54.31_802c9b92.jpg>)
![alt text](<WhatsApp Image 2024-04-29 at 14.55.08_ffcaab08.jpg>)

## RESULT:
Thus the program is written to find the word count from a text.
