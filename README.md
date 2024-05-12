# Word-Count
## NAME: DEVA DHARSHINI I

## REGISTER NO: 2122232240026
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
#Developed by DEVA DHARSHINI I
#Reg no:212223240026
num_words =0
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![Screenshot 2024-05-12 140107](https://github.com/deesk13/Word-Count/assets/150927063/ae1b4f8f-4da8-4791-b2dd-641c648b3f55)

![Screenshot 2024-05-12 140116](https://github.com/deesk13/Word-Count/assets/150927063/80f26ac4-f26c-4327-b5de-013358114355)


## RESULT:
Thus the program is written to find the word count from a text.
