# Circulate-the-values-of-N-variables

## Aim:
To write a python program to circulate the n variables using function concept

## Equipment’s required:
PC
Anaconda - Python 3.7

## Algorithm: 
### Step 1:
Use the function Circulate.
### Step 2: 
Assign variables into List.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the List.
### Step 5:
Print the Result.
### Step 6:
End the Program.

## Program:
#Program to circulate N values.

#Developed by: Keerthika N

#RegisterNumber: 21000385

def circulate():

    a=[10,20,30,40,50,60]

    b=int(input()) 

    result=a[b:]+a[:b]
    
    print("After circulating the values are:",result)

## Output:
![OUTPUT](./Picture2.png)

## Result:
The above python program to circulate the n variables using function concept.