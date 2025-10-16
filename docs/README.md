# Geometric_lib

## General description

Library includes _4 programs_ files with _2 functions_ for each geometric figure: `area` and `perimetr`

The functions <ins>take several parameters</ins> and in the next line return the calculated value in the form of **return <formula>**

Full descriptions of all functions are <ins>in the code files</ins>

### Links

- Circle.py https://github.com/ViLLXM/geometric_lib/blob/lab2/circle.py
- Rectangle.py https://github.com/ViLLXM/geometric_lib/blob/lab2/rectangle.py
- Sqare.py https://github.com/ViLLXM/geometric_lib/blob/lab2/square.py
- Triangle.py https://github.com/ViLLXM/geometric_lib/blob/lab2/triangle.py
```
import math


def area(r):
    '''
    Принимает число r, возвращает площадь круга радиуса r
    Например, для числа 3 будет возвращено число 28.274333882308138
    '''
    return math.pi * r * r


def perimeter(r):
    '''
    Принимает число r, возвращает площадь круга радиуса r
    Например, для числа 3 будет возвращено число 18.84955592153876
    '''
    return 2 * math.pi * r
```
## Math formulas

### Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = 1/2ah

### Perimeter
- Circle: P = 2πR
- Rectangle: P = 2(a + b)
- Square: P = 4a
- Triangle: P = a + b + c

## History of commits

* Commit 13b00e1bba2efeee0d02d09bd9861960f7bc7124
    Date:   Thu Sep 18 09:36:38 2025 +0300
    `Added comments to functions`

* Commit 6183a34dc69a32047bd80d573f07d8cd51286a87
    Date:   Thu Sep 18 09:08:59 2025 +0300
    `Rectangle.py and and triangle.py was added`

* Commit d078c8d9ee6155f3cb0e577d28d337b791de28e2
    Date:   Thu Mar 4 14:55:29 2021 +0300
    `Docs added`
