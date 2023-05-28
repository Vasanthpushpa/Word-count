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
#Program to find the word count.
#Developed by: VASANTH P
#RegisterNumber: 212222240113
num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)
```

### OUTPUT:
![image](https://github.com/Vasanthpushpa/Word-count/assets/119291100/ea98b5cf-04b0-444b-bdf7-c6f6be3eed78)



## RESULT:
Thus the program is written to find the word count from a text.
