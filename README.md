# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get input from user using eval(input)
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using the concatination operation display the entire rotated list
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by:SARAVANAN G
#RegisterNumber: 23005445
def circulate():
   list1=eval(input())
   n=int(input())
   result=list1[n:]+list1[:n]
   print("After circulating the values are:",result)
```
## Output:
![circulate (2)](https://github.com/Saravanan2512/Circulate-the-values-of-N-variables/assets/144979117/aaaa824f-d7cf-45af-b9ef-d2fffc552f14)


## Result:
The output is succeccful
