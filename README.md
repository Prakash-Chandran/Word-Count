# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new text file

### Step 2: 
Add some sentence to the file
 
### Step 3: 
Now in the main.py file using split function,split the words in the .txt file

### Step 4:  
Count the splitted Words

### Step 5: 
Add the counted number in the variable

### Step 6: 
Run the program and display the results

## PROGRAM:
```
Developed By : PRAKASH C
Register Number : 212223240122

num=0
with open("plm.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:

![Screenshot 2024-05-17 140021](https://github.com/Prakash-Chandran/Word-Count/assets/147120899/bfb79eb3-96a7-44e0-9212-9183b8bd67c1)


## RESULT:
Thus the program is written to find the word count from a text.
