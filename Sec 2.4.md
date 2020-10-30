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



## Exercise 10

### Statement

求函數的二階導函數。

$y = \dfrac{1+2x}{1-2x}$



### Solution

$y' = \dfrac{d}{dx}(\dfrac{1+2x}{1-2x})$



$= \dfrac{(1-2x)(1+2x)' - (1+2x)(1-2x)'}{(1-2x)^2}$

$= \dfrac{(1-2x)(2) - (1+2x)(-2)}{(1-2x)^2}$

$= \dfrac{(1-2x)(2) + (1+2x)(2)}{(1-2x)^2}$

$= \dfrac{(1-2x+1+2x)(2)}{(1-2x)^2}$

$= \dfrac{4}{(1-2x)^2}$



$y'' = \dfrac{d}{dx}(\dfrac{4}{(1-2x)^2})$

$= \dfrac{(1-2x)^2(4)' - (4)((1-2x)^2)'}{(1-2x)^4}$

$= \dfrac{-4(2(1-2x)\times 2)}{(1-2x)^4}$

$= \dfrac{-16(1-2x)}{(1-2x)^4}$

$= \dfrac{-16}{(1-2x)^3}$



### Answer

$y'' = \dfrac{-16}{(1-2x)^3}$



## Exercise 11

### Statement

求函數的二階導函數。

$y = \sin 2x$



### Solution

令$u = 2x$，則$y= \sin u$

因此$y' = \dfrac{d}{dx} \sin u$

$= \dfrac{d}{du} \sin u \dfrac{du}{dx}$

$= \cos u \dfrac{d}{dx} u$

還原$u$，得到$y' = \cos(2x) \dfrac{d}{dx} 2x = 2\cos(2x)$



$y'' = \dfrac{d}{dx} 2\cos (2x) = \dfrac{d}{dx} 2\cos(u)$

$= \dfrac{d}{du} 2\cos(u) \dfrac{du}{dx}$

$= -2\sin(u) \dfrac{d}{dx} u$

$= -2\sin(2x) \dfrac{d}{dx}2x$

$= -4\sin(2x)$



### Answer

$y'' = -4\sin(2x)$



## Exercise 12

### Statement

求函數的二階導函數。

$y = \tan 3x$



### Solution

令$u = 3x$，則$y = \tan u$

因此$y' = \dfrac{d}{dx} \tan u$

$= \dfrac{d}{du} \tan u \dfrac{du}{dx}$

$= \sec^2 u \dfrac{d}{dx} u$

還原$u$，得到$y' = \sec^2 3x \dfrac{d}{dx} 3x = 3\sec^2 3x$



$y'' = \dfrac{d}{dx}(3\sec^2 3x)$

$ = \dfrac{d}{dx}(3) (\sec^2 3x) + 3 \dfrac{d}{dx}(\sec^2 3x)$

$ = 3\dfrac{d}{dx}(\sec^2 3x)$

$= 3\dfrac{d}{dx} \dfrac{1}{\cos^2 3x}$

$= 3 \dfrac{(\cos^2 3x)(1)' - (1)(\cos^2 3x)'}{(\cos^2 3x)^2}$

$= 3\dfrac{-\dfrac{d}{dx}(\cos^2 3x)}{(\cos^2 3x)}$

令$u = \cos 3x$，則$\dfrac{d}{dx}(\cos^2 3x) = \dfrac{d}{dx}{u^2}$

$= \dfrac{d}{du} u^2 \dfrac{du}{dx} = 2u\dfrac{d}{dx} u$

還原$u$，得到$2\cos 3x \dfrac{d}{dx}(\cos 3x)$

令$t = 3x$，則$2\cos 3x \dfrac{d}{dx}(\cos 3x) = 2\cos 3x \dfrac{d}{dx}(\cos t)$

$= 2\cos 3x \dfrac{d}{dt}(\cos t) \dfrac{dt}{dx}$

$= 2\ \cos 3x (-\sin t) \dfrac{d}{dx} 3x$

$= -6\cos 3x \sin 3x$

因此$\dfrac{d}{dx}(\cos^2 3x) = -6\cos 3x\sin 3x$

所以$y'' = \dfrac{-3(-6\cos 3x\sin 3x)}{(\cos^2 3x)^2}$

$= \dfrac{18\cos 3x \sin 3x}{(\cos^4 3x)}$

$= 18\sec^2 3x \tan 3x$



### Answer

$y'' = 18\sec^2 3x \tan 3x$



## Exercise 13

### Statement

求函數的二階導函數。

$y = \sin x \cos x$



### Solution

$y' = \dfrac{d}{dx}(\sin x \cos x)$

$= (\sin x)\dfrac{d}{dx}(\cos x) + \dfrac{d}{dx}(\sin x)(\cos x)$

$= (\sin x)(-\sin x) + (\cos x)(\cos x)$

$= -\sin^2 x + \cos^2 x$



$y'' = \dfrac{d}{dx}(-\sin^2 x + \cos^2 x)$

令$u = \sin x$, $t = \cos x$

則$y'' = \dfrac{d}{dx}(-u^2 + t^2)$

$= -\dfrac{d}{dx}u^2 + \dfrac{d}{dx} t^2 $

$= -\dfrac{d}{du} u^2 \dfrac{du}{dx} + \dfrac{d}{dt} t^2 \dfrac{dt}{dx}$

$= -2u \dfrac{d}{dx} u + 2t \dfrac{d}{dx} t$

還原$u,\ t$，$y'' = -2(\sin x)\dfrac{d}{dx}(\sin x) + 2(\cos x)\dfrac{d}{dx}(\cos x)$

$= -2\sin x \cos x + 2\cos x \times -\sin x$

$= -4\sin x \cos x$



### Answer

$y'' = -4\sin x\cos x$



## Exercise 14

### Statement

求函數的二階導函數。

$y = x \sin 2x$



### Solution

$y' = \dfrac{d}{dx}(x)(\sin 2x) + (x)\dfrac{d}{dx}(\sin 2x)$

$ = (\sin 2x) + (x)(2\cos 2x)$

$= \sin 2x + 2x\cos 2x$



$y'' = \dfrac{d}{dx}(\sin 2x) + \dfrac{d}{dx}(2x\cos 2x)$

$= (2\cos 2x) + (\dfrac{d}{dx}(2x)\cos 2x) + (2x\dfrac{d}{dx}(\cos 2x))$

$= 2\cos 2x + 2\cos 2x + 2x\times 2\times -\sin2x$

$= 4\cos 2x - 4x\sin 2x$



### Answer

$y'' = 4\cos 2x - 4x\sin 2x$



## Exercise 15

### Statement

求函數的二階導函數。

$y = \sin^3 x$



### Solution

令$u = \sin x$，$y = u^3$

$y' = \dfrac{d}{dx}u^3$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx}$

$= 3u^2 \dfrac{d}{dx} u$



還原$u$，得到$y' = 3\sin^2 x \dfrac{d}{dx} \sin x$

$= 3\sin^2 x\cos x$



$y'' = \dfrac{d}{dx}(3\sin^2 x\cos x)$

$= \dfrac{d}{dx}(3\sin^2 x)(\cos x) + (3\sin^2 x)\dfrac{d}{dx}(\cos x)$

$= (2\sin x\cos x)(\cos x) + (3\sin^2 x)(-\sin x)$

$= 2\sin x\cos^2 x - 3\sin^3 x$

$= \sin x(2\cos^2 x - 3\sin^2 x)$



### Answer

$y'' = \sin x(2\cos^2 x - 3\sin^2 x)$



## Exercise 16

### Statement

求函數的二階導函數。

$y = \sec 3x$



### Solution

$y' = \dfrac{d}{dx}(\sec 3x)$

令$u = 3x$，$y' = \dfrac{d}{dx}\sec u$

$= \dfrac{d}{du} \sec u \dfrac{du}{dx} = 3\tan 3x \sec 3x$



$y'' = \dfrac{d}{dx}(3\tan 3x\sec 3x)$

$= \dfrac{d}{dx}(3\tan 3x)(\sec 3x) + (3\tan 3x)\dfrac{d}{dx}(\sec 3x)$

$= 3\cdot3\sec^2 3x \cdot \sec 3x + 3\tan 3x \cdot 3\tan 3x \cdot \sec 3x$

$= 9\sec^2(3x) + 9\tan^2 3x\sec 3x$

$= 9(\sec^2 3x + \tan^2 3x \sec 3x)$



### Answer

$y'' = 9(\sec^2 3x + \tan^2 3x\sec 3x)$



## Exercise 17

### Statement

求函數的二階導函數。

$f(t) = \sec^3 2t$



### Solution

令$u = \sec 2t$，則$f(t) = u^3$

所以$f'(t) = \dfrac{d}{dt} u^3 = \dfrac{d}{du}u^3\dfrac{du}{dt} = 3u^2 \dfrac{d}{dt} u$

還原$u$，得到$f'(t) = 3(\sec 2t)^2 \dfrac{d}{dt} (\sec 2t)$

令$v = 2t$，因此$f'(t) = 3(\sec 2t)^2 \dfrac{d}{dt} (\sec v)$

$= 3(\sec 2t)^2 \dfrac{d}{dv} (\sec v) \dfrac{dv}{dt}$

$= 3(\sec 2t)^2 \dfrac{d}{dv} (\sec v) \dfrac{dv}{dt}$

$= 3(\sec 2t)^2 \sec v\tan v \dfrac{d}{dt}v$

還原$v$，得到$f'(t) = 3(\sec 2t)^2 \sec 2t \tan 2t \dfrac{d}{dt} 2t$

$= 6(\sec 2t)^2 \sec 2t \tan 2t$

$= 6(\sec 2t)^3 \tan 2t$



$f''(t) = \dfrac{d}{dt}(6(\sec 2t)^3 \tan 2t)$

$= \dfrac{d}{dt}(6(\sec 2t)^3)(\tan 2t)(6(\sec 2t)^3)\dfrac{d}{dt}(\tan 2t)$

令$u = \sec 2t$，$v = 2t$

$f''(t) = \dfrac{d}{dt}(6u^3)(\tan 2t)+(6(\sec 2t)^3)\dfrac{d}{dt}(v)$

$= (\dfrac{d}{du}(6u^3) \dfrac{du}{dt})(\tan 2t)+(6(\sec 2t)^3)(\dfrac{d}{dv}(\tan v)\dfrac{dv}{dt})$

$= (18u^2 \dfrac{d}{dt}u)(\tan 2t)+(6(\sec 2t)^3)(\sec^2v\dfrac{d}{dt}v)$

還原$u, v$，$f''(t) = (18\sec^2 2t \dfrac{d}{dt}(\sec 2t))(\tan 2t)+(6(\sec 2t)^3)(\sec^22t\dfrac{d}{dt}(2t))$

$= (18\sec^2 2t \dfrac{d}{dt}(\sec 2t))(\tan 2t)+(6(\sec 2t)^3)(\sec^22t\dfrac{d}{dt}(2t))$

$= (36\sec^2 2t \tan 2t \sec 2t)(\tan 2t)+(6(\sec 2t)^3)(2\sec^22t)$

$= (36\sec^2 2t \tan 2t \sec 2t)(\tan 2t)+(6\sec^3 2t)(2\sec^22t)$

$= (36\sec^3 2t)(\tan^2 2t)+(12\sec^5 2t)$

$=(12\sec^3 2t)(3\tan^2 2t + \sec^2 2t)$



### Answer

$f''(t) =(12\sec^3 2t)(3\tan^2 2t + \sec^2 2t)$



## Exercise 18

### Statement

求函數的二階導函數。

$y = \sin(x^2+1)$



### Solution

令$u = x^2+1$，$y = \sin u$

$y' = \dfrac{d}{dx} \sin u = \dfrac{d}{du} \sin u \dfrac{du}{dx} = \cos u \dfrac{d}{dx} u$

還原$u$，得到$y' = \cos (x^2+1) \dfrac{d}{dx} (x^2+1)$

$= (2x)\cos(x^2+1)$



$y'' = \dfrac{d}{dx}(2x\cos(x^2+1))$

$= \dfrac{d}{dx}(2x)(\cos(x^2+1)) + (2x)\dfrac{d}{dx}(\cos(x^2+1))$

$= 2\cos(x^2+1) + 2x\dfrac{d}{dx}(\cos(x^2+1))$

$= 2\cos(x^2+1) + 2x\dfrac{d}{dx}(\cos(u))$

$= 2\cos(x^2+1) + 2x\dfrac{d}{du}(\cos(u)) \dfrac{du}{dx}$

$= 2\cos(x^2+1) + 2x(-\sin u) \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = 2\cos(x^2+1) + 2x(-\sin (x^2+1)) \dfrac{d}{dx} (x^2+1)$

$= 2\cos(x^2+1) - 4x^2\sin (x^2+1)$



### Answer

$y'' = 2\cos(x^2+1) - 4x^2\sin (x^2+1)$



## Exercise 19

### Statement

求函數的二階導函數。

$y = \dfrac{1}{(1-2x)^3}$



### Solution

$y = \dfrac{1}{(1-2x)^3} = (1-2x)^{-3}$

令$u = 1-2x$，$y = u^{-3}$

$y' = \dfrac{d}{dx} u^{-3}$

$= \dfrac{d}{du} u^{-3} \dfrac{du}{dx}$

$= -3u^{-4} \dfrac{d}{dx} u$

還原$u$，得到$y' = -3(1-2x)^{-4} \dfrac{d}{dx} (1-2x)$

$= -3(1-2x)^{-4}(-2) = 6(1-2x)^{-4}$



$y'' = \dfrac{d}{dx} 6(1-2x)^{-4} = \dfrac{d}{dx}6u^{-4}$

$= \dfrac{d}{du}6u^{-4} \dfrac{du}{dx}$

$= -24u^{-5} \dfrac{d}{dx} u$

還原$u$，得到$y' = -24(1-2x)^{-5} \dfrac{d}{dx}(1-2x)$

$= 48(1-2x)^{-5} = \dfrac{48}{(1-2x)^5}$



### Answer

$y'' = \dfrac{48}{(1-2x)^5}$



## Exercise 20

### Statement

求函數的二階導函數。

$y = \dfrac{1+x^2}{1-x^2}$



### Solution

$y' = \dfrac{(1-x^2)(1+x^2)' - (1+x^2)(1-x^2)'}{(1-x^2)^2}$

$= \dfrac{(1-x^2)(2x) - (1+x^2)(-2x)}{(1-x^2)^2}$

$= \dfrac{(1-x^2)(2x) + (1+x^2)(2x)}{(1-x^2)^2}$

$= \dfrac{4x}{(1-x^2)^2}$



$y'' = \dfrac{d}{dx} \dfrac{4x}{(1-x^2)^2}$

$= \dfrac{(1-x^2)^2\dfrac{d}{dx}(4x) - (4x)\dfrac{d}{dx}((1-x^2)^2)}{(1-x^2)^4}$

$= \dfrac{4(1-x^2)^2 - (4x)(-4x(1-x^2))}{(1-x^2)^4}$

$= \dfrac{4(1-x^2)(1-x^2) - (4x)(-4x(1-x^2))}{(1-x^2)^4}$

$= \dfrac{(4-4x^2)(1-x^2) + 16x^2(1-x^2)}{(1-x^2)^4}$

$= \dfrac{(4+12x^2)(1-x^2)}{(1-x^2)^4}$

$= \dfrac{4(1+3x^2)}{(1-x^2)^3}$



### Answer

$y'' = \dfrac{4(1+3x^2)}{(1-x^2)^3}$



## Exercise 21

### Statement

求函數的二階導函數。

$y = \tan \sqrt{x}$



### Solution

$y = \tan \sqrt{x}$，令$u = \sqrt{x}$

則$y' = \dfrac{d}{dx}(\tan u) = \dfrac{d}{du}\tan u \dfrac{du}{dx} = \sec^2 u \dfrac{d}{dx} u$

還原$u$，得到$y' = \sec^2(\sqrt{x}) \dfrac{d}{dx}\sqrt{x} = \dfrac{\sec^2(\sqrt{x})}{2\sqrt{x}}$



$y'' = \dfrac{d}{dx} \dfrac{\sec^2(\sqrt{x})}{2\sqrt{x}}$

$= \dfrac{(2\sqrt{x})(\sec^2(\sqrt{x}))' - (\sec^2(\sqrt{x}))(2\sqrt{x})'}{(2\sqrt{x})^2}$

考慮$\dfrac{d}{dx}(\sec^2(\sqrt{x}))$，令$u = \sec{\sqrt{x}}$

因此$\dfrac{d}{dx}(\sec^2(\sqrt{x})) = \dfrac{d}{dx} u^2 = 2u \dfrac{d}{dx}u$

還原$u$得到$2\sec\sqrt{x} \dfrac{d}{dx}(\sec\sqrt{x})$

$= 2\sec\sqrt{x}(\tan\sqrt{x}\sec\sqrt{x}\dfrac{1}{2\sqrt{x}}) =2\tan\sqrt{x}\sec^2{\sqrt{x}}\dfrac{1}{2\sqrt{x}}$

$y'' = \dfrac{(2\sqrt{x})(2\tan\sqrt{x}\sec^2{\sqrt{x}}\dfrac{1}{2\sqrt{x}}) - (\sec^2(\sqrt{x}))\dfrac{2}{2\sqrt{x}}}{(2\sqrt{x})^2}$

$= \dfrac{(2\sqrt{x}2\tan\sqrt{x}\sec^2{\sqrt{x}})\dfrac{1}{2\sqrt{x}} - (\sec^2(\sqrt{x}))\dfrac{2}{2\sqrt{x}}}{(2\sqrt{x})^2}$

$= \dfrac{(4\sqrt{x}\tan\sqrt{x}\sec^2{\sqrt{x}} - 2\sec^2\sqrt{x})\dfrac{1}{2\sqrt{x}}}{(2\sqrt{x})^2}$

$= \dfrac{(4\sqrt{x}\tan\sqrt{x}\sec^2{\sqrt{x}} - 2\sec^2\sqrt{x})\dfrac{1}{2\sqrt{x}}}{(2\sqrt{x})^2}$

$= \dfrac{(4\sqrt{x}\tan\sqrt{x}\sec^2{\sqrt{x}} - 2\sec^2\sqrt{x})}{(2\sqrt{x})^3}$

$= \dfrac{2\sec^2{\sqrt{x}}(2\sqrt{x}\tan\sqrt{x} - 1)}{(2\sqrt{x})^3}$

$= \dfrac{2\sec^2{\sqrt{x}}(2\sqrt{x}\tan\sqrt{x} - 1)}{8x\sqrt{x}}$

$= \dfrac{\sec^2{\sqrt{x}}(2\sqrt{x}\tan\sqrt{x} - 1)}{4x\sqrt{x}}$



### Answer

$y'' = \dfrac{\sec^2{\sqrt{x}}(2\sqrt{x}\tan\sqrt{x} - 1)}{4x\sqrt{x}}$



## Exercise 22

### Statement

求函數的二階導函數。

$y = (1+x^3)^6$



### Solution

令$u = 1+x^3$，則$y = u^6$

$y' = \dfrac{d}{dx} u^6 = \dfrac{d}{du} u^6 \dfrac{du}{dx} = 6u^5 \dfrac{d}{dx} u$

還原$u$，得到$y' = 6(1+x^3)^5 \dfrac{d}{dx}(1+x^3)$

$= 6(1+x^3)^5(3x^2)$

$= (18x^2)(1+x^3)^5$



$y'' = \dfrac{d}{dx}((18x^2)(1+x^3)^5)$

$= \dfrac{d}{dx}(18x^2)(1+x^3)^5 + (18x^2)\dfrac{d}{dx}((1+x^3)^5)$

$= (36x)(1+x^3)^5 + (18x^2)\dfrac{d}{dx}(u^5)$

$= (36x)(1+x^3)^5 + (18x^2)(\dfrac{d}{du}u^5\dfrac{du}{dx})$

$= (36x)(1+x^3)^5 + (18x^2)(\dfrac{d}{du}u^5\dfrac{du}{dx})$

$= (36x)(1+x^3)^5 + (18x^2)(5u^4\dfrac{d}{dx}u)$

$= (36x)(1+x^3)^5 + (18x^2)(5(1+x^3)^4\dfrac{d}{dx}(1+x^3))$

$= (36x)(1+x^3)^5 + (18x^2)(15x^2(1+x^3)^4)$

$= (36x(1+x^3))(1+x^3)^4 + (18x^2)(15x^2(1+x^3)^4)$

$= (36x(1+x^3)+(18x^2)(15x^2))(1+x^3)^4$

$= (36x(1+x^3)+(18x^2)(15x^2))(1+x^3)^4$

$= 18x(2(1+x^3)+x(15x^2))(1+x^3)^4$

$= 18x(2+2x^3+15x^3)(1+x^3)^4$

$= 18x(2+17x^3)(1+x^3)^4$



### Answer

$y'' = 18x(2+17x^3)(1+x^3)^4$



## Exercise 23

### Statement

求函數的二階導函數。

$y = \sqrt{x^2+1}$



### Solution

令$u = x^2+1$，則$y = \sqrt{u}$

$y' = \dfrac{d}{dx}\sqrt{u}$

$= \dfrac{d}{du} \sqrt{u} \dfrac{du}{dx}$

$= \dfrac{1}{2\sqrt{u}} \dfrac{d}{dx} (x^2+1)$

$= \dfrac{1}{2\sqrt{x^2+1}}\times 2x$

$= \dfrac{2x}{2\sqrt{x^2+1}}$

$= \dfrac{x}{\sqrt{x^2+1}}$



$y'' = \dfrac{d}{dx}(\dfrac{x}{\sqrt{x^2+1}})$

$= \dfrac{(\sqrt{x^2+1})(x)' - (x)(\sqrt{x^2+1})'}{x^2+1}$

$= \dfrac{\sqrt{x^2+1} - (x)(\dfrac{x}{\sqrt{x^2+1}})}{x^2+1}$

$= \dfrac{\sqrt{x^2+1} - (\dfrac{x^2}{\sqrt{x^2+1}})}{x^2+1}$

$= \dfrac{\dfrac{x^2+1}{\sqrt{x^2+1}} - (\dfrac{x^2}{\sqrt{x^2+1}})}{x^2+1}$

$= \dfrac{1}{(\sqrt{x^2+1})x^2+1}$

$= \dfrac{1}{\sqrt{(x^2+1)^3}}$



### Answer

$y'' = \dfrac{1}{\sqrt{(x^2+1)^3}}$



## Exercise 24

### Statement

求函數的二階導函數。

$y= (\dfrac{x+3}{x})^4$



### Solution

令$u = \dfrac{x+3}{x}$，則$y = u^4$

$y' = \dfrac{d}{dx} u^4 = \dfrac{d}{du} u^4 \dfrac{du}{dx}$

$= 4u^3 \dfrac{d}{dx} u$

還原$u$，得到$y' = 4(\dfrac{x+3}{x})^3 \dfrac{d}{dx}(\dfrac{x+3}{x})$

$= 4(\dfrac{x+3}{x})^3 \dfrac{(x)(x+3)' - (x+3)(x)'}{x^2} = 4(\dfrac{x+3}{x})^3 \dfrac{(x) - (x+3)}{x^2}$

$4(\dfrac{x+3}{x})^3 \dfrac{-3}{x^2}$

$= -\dfrac{12}{x^2} (\dfrac{x+3}{x})^3$



$y'' = \dfrac{d}{dx}(-\dfrac{12}{x^2} (\dfrac{x+3}{x})^3)$

$= \dfrac{d}{dx}(-\dfrac{12}{x^2})(\dfrac{x+3}{x})^3 + (-\dfrac{12}{x^2})\dfrac{d}{dx}(\dfrac{x+3}{x})^3$

$= \dfrac{x^2(-12)' - (-12)(x^2)'}{x^4}(\dfrac{x+3}{x})^3 + (-\dfrac{12}{x^2})(-\dfrac{3}{x^2})3(\dfrac{x+3}{x})^2$ 

$= \dfrac{-(-12)2x}{x^4}(\dfrac{x+3}{x})^3 + (\dfrac{108}{x^4})(\dfrac{x+3}{x})^2$

$= \dfrac{24x}{x^4}(\dfrac{x+3}{x})^3 + (\dfrac{108}{x^4})(\dfrac{x+3}{x})^2$

$= \dfrac{24x(x+3)}{x^5}(\dfrac{x+3}{x})^2 + (\dfrac{108}{x^4})(\dfrac{x+3}{x})^2$

$= \dfrac{24x(x+3)+108x}{x^5}(\dfrac{x+3}{x})^2$

$= \dfrac{12x(2(x+3)+9)}{x^5}(\dfrac{x+3}{x})^2$

$= \dfrac{12x(2x+15)}{x^5}(\dfrac{x+3}{x})^2$

$= \dfrac{12(2x+15)}{x^4}(\dfrac{x+3}{x})^2$

$= \dfrac{12(2x+15)(x+3)^2}{x^6}$



### Answer

$y'' = \dfrac{12(2x+15)(x+3)^2}{x^6}$



## Exercise 25

### Statement

假設$f(x) = x\sin(2x)$，求$f'''(\pi)$



### Solution

$f'(x) = \dfrac{d}{dx}(x\sin (2x)) = \dfrac{d}{dx}(x)\sin 2x + x\dfrac{d}{dx}(\sin 2x)$

$= \sin 2x + 2x\cos 2x$

$f''(x) = \dfrac{d}{dx}(\sin 2x) + \dfrac{d}{dx}(2x\cos 2x)$

$= (\cos 2x) + \dfrac{d}{dx}(2x)\cos 2x + 2x\dfrac{d}{dx}(\cos 2x)$

$= \cos 2x + 2\cos 2x + 2x(-2\sin 2x)$

$= 3\cos 2x -4x\sin 2x$

$f'''(x) = \dfrac{d}{dx}(3\cos 2x - 4x\sin 2x)$

$= \dfrac{d}{dx}(3\cos 2x) - \dfrac{d}{dx}{4x\sin 2x}$

$= (-6\sin 2x) - (\dfrac{d}{dx}(4x)\sin 2x + 4x\dfrac{d}{dx}(\sin 2x))$

$= -6\sin 2x - 4\sin 2x + 4x(2\cos 2x)$

$= -6\sin 2x - 4\sin 2x + 8x\cos 2x$

因此，$f'''(x) = -6\sin 2\pi - 4\sin 2\pi + 8\pi \cos 2\pi = 8\pi$



### Answer

$f'''(x) = 8\pi$



## Exercise 26

### Statement

假設$f(x) = \dfrac{1}{1-2x}$，求$\displaystyle \lim_{x\rightarrow 1} \dfrac{f^{(6)}(x)-f^{(6)}(1)}{x-1}$



### Solution

考慮微分定義，相當於求$f^{(7)}(x)$

$f(x) = \dfrac{1}{1-2x} = (1-2x)^{-1}$

$f'(x) = \dfrac{(1-2x)(1)' - (1)(1-2x)'}{(1-2x)^2} = \dfrac{2}{(1-2x)^2} =2\cdot 1\cdot(1-2x)^{-2}$

$f''(x) = \dfrac{d}{dx}(2(1-2x)^{-2}) = 8(1-2x)^{-3} = 2^2\cdot 1\cdot 2\cdot (1-2x)^{-3}$

$f'''(x) = \dfrac{d}{dx}(-12(1-2x)^{-3}) = 48(1-2x)^{-4} = 2^3\cdot 1\cdot 2\cdot 3\cdot(1-2x)^{-3}$

推得規律，得到$f^{(n)}(x) = 2^n\times n!\times (1-2x)^{-n-1}$

因此$f^{(7)}(x) = 2^7\times 7!\times (1-2x)^{-8}$

故$f^{(7)}(1) = 2^7\times 7!\times (-1)^{-8} = 2^7\times 7!$



### Answer

$\displaystyle \lim_{x\rightarrow 1} \dfrac{f^{(6)}(x)-f^{(6)}(1)}{x-1} = 2^7\times 7!$



## Exercise 27

### Statement

假設$g(1) = 2$、$g(3) = 1$、$g'(1) = 3$、$g'(3) = 4$且$f(3x) = xg(x^2)$，求$f'(3)$



### Solution

$f(3x) = xg(x^2)$

$\dfrac{d}{dx}f(3x) = \dfrac{d}{dx}(xg(x^2))$

$3\times f'(3x) = (\dfrac{d}{dx}(x)g(x^2) + x\dfrac{d}{dx}g(x^2))$

$3f'(3x) = g(x^2) + xg'(x^2)\times 2x)$

$3f'(3x) = g(x^2) + 2x^2g'(x^2)$

欲求$f'(3x)$，因此$x$帶入$1$。

$3f'(3) = g(1) + 2\times g'(1) = 2 + 2\times(3) = 8$

因此$f'(3) = \dfrac{8}{3}$



### Answer

$f'(3) = \dfrac{8}{3}$



## Exercise 28

### Statement

假設$f'(x) + (x-1)(f(x))^2 = x$，且$f(1) = 2$，求$f'(1) + f''(1)$



### Solution

將$x$帶入$1$，可以得到$f'(1) + 0 = 1$，因此$f'(1) = 1$

等號兩邊微分

$\dfrac{d}{dx}(f'(x) + (x-1)(f(x))^2) = \dfrac{d}{dx}(x)$

$\dfrac{d}{dx} f'(x) + \dfrac{d}{dx}(x-1)((f(x))^2) = 1$

$\Rightarrow f''(x) + (\dfrac{d}{dx}(x-1)(f(x))^2 + (x-1)\dfrac{d}{dx}(f(x))^2$

$\Rightarrow f''(x) + (f(x))^2 + (x-1)(2f(x)f'(x)) = 1$

$x$帶入$1$，帶入$f(1)$與$f'(1)$，得到

$f''(1) + 2^2 + 0\cdot(2\times 2\times 1) = 1$，得到$f''(1) = -3$

因此$f'(1) + f''(1) = 1 - 3 = -2$



### Answer

$f'(1) + f''(1) =  -2$

