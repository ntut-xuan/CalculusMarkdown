# 洪揮霖微積分Practice Ch2.4

###### tags: `微積分題目紀錄`

## Exercise 1

### Statement

求函數的二階導函數。

$f(x) = x^7 - x^3 + 3x^2 - 1$



### Solution

$f'(x) = \dfrac{d}{dx} x^7 - \dfrac{d}{dx} x^3 + \dfrac{d}{dx} 3x^2 - \dfrac{d}{dx} 1$

$= 7x^6 - 3x^2 + 6x$

$f''(x) = \dfrac{d}{dx} 7x^6 - \dfrac{d}{dx} 3x^2 + \dfrac{d}{dx} 6x$

$= 42x^5 - 6x + 6$



### Answer

$f''(x) = 42x^5 - 6x + 6$



## Exercise 2

### Statement

求函數的二階導函數。

$f(x) = x^3 - \dfrac{2}{x^3} - 3$



### Solution

$f(x) = x^3 - \dfrac{2}{x^3} - 3$

$= x^3 -2x^{-3} - 3$



$f'(x) = \dfrac{d}{dx} x^3 - \dfrac{d}{dx} 2x^{-3} - \dfrac{d}{dx} 3$

$= 3x^2 + 6x^{-4}$



$f''(x) = \dfrac{d}{dx} 3x^2 + \dfrac{d}{dx} 6x^{-4}$

$= 6x - 24x^{-5}$



### Answer

$f''(x) = 6x-24x^{-5}$



## Exercise 3

### Statement

求函數的二階導函數。

$f(x) = \sqrt{x} + \dfrac{3}{x^2}$



### Solution

$f(x) = \sqrt{x} + \dfrac{3}{x^2}$

$= x^\frac{1}{2} + 3x^{-2}$



$f'(x) = \dfrac{d}{dx} x^\frac{1}{2} + \dfrac{d}{dx} 3x^{-2}$

$= \dfrac{1}{2} x^\frac{-1}{2} - 6x^{-3}$



$f''(x) = \dfrac{d}{dx} \dfrac{1}{2} x^\frac{-1}{2} - \dfrac{d}{dx} 6x^{-3}$

$= \dfrac{-1}{4}x^\frac{-3}{2} + 18x^{-4}$

$= -\dfrac{1}{4\sqrt{x^3}} + \dfrac{18}{x^4}$



### Answer

$f''(x) = -\dfrac{1}{4\sqrt{x^3}} + \dfrac{18}{x^4}$



## Exercise 4

### Statement

求函數的二階導函數。

$f(x) = 3x^\frac{2}{3} - x^2 + 2$



### Solution

$f'(x) = \dfrac{d}{dx} 3x^\frac{2}{3} - \dfrac{d}{dx} x^2 +\dfrac{d}{dx}  2$

$= 2x^\frac{-1}{3} -2x$



$f''(x) = 2x^\frac{-1}{3} -2x$

$= \dfrac{d}{dx} 2x^\frac{-1}{3} - \dfrac{d}{dx} 2x$

$= \dfrac{-2}{3}x^\frac{-4}{3} - 2$

$= \dfrac{-2}{3\sqrt[3]{x^4}} - 2$



### Answer

$f''(x) = \dfrac{-2}{3\sqrt[3]{x^4}} - 2$



## Exercise 5

### Statement

求函數的二階導函數。

$f(x) = \dfrac{1+x}{1-x}$



### Solution

$f'(x) = \dfrac{d}{dx}\dfrac{1+x}{1-x}$

$= \dfrac{(1-x)(1+x)' - (1+x)(1-x)'}{(1-x)^2}$

$= \dfrac{(1-x)(1)-(1+x)(-1)}{(1-x)^2}$

$= \dfrac{(1-x)-(-1-x)}{(1-x)^2}$

$= \dfrac{2}{(1-x)^2}$

$= \dfrac{2}{(1-x)^2}$



$f''(x) = \dfrac{d}{dx} (\dfrac{2}{(1-x)^2})$

$= \dfrac{(1-x)^2(2)' - 2((1-x)^2)'}{(1-x)^4}$

$= \dfrac{(1-x)^2(0) - 2(2(1-x)\times (-1))}{(1-x)^4}$

$= \dfrac{4-4x}{(1-x)^4}$

$= \dfrac{4}{(1-x)^3}$

### Answer

$f''(x) = \dfrac{4}{(1-x)^3}$



## Exercise 6

### Statement

求函數的二階導函數。

$f(x) = (x^2+3)^3$



### Solution

令$u = x^2+3$，則$f(x) = u^3$

因此$f'(x) = \dfrac{d}{dx} u^3$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx}$

$= 3u^2 \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = 3(x^2+3)^2 \dfrac{d}{dx}(x^2 + 3)$

$= 3(x^2+3)^2 \times 2x$

$= 6x(x^2+3)^2$



$f''(x) = \dfrac{d}{dx}(6x(x^2+3)^2)$

$= \dfrac{d}{dx}(6x)(x^2+3)^2 + 6x\dfrac{d}{dx}((x^2+3)^2)$

$ = 6(x^2+3)^2 + 6x(2(x^2+3)\times 2x)$

$ = 6(x^2+3)^2 + 24x^2(x^2+3)$



### Answer

$f''(x) = 6(x^2+3)^2 + 24x^2(x^2+3)$



## Exercise 7

### Statement

求函數的二階導函數。

$f(x) = (2x-3)^5$



### Solution

$f'(x) = \dfrac{d}{dx}(2x-3)^5$

$= 5(2x-3)^4\times 2 = 10(2x-3)^4$



$f''(x) = \dfrac{d}{dx}(10(2x-3)^4)$

$= \dfrac{d}{dx}(10)(2x-3)^4 + (10)\dfrac{d}{dx}((2x-3)^4)$

$= (10)(4(2x-3)^3 \times 2)$

$= 80(2x-3)^3$



### Answer

$f''(x) = 80(2x-3)^3$



## Exercise 8

### Statement

求函數的二階導函數。

$f(x) = \dfrac{x}{x^2+1}$


### Solution

$f'(x) = \dfrac{d}{dx}(\dfrac{x}{x^2+1}) = \dfrac{(x^2+1)(x)' - (x)(x^2+1)'}{(x^2+1)^2}$

$=\dfrac{(x^2+1) - (x)(2x)}{(x^2+1)^2}$

$=\dfrac{(x^2+1) - 2x^2}{(x^2+1)^2}$

$=\dfrac{-x^2+1}{(x^2+1)^2}$



$f''(x) = \dfrac{d}{dx}(\dfrac{-x^2+1}{(x^2+1)^2})$

$= \dfrac{(x^2+1)^2(-x^2+1)' - (-x^2+1)((x^2+1)^2)'}{(x^2+1)^4}$

$= \dfrac{(x^2+1)^2(-2x) - (-x^2+1)(2(x^2+1)\times 2x)}{(x^2+1)^4}$

$= \dfrac{(-2x)(x^2+1)^2 - (-4x^3+4x)(x^2+1)}{(x^2+1)^4}$

$= \dfrac{(-2x(x^2+1))(x^2+1) - (-4x^3+4x)(x^2+1)}{(x^2+1)^4}$

$= \dfrac{(-2x(x^2+1)- (-4x^3+4x))(x^2+1)}{(x^2+1)^4}$

$= \dfrac{(-2x^3-2x+4x^3-4x)(x^2+1)}{(x^2+1)^4}$

$= \dfrac{(2x^3-6x)(x^2+1)}{(x^2+1)^4}$

$= \dfrac{(2x^3-6x)}{(x^2+1)^3}$

$= \dfrac{2x(x^2-3)}{(x^2+1)^3}$



### Answer

$f''(x) = \dfrac{2x(x^2-3)}{(x^2+1)^3}$



## Exercise 9

### Statement

$y = \dfrac{1}{1-3x}$



### Solution

$y' = \dfrac{d}{dx}(\dfrac{1}{1-3x}) = \dfrac{(1-3x)(1)' - (1)(1-3x)'}{(1-3x)^2}$

$= \dfrac{-(-3)}{(1-3x)^2} = \dfrac{3}{(1-3x)^2}$



$y'' = \dfrac{d}{dx}(\dfrac{3}{(1-3x)^2}) = \dfrac{(1-3x)^2(3)' - 3((1-3x)^2)'}{(1-3x)^4}$

$= \dfrac{-3(2(1-3x)\times (-3))}{(1-3x)^4}$

$= \dfrac{18}{(1-3x)^3}$



### Answer

$y'' = \dfrac{18}{(1-3x)^3}$

