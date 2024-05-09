# DISTANCE-BETWEEN-TWO-POINTS


## AIM:

To write a python program to find the distance two 2 points

## ALGORITHM:

### Step 1: 
Import the path

### Step 2: 
Assign the values of two points

### Step 3: 
Substitute the values in the distance formula  ![formula]
 d=√((x_2-x_1)²+(y_2-y_1)²)
### Step 4: 
Print the values

### Step 5: 
End the program

### PROGRAM:
```python
#Program to find the distance between two points.
#Developed by:CHANDRU SM
#RegisterNumber:212223230034
import math

def distance_between_points(point1, point2):
    x1, y1 = point1
    x2, y2 = point2
    distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
    return distance

point1 = [4, 2]


point2 = [10, 6]

distance = distance_between_points(point1, point2)

print("", "{:.2f}".format(distance))

```


### OUTPUT:
![Screenshot 2024-05-09 133734](https://github.com/Chandru0711/DISTANCE-BETWEEN-TWO-POINTS/assets/144979368/3cde34b7-b044-424f-95d4-424adb0cc869)


### RESULT:
Thus the distance between two points is successfully executed


