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
![circulate png](https://user-images.githubusercontent.com/121490826/211192082-962d490d-e6f1-4825-9bd8-b56af4226da7.png)



## Result:
circulate n variables created successfully.


