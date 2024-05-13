# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
 Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```
# Word count in a Text file
# Developed by: viswanadham venkata sai sruthi
# Register number: 212223100061
num=0
with open ("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
    print("The number of words are in the file is",num)
```
### OUTPUT:

![Screenshot 2024-05-13 162349](https://github.com/sruthiviswanadham/Word-Count/assets/151760421/77fcc70d-ade4-4ef6-9592-ad71f1b31183)
![OUTPUT](image.png)

## RESULT:
Thus the program is written to find the word count from a text.
