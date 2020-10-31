# 洪揮霖微積分Practice Ch2.5



###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$x^2+3y^2=7$



### Solution

$\dfrac{d}{dx}(x^2+3y^2) = \dfrac{d}{dx}(7)$

$\dfrac{d}{dx}(x^2) + \dfrac{d}{dx}(3y^2) = \dfrac{d}{dx}(7)$

$2x + \dfrac{d}{dy}(3y^2)\dfrac{dy}{dx} = 0$

$2x + 6y\dfrac{dy}{dx} = 0$

$6y\dfrac{dy}{dx} = -2x$

$\dfrac{dy}{dx} = \dfrac{-2x}{6y} = -\dfrac{x}{3y}$



### Answer

$\dfrac{dy}{dx} = -\dfrac{x}{3y}$



## Exercise 2

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$y^2-2y=3x$



### Solution

$\dfrac{d}{dx}(y^2-2y) = \dfrac{d}{dx}(3x)$

$\dfrac{d}{dx}y^2 - \dfrac{d}{dx}2y = 3$

$= \dfrac{d}{dy}y^2\dfrac{dy}{dx} - \dfrac{d}{dy}2y\dfrac{dy}{dx} =  3$

$= 2y\dfrac{dy}{dx} - 2\dfrac{dy}{dx} = 3$

$= (2y-2)\dfrac{dy}{dx} = 3$

$\dfrac{dy}{dx} = \dfrac{3}{(2y-2)}$



### Answer

$\dfrac{dy}{dx} = \dfrac{3}{(2y-2)}$



## Exercise 3

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$xy^2+3yx^2-5=0$



### Solution

$\dfrac{d}{dx}(xy^2+3x^2y-5) = \dfrac{d}{dx} 0$

$\dfrac{d}{dx}(xy^2) + \dfrac{d}{dx}(3x^2y) - \dfrac{d}{dx}(5) = 0$

$\dfrac{d}{dx}(x)y^2 + x\dfrac{d}{dx}(y^2) + \dfrac{d}{dx}(3x^2)y + 3x^2\dfrac{d}{dx}(y) - \dfrac{d}{dx}(5) = 0$

$y^2 + x\dfrac{d}{dy}(y^2)\dfrac{dy}{dx} +  6xy + 3x^2\dfrac{d}{dy}y\dfrac{dy}{dx} - 0 = 0$

$y^2+2xy\dfrac{dy}{dx} + 6xy + 3x^2\dfrac{dy}{dx} = 0$

$(2xy+3x^2)\dfrac{dy}{dx} = -y^2-6xy$

$\dfrac{dy}{dx} = \dfrac{-y^2-6xy}{2xy+3x^2}$

$= -\dfrac{y^2+6xy}{2xy+3x^2}$



### Answer

$\dfrac{dy}{dx} = -\dfrac{y^2+6xy}{2xy+3x^2}$



## Exercise 4

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$\dfrac{2}{x} - \dfrac{3}{y} = 1$



### Solution

$\dfrac{2}{x} - \dfrac{3}{y} = 1$

$= 2x^{-1} - 3y^{-1} = 1$



$\dfrac{d}{dx}(\dfrac{2}{x} - \dfrac{3}{y}) = \dfrac{d}{dx}(1)$

$\Rightarrow \dfrac{d}{dx}(2x^{-1}) - \dfrac{d}{dx}(3y^{-1}) = \dfrac{d}{dx}(1)$

$\Rightarrow  -2x^{-2} - \dfrac{d}{dy}(3y^{-1})\dfrac{dy}{dx} = 0$

$\Rightarrow -2x^{-2} + 3y^{-2}\dfrac{dy}{dx} = 0$

$3y^{-2}\dfrac{dy}{dx} = 2x^{-2}$

$\dfrac{dy}{dx} = \dfrac{2x^{-2}}{3y^{-2}} = \dfrac{2y^2}{3x^2}$



## Exercise 5

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$x^2y + 2xy^2 - x + 3 = 0$



### Solution

$\dfrac{d}{dx}(x^2y + 2xy^2 - x + 3) = \dfrac{d}{dx}(0)$

$\dfrac{d}{dx}(x^2y) + \dfrac{d}{dx}(2xy^2) + \dfrac{d}{dx}(-x) + \dfrac{d}{dx}(3) = 0$

$(\dfrac{d}{dx}(x^2)y + x^2\dfrac{d}{dx}y + \dfrac{d}{dx}(2x)y^2 + 2x\dfrac{d}{dx}(y^2) - \dfrac{d}{dx}x + \dfrac{d}{dx}3) = 0$

$= 2xy + x^2\dfrac{d}{dy}y \dfrac{dy}{dx} + 2y^2 + 2x\dfrac{d}{dy}(y^2)\dfrac{dy}{dx} - 1 = 0$

$= 2xy + x^2\dfrac{dy}{dx} + 2y^2 + 2x2y\dfrac{dy}{dx} = 1$

$(x^2+4xy)\dfrac{dy}{dx} = 1-2xy-2y^2$

$\dfrac{dy}{dx} = \dfrac{1-2xy-2y^2}{x^2+4xy}$



### Answer

$\dfrac{dy}{dx} = \dfrac{1-2xy-2y^2}{x^2+4xy}$



## Exercise 6

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$(x+2)^2 + 3(y-1)^2 = 1$



### Solution

令$u = x+2, v = y-1$

$u^2 + 3v^2 = 1$

等號兩邊微分。

$\dfrac{d}{dx}(u^2) + \dfrac{d}{dx}(3v^2) = \dfrac{d}{dx} 1$

$\dfrac{d}{du}(u^2)\dfrac{du}{dx} + \dfrac{d}{dv}(3v^2)\dfrac{dv}{dx} = 0$

$2u\dfrac{d}{dx}u + 6v\dfrac{d}{dx}v = 0$

還原$u, v$，得到

$2(x+2)\dfrac{d}{dx}(x+2) + 6(y-1)\dfrac{d}{dx}(y-1) = 0$

$2(x+2)(1) + 6(y-1)(\dfrac{d}{dx}y - \dfrac{d}{dx}(1)) = 0$

$2(x+2) + 6(y-1)(\dfrac{d}{dy} y \dfrac{dy}{dx}) = 0$

$2(x+2) + 6(y-1)(\dfrac{dy}{dx}) = 0$

$6(y-1)(\dfrac{dy}{dx}) = -2(x+2)$

$\dfrac{dy}{dx} = \dfrac{-2(x+2)}{6(y-1)} = -\dfrac{x+2}{3(y-1)}$



### Answer

$\dfrac{dy}{dx} = -\dfrac{x+2}{3(y-1)}$



## Exercise 7

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$\sin 2x - \cos 3y = 1$



### Solution

$\dfrac{d}{dx}(\sin 2x - \cos 3y) = \dfrac{d}{dx}(1)$

$\dfrac{d}{dx}\sin 2x - \dfrac{d}{dx}\cos 3y = 0$

令$u = 2x, v = 3y$

$\dfrac{d}{dx}\sin u - \dfrac{d}{dx}\cos v = 0$

$\dfrac{d}{du}\sin u\dfrac{du}{dx} - \dfrac{d}{dv}\cos v \dfrac{dv}{dx} = 0$

$\cos u \dfrac{d}{dx} u - (-\sin v)\dfrac{d}{dx} v = 0$

$\cos u \dfrac{d}{dx} u + \sin v\dfrac{d}{dx} v = 0$

還原$u, v$，得到

$\cos 2x \dfrac{d}{dx} 2x + \sin 3y\dfrac{d}{dx} 3y = 0$

$2\cos 2x + \sin 3y\dfrac{d}{dy} 3y\dfrac{dy}{dx} = 0$

$2\cos 2x + 3\sin 3y\dfrac{dy}{dx} = 0$

$\dfrac{dy}{dx} = -\dfrac{2\cos 2x}{3\sin 3y}$



### Answer

$\dfrac{dy}{dx} = -\dfrac{2\cos 2x}{3\sin 3y}$



## Exercise 8

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$(2x+3y)^8 = 1$



### Solution

令$u = 2x+3y$，則$u^8 = 1$

等號兩邊微分，得到

$\dfrac{d}{dx}u^8 = \dfrac{d}{dx}1$

$\dfrac{d}{du}u^8\dfrac{du}{dx} = \dfrac{d}{dx}1$

$8u^7\dfrac{d}{dx}u = 0$

還原$u$，得到

$8(2x+3y)^7\dfrac{d}{dx}(2x+3y) = 0$

$8(2x+3y)^7(\dfrac{d}{dx}(2x) + \dfrac{d}{dx}(3y)) = 0$

$8(2x+3y)^7(2 + \dfrac{d}{dx}(3y)) = 0$

$8(2x+3y)^7(2 + \dfrac{d}{dy}(3y)\dfrac{dy}{dx}) = 0$

$8(2x+3y)^7(2 + 3\dfrac{dy}{dx}) = 0$

$(2 + 3\dfrac{dy}{dx}) = 0$

$\dfrac{dy}{dx} = -\dfrac{2}{3}$



### Answer

$\dfrac{dy}{dx} = -\dfrac{2}{3}$



## Exercise 9

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$\tan(x^3+y^3) = xy$



### Solution

令$u = x^3+y^3$

$\tan(u) = xy$

等號兩邊微分

$\dfrac{d}{dx}(\tan u) = \dfrac{d}{dx}(xy)$

$\dfrac{d}{du}(\tan u) \dfrac{du}{dx} = \dfrac{d}{dx}(x)y + x\dfrac{d}{dx}(y)$

$\sec^2 u \dfrac{d}{dx} u = y + x\dfrac{d}{dy}y\dfrac{dy}{dx}$

$\sec^2 u \dfrac{d}{dx} u = y + x\dfrac{dy}{dx}$

還原$u$，得到

$\sec^2 (x^3+y^3) \dfrac{d}{dx} (x^3+y^3) = y + x\dfrac{dy}{dx}$

$\sec^2 (x^3+y^3) (\dfrac{d}{dx}x^3+\dfrac{d}{dx}y^3) = y + x\dfrac{dy}{dx}$

$\sec^2 (x^3+y^3) (3x^2+\dfrac{d}{dy}y^3\dfrac{dy}{dx}) = y + x\dfrac{dy}{dx}$

$\sec^2 (x^3+y^3) (3x^2+3y^2\dfrac{dy}{dx}) = y + x\dfrac{dy}{dx}$

$3x^2\sec^2(x^3+y^3) + 3y^2\sec^2(x^3+y^3)\dfrac{dy}{dx} = y + x\dfrac{dy}{dx}$

$3x^2\sec^2(x^3+y^3)-y = (x-3y^2\sec^2(x^3+y^3))\dfrac{dy}{dx}$

$\dfrac{dy}{dx} = \dfrac{3x^2\sec^2(x^3+y^3)-y}{x-3y^2\sec^2(x^3+y^3)}$



### Answer

$\dfrac{dy}{dx} = \dfrac{3x^2\sec^2(x^3+y^3)-y}{x-3y^2\sec^2(x^3+y^3)}$



## Exercise 10

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$y^2 = \sin(x+2y)$



### Solution

令$u = x+2y$，則$y^2 = \sin u$

等號兩邊微分，得

$\dfrac{d}{dx}y^2 = \dfrac{d}{dx}\sin u$

$\dfrac{d}{dy}y^2\dfrac{dy}{dx} = \dfrac{d}{du}\sin u\dfrac{du}{dx}$

$2y\dfrac{dy}{dx} = \cos u \dfrac{d}{dx} u$

還原$u$，得到$2y\dfrac{dy}{dx} = \cos (x+2y) \dfrac{d}{dx}(x+2y)$

$2y\dfrac{dy}{dx} = \cos(x+2y)(\dfrac{d}{dx}x + \dfrac{d}{dx}(2y))$

$2y\dfrac{dy}{dx} = \cos(x+2y)(1 + \dfrac{d}{dy}2y\dfrac{dy}{dx})$

$2y\dfrac{dy}{dx} = \cos(x+2y)(1+2\dfrac{dy}{dx})$

$2y\dfrac{dy}{dx} = \cos(x+2y) + 2\cos(x+2y)\dfrac{dy}{dx}$

$(2y-2\cos(x+2y))\dfrac{dy}{dx} = \cos(x+2y)$

$\dfrac{dy}{dx} = \dfrac{\cos(x+2y)}{2y-2\cos(x+2y)}$



### Answer

$\dfrac{dy}{dx} = \dfrac{\cos(x+2y)}{2y-2\cos(x+2y)}$