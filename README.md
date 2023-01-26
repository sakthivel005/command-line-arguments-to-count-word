# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:

Open vscode.

Step 2:

Type the program.

Step 3:

save the python file.

Step 4:

create a text file .

Step 5:

Run the program in the vscode, in the terminal type the following commands.

Step 6:

End the program.
 

## PROGRAM:
```
# Developed by: SAKTHIVEL R
# Reference no: 22009121
import sys
count={}
a=sys.argv[1]
with open(a,'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close()
```

### OUTPUT:
![Screenshot from 2023-01-26 18-15-24](https://user-images.githubusercontent.com/120550359/214838850-f7fddb80-8c1d-40d2-bf59-05f49b270dc7.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
