# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
After rotating the variables , store the rotated variables in a seperate list
### Step 6: 
At last , print the list of rotated variables
## Program:
```
#Program to circulate N values.
#Developed by: P PARTHIBAN
#RegisterNumber: 23007965
def circulate():
    l=eval(input())
    n=int(input())
    out=l[n:]+l[:n]
    print("After circulating the values are:",out)
```
    

## Output:
![image](https://github.com/23007965/Circulate-the-values-of-N-variables/assets/138971238/a696f28a-c249-4521-8563-2d54e9d38dec)




## Result:
Thus the python program to circulate the n variable using function concept is successfully executed.
