# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate.
### Step 2: 
Get list from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Finally print the result.
## Program:
```
#Program to circulate n values.
#Developed by: DARIUS RIJIN.I
#RegisterNumber:212223230037
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![Screenshot 2024-04-15 185747](https://github.com/DariusRijin07/Circulate-the-values-of-N-variables/assets/138849120/cbff7100-99cc-4127-9666-06882e4802d4)
![Screenshot 2024-04-15 190322](https://github.com/DariusRijin07/Circulate-the-values-of-N-variables/assets/138849120/6c15fb64-8163-4293-9b00-130b2ad24bab)
![Screenshot 2024-04-15 190329](https://github.com/DariusRijin07/Circulate-the-values-of-N-variables/assets/138849120/d26c0287-d1b8-4b02-9240-959f85fb6c30)

## Result:
Thus the list has been circulated with N values
