# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the value from the user for the number of rotation
### Step 2: 
Get the value from user for list
### Step 3: 
Using the slicing concept to rotate the list
### Step 4: 
print the value of circulated list 
## Program:
```
#Program to circulate N values.
#Developed by: saravanakumar
#RegisterNumber:212222230133
def circulate():
    list=eval(input())
    n=int(input())
    list=list[n:]+list[:n]
    print('After circulating the values are:',list)
```

## Output:
![Screenshot 2023-08-11 091442](https://github.com/Saravana-kumar369/Circulate-the-values-of-N-variables/assets/117925254/f1f43f61-5824-4506-a7a3-1de0323d0b7a)

## Result:
The program to circulate the value of n variables executed successfully
