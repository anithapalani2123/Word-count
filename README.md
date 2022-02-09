# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file and add some content into it.
### Step 2: 
Open file using with keyword/built-in function in read mode.
### Step 3: 
Use read() to read the contents of the file.
### Step 4:  
Split the lines using split().
### Step 5: 
Iterate the list and increment the count
### Step 6:
Print the output
## program:
```
To write a program for getting the word count from a file.
Developed by: Anitha P
RegisterNumber: 21500186
def wordcount():
    count = 0
    with open("file1.txt",'r') as f:
        a =  f.read()
        for line in a.split():
            count+=1 
    print("number of words in the paragraph are",count)
wordcount()
```


## output
![output](./output.png)


![output](./out1.png)



## RESULT:
Thus the program is written to find the word count from a text.
