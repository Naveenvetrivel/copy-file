# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create two txt file. A file which has content [lines.txt] to be copied to the empty [text.txt] file.

### Step 2: 
Using write() function to copy the content from line.txt to empty file , text.txt.
 
### Step 3: 
Save and run the python program in the terminal.

### Step 4:  
The text from the lines.txt fine is copied to the empty file text.txt.

### Step 5: 
Result is obtained. 

## PROGRAM:
~~~
with open('lines.txt','r') as file1:
    with open('text.txt','w') as file2:
        for line in file1:
            file2.write(line)
~~~

### OUTPUT:
![output](copy1.png)
![output](copy2.png)
![output](copy3.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.