# Name: Ogbodo Uonna
# Matric Number: 21120612480
# Email: udonna.ogbodo@pau.edu.ng

## Project 1
## Pseudocode for project 1

#### START
#### INPUT b
#### COMPUTE b - 17= answer
#### IF b>17
#### COMPUTE answer*2
#### PRINT answer*2
#### ELSE
#### IF b<17
#### OUTPUT t=b-17
#### PRINT t
#### STOP

![image.png](attachment:image.png)


```python
b=int(input("input number"))
ans= b-17
if b > 17:
    print(ans*2)
else:
    t=b-17
    print (t)
     
```

    input number20
    6
    

## Project 2
## Pseudocode for project 2

#### START
#### INPUT a,b,c,
#### COMPUTE a + b + c = Ans
#### PRINT Ans
#### IF a==b, b==c, c==a
#### PRINT Ans*3
#### STOP


![image.png](attachment:image.png)


```python
a = int(input("input number"))
b = int(input("input number"))
c = int(input("input number"))

ans = a + b + c 
if a==b and b==c and c==a:
    print(ans*3) 
else:
        print(ans)
```

    input number3
    input number3
    input number3
    27
    

## Project 3
## Pseudocode for project 3

#### START
#### INPUT a,b
#### COMPUTE a + b= Z
#### COMPUTE a - b = X
#### IF a=b
#### PRINT true
#### ELIF Z=5
#### PRINT true
#### ELIF X=5 
#### PRINT true
#### ELSE
#### PRINT false
#### STOP

![image.png](attachment:image.png)


```python
a = int(input("input number"))
b = int(input("input number"))
if a+b==5:
    print("TRUE")
elif a-b==5:
    print("TRUE")
elif a==b:
    print("TRUE")
```

    input number3
    input number3
    TRUE
    

## Project 4
## Pseudocode for project 4

#### START
#### INPUT a,b,c
#### INPUT x1=max(a,b,c)
#### INPUT x2=min(a,b,c)
#### INPUT x3=(a+b+c)-x1-x2
#### STOP

![image.png](attachment:image.png)


```python
a = int(input("input number"))
b = int(input("input number"))
c = int(input("input number"))

x1 = max(a,b,c)
x2 = min(a,b,c)
x3 = (a + b + c)-x1-x2

print(x1, x2, x3)
```

    input number3
    input number4
    input number5
    5 3 4
    

## PROJECT 5
## Pseudocode for project 5

#### START
#### INPUT a
#### IF a<6
#### PRINT a**a
#### ELSE
#### PRINT a
#### STOP

![image.png](attachment:image.png)


```python
    a = int(input("input number"))
    if a < 6:
        print (a**a)
    else:
        a>6
        print (a)
```

    input number5
    3125
    


```python

```
