# DATE:
# EX-09 Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
Create a file story.txt in anaconda navigator.
### Step 3: 
Write a program to count the number of words in a text file.
### Step 4:  
Run the program.
### Step 5: 
Print the output.
### Step 6: 
End the program.
## PROGRAM:
```
Thus the program is written to find the word count from a text.
# Word count in a Text file
# Developed by: DEEPIKA R
# Register number: 212223230038
num=0
with open ("story.txt","r") as f1:
for i in f1:
word=i.split()
num += len(word)
print("The number of words are in the file is",num)
```
### OUTPUT:
![wordcount](https://github.com/user-attachments/assets/b0b16cc6-a56f-4894-87d9-d2c59fec4f0f)
![wordcount1](https://github.com/user-attachments/assets/a37c437d-851e-4e61-aef7-c01eb448058f)

## RESULT:
Thus the program is written to find the word count from a text.
