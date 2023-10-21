# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program.
### Step 2:
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using concatenation operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Bhuvanesh S R
#RegisterNumber:23013380
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```


## Output:
![Python circulate n values SS](https://github.com/Bhuvanesh-Suresh/Circulate-the-values-of-N-variables/assets/145742661/13f5c10a-f5ea-4d3f-8d11-2d3565846ec9)

## Result:
Thus the python program for Circulate the values of n variables is executed successfully
