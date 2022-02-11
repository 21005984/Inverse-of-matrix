# Inverse-of-matrix

## AIM:
to write a python progarm to find the inverse f the matrix
## ALGORITHM:
### Step 1:
Use import numpy as np.

### Step 2:
enter the input.

### Step 3:
use.append().


### Step 4:
use*to multiply two matrix


### Step 5:
print

## PROGRAM:
```
### NAME:MEIYARASI.V
### REGISTER NUMBER
import numpy as np
l1,l2=[],[]
r,c=int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse=np.linalg.inv(value1)
print(inverse)
```

## OUTPUT:
![Output](.//G1.png)

## RESULT:
thus the program is written to find the matrix
