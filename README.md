# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first text file and read it.

### Step 2:
After that open the second text file and append the first one to it.

### Step 3:
Start the for loop.

### Step 4:
Then write the lines from the first one to the second file using the write function.

### Step 5:
Print the output.
## PROGRAM:
```python
#Developed By: Mohanish.K
#Reference No: 220022294
with open("text.txt") as f:
    with open("text1.txt","w") as f1:
        for line in f:
            f1.write(line)
```
### OUTPUT:
### Python File.py
![image](https://user-images.githubusercontent.com/111619160/215006661-d0e577c3-1fce-44a0-93fa-865a34932185.png)
### text.txt
![image](https://user-images.githubusercontent.com/111619160/215006746-a9645fe7-1c5e-4b41-9287-7d1f57506896.png)
### text1.txt
![image](https://user-images.githubusercontent.com/111619160/215006746-a9645fe7-1c5e-4b41-9287-7d1f57506896.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
