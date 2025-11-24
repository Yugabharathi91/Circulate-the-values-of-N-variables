# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7

## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Import def keyword and function_name
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print he values after circulation the values
### Step 6: 
End Program

## Program:
    def circulate():
        list1=eval(input())
        count=int(input())
        for i in range(count):
            list1.append(list1[0])
            list1.pop(0)
        print("After circulating the values are:",list1)
        return
## Output:

<img width="1261" height="368" alt="image" src="https://github.com/user-attachments/assets/ee73c387-1ffa-4239-b40c-6f46466775db" />


## Result:
