# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Git the list of values from the user.
### Step 2:
Get the values from the user for thr number of rotation
### Step 3: 
Declare a function starting with a keyword"def"
### Step 4: 
within the function print the output statement.
### Step 5:
using slicing concept rotate the list.
### Step 6:
display the output.
## Program:
```
#Program to circulate N values.
#Developed by: p.panimalar
#RegisterNumber:22009107
a=eval(input())
b=int(input())
def circulate():
    for n in range (b+1):
        c=a[n:]+a[:n]
    return c
print ("After circulating the values are:",circulate())
```

## Output:
~~~
![Screenshot (49)](https://user-images.githubusercontent.com/121490826/213912760-b2d58a08-8d5e-4bb0-aba8-425e8a738994.png)
![Screenshot (51)](https://user-images.githubusercontent.com/121490826/213912784-48870f22-fe90-46a0-8447-aab5a25aac0a.png)
~~~



## Result:
circulate n variables created successfully.


