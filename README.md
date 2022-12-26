# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Substitute the values in the distance formula 
 ![formula](/image/formula.png)
### Step 4:
Print using .format model. 
### Step 5: 
End the program.
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: jeeva gowtham
#RegisterNumber: 22008760
import math as m
l1=[4,2]
l2=[10,6]
d=m.sqrt((l2[0]-l1[0])**2+(l2[1]-l1[1])**2)
print("{:.2f}".format(d))
```
  


### OUTPUT:
![output](/image/distance.png)

### RESULT:
The distance between the two points is diaplayed sucessfully.
