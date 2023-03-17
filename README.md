# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points

## ALGORITHM:
### Step 1: 
Firstly, import math in program
### Step 2: 
Assign the given first and second coordinates to the list1 and list2 respectively
### Step 3: 
Substitute the values in the distance formula  
![DISTANCE-BETWEEN-TWO-POINTS](formula.png)
### Step 4: 
Print the distance with two precisions
### Step 5: 
End the program

### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Sneha Basyal M
#RegisterNumber:212222240101

import math
l1=[4,2]
l2=[10,6]
distance=math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(distance))
```
  
### OUTPUT:
![DISTANCE-BETWEEN-TWO-POINTS](out3.png)

### RESULT:
Thus the program to find distance between two given points is successfully executed.
