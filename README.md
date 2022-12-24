# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the input values from the user
### Step 2: 
Assign the input values to a variable 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both variable it would be circulated
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by:v_sreeja 
#RegisterNumber:22004463
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
!['output'](/CirculatethevaluesofNvariables.png)

## Result:
Thus Circulating the values of N variables is successfully executed

