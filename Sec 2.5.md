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



## Exercise 11

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$\dfrac{x^2}{y^2+1} = 3x+2$



### Solution

等號兩邊微分

$\dfrac{d}{dx}(\dfrac{x^2}{y^2+1}) = \dfrac{d}{dx}(3x+2)$

$\dfrac{(y^2+1)\dfrac{d}{dx}(x^2) - x^2\dfrac{d}{dx}(y^2+1)}{(y^2+1)^2} = 3$

$\dfrac{2x(y^2+1) - x^2\dfrac{d}{dy}(y^2+1)\dfrac{dy}{dx}}{(y^2+1)^2} = 3$

$\dfrac{2x(y^2+1) - 2x^2y\dfrac{dy}{dx}}{(y^2+1)^2} = 3$

$2x(y^2+1) - 2x^2y \dfrac{dy}{dx} = 3(y^2+1)^2$

$-2x^2y\dfrac{dy}{dx} = 3(y^2+1)^2-2x(y^2+1)$

$\dfrac{dy}{dx} = -\dfrac{3(y^2+1)^2-2x(y^2+1)}{2x^2y}$



### Answer

$\dfrac{dy}{dx} = -\dfrac{3(y^2+1)^2-2x(y^2+1)}{2x^2y}$



## Exercise 12

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$2x + \cos^2 y = 1$



### Solution

等號兩邊微分，得到$\dfrac{d}{dx}(2x+\cos^2y) = \dfrac{d}{dx}(1)$

$\dfrac{d}{dx}(2x) + \dfrac{d}{dx}(\cos^2y) = 0$

$2 + \dfrac{d}{dx}(\cos^2 y) = 0$

令$u = \cos y$，則$2 + \dfrac{d}{dx} u^2 = 0$

$2 + \dfrac{d}{du} u^2 \dfrac{du}{dx} = 0$

$2 + 2u\dfrac{d}{dx}u = 0$

還原$u$，得到$2+2\cos y \dfrac{d}{dx} \cos y = 0$

$2 + 2\cos y \dfrac{d}{dy} \cos y \dfrac{dy}{dx} = 0$

$2 + 2\cos y (-\sin y) \dfrac{dy}{dx} = 0$

化簡

$2 - 2\cos y\sin y \dfrac{dy}{dx} = 0$

$\dfrac{dy}{dx} = \dfrac{1}{\cos y\sin y}$



### Answer

$\dfrac{dy}{dx} = \dfrac{1}{\cos y\sin y}$



## Exercise 13

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$\sin(x^2y) = 3x-2y$



### Solution

令$u = x^2y$，則$\sin(u) = 3x-2y$

等號兩邊微分

$\dfrac{d}{dx}\sin(u) = \dfrac{d}{dx}(3x-2y)$

$\dfrac{d}{dx}\sin(u) =\dfrac{d}{dx}(3x) - \dfrac{d}{dx}(2y)$

$\dfrac{d}{du}\sin(u)\dfrac{du}{dx} = \dfrac{d}{dx}(3x) - \dfrac{d}{dx}(2y)$

$\cos(u)\dfrac{d}{dx}u = \dfrac{d}{dx}(3x) - \dfrac{d}{dx}(2y)$

還原$u$，得到

$\cos(x^2y) \cdot \dfrac{d}{dx}(x^2y) = \dfrac{d}{dx}(3x) - \dfrac{d}{dx}(2y)$

$\cos(x^2y) \cdot (\dfrac{d}{dx}(x^2)y + (x^2)\dfrac{d}{dx}(y)) = \dfrac{d}{dx}(3x) - \dfrac{d}{dx}(2y)$

$\cos(x^2y) \cdot (2xy + (x^2)\dfrac{d}{dx}(y)) = 3 - \dfrac{d}{dx}(2y)$

$\cos(x^2y) \cdot (2xy + (x^2)\dfrac{d}{dy}(y)\dfrac{dy}{dx}) = 3 - \dfrac{d}{dy}(2y)\dfrac{dy}{dx}$

$\cos(x^2y) \cdot (2xy + x^2\dfrac{dy}{dx}) = 3 - 2\dfrac{dy}{dx}$

$2xy\cos(x^2y) + x^2\cos(x^2y)\dfrac{dy}{dx} = 3 - 2\dfrac{dy}{dx}$

$(x^2\cos(x^2y)+2)\dfrac{dy}{dx} = 3-2xy\cos(x^2y)$

$\dfrac{dy}{dx} = \dfrac{3-2xy\cos(x^2y)}{x^2\cos(x^2y)+2}$



## Exercise 14

### Statement

利用隱函數微分法求$\dfrac{dy}{dx}$。

$x+y^2= \cot(xy)$



### Solution

等號左右兩邊微分

$\dfrac{d}{dx}(x + y^2) = \dfrac{d}{dx}(\cot(xy))$

$\dfrac{d}{dx}(x) + \dfrac{d}{dx}(y^2) = \dfrac{d}{dx}\cot(xy)$

令$u = xy$，則$\dfrac{d}{dx}(x) + \dfrac{d}{dy}(y^2)\dfrac{dy}{dx} = \dfrac{d}{du}\cot(u)\dfrac{du}{dx}$

$1 + 2y\dfrac{dy}{dx} = \tan u \sec u \dfrac{d}{dx}u$

還原$u$，得到$1+2y\dfrac{dy}{dx} = -\csc(xy) \dfrac{d}{dx}(xy)$

$1+2y\dfrac{dy}{dx} = -\csc(xy) (\dfrac{d}{dx}(x)y + x\dfrac{d}{dx}(y))$

$1+2y\dfrac{dy}{dx} = -\csc(xy) (y + x\dfrac{d}{dy}(y)\dfrac{dy}{dx})$

$1+2y\dfrac{dy}{dx} = -\csc(xy) (y + x\dfrac{dy}{dx})$

$1+2y\dfrac{dy}{dx} = -y\csc(xy) - x\csc(xy)\dfrac{dy}{dx}$

$(2y+x\csc(xy))\dfrac{dy}{dx} = -y\csc(xy)-1$

$\dfrac{dy}{dx} = \dfrac{-y\csc(xy)-1}{2y+x\csc(xy)}$



## Exercise 15

### Statement

利用隱函數微分法，求曲線在給定點之切線方程式。

$x+9y^2=9$，$(0, -1)$



### Solution

等式兩邊微分

$\dfrac{d}{dx}(x+9y^2) = \dfrac{d}{dx}(9)$



$\dfrac{d}{dx}x + \dfrac{d}{dx}(9y^2) = 0$

$1 + \dfrac{d}{dy}9y^2\dfrac{dy}{dx} = 0$

$1 + 18y\dfrac{dy}{dx} = 0$

$\dfrac{dy}{dx} = \dfrac{-1}{18y}$



由函數微分該點後可以得到切線斜率。

因此套入$(0, -1)$

$\dfrac{dy}{dx} = \dfrac{-1}{-18} = \dfrac{1}{18} = m$

造出直線方程式

$y + 1 = \dfrac{1}{18}x$

$18y-x+18=0$

$x-18y-18=0$



### Answer

$x-18y-18=0$



## Exercise 16

### Statement

利用隱函數微分法，求曲線在給定點之切線方程式。

$x^2y + y^3 = -2$，$(1, -1)$



### Answer

$\dfrac{d}{dx}(x^2y+y^3) = \dfrac{d}{dx}(-2)$，$(1, -1)$

$\dfrac{d}{dx}(x^2y) + \dfrac{d}{dx}(y^3) = 0$

$\dfrac{d}{dx}(x^2)y + x^2\dfrac{d}{dx}(y) + \dfrac{d}{dy}(y^3)\dfrac{dy}{dx} = 0$

$2xy + x^2\dfrac{d}{dy}(y)\dfrac{dy}{dx} + \dfrac{d}{dy}(y^3)\dfrac{dy}{dx} = 0$

$2xy + x^2\dfrac{dy}{dx} + 3y^2\dfrac{dy}{dx} = 0$

$(x^2+3y^2)\dfrac{dy}{dx} = -2xy$

$\dfrac{dy}{dx} = \dfrac{-2xy}{x^2+3y^2}$



由函數微分該點後可以得到切線斜率。

因此套入$(1, -1)$

$\dfrac{dy}{dx} = \dfrac{-2(1)(-1)}{(1)^2+3(-1)^2} = \dfrac{2}{4} = \dfrac{1}{2} = m$

造出直線方程式

$y - (-1) = \dfrac{1}{2}(x-1)$

$y + 1 = \dfrac{1}{2}(x-1)$

$2y+2=x-1$

$x-2y-3=0$



### Answer

$x-2y-3=0$



## Exercise 17

### Statement

利用隱函數微分法，求曲線在給定點之切線方程式。

$y = \pi + \sin(xy)$，$(1, \pi)$



### Solution

微分等號左右兩邊

$\dfrac{d}{dx}(y) = \dfrac{d}{dx}(\pi + \sin(xy))$

$\dfrac{dy}{dx} = \dfrac{d}{dx}(\pi) + \dfrac{d}{dx}(\sin(xy))$

$\dfrac{dy}{dx} = \dfrac{d}{dx}(\sin(xy))$

令$u = xy$，則$\dfrac{dy}{dx} = \dfrac{d}{dx}(\sin(u)) = \dfrac{d}{du}\sin u\dfrac{du}{dx} = \cos u \dfrac{d}{dx} u$

還原$u$，得到$\dfrac{dy}{dx} = \cos(xy) \dfrac{d}{dx}(xy) = \cos(xy)(\dfrac{d}{dx}(x)y + x\dfrac{d}{dx}(y)) =\cos(xy)(y + x\dfrac{dy}{dx})$

$\dfrac{dy}{dx} = \cos(xy)(y + x\dfrac{dy}{dx})$

$\dfrac{dy}{dx} = y\cos(xy) + x\cos(xy)\dfrac{dy}{dx}$

$(1-x\cos(xy))\dfrac{dy}{dx} = y\cos(xy)$

$\dfrac{dy}{dx} = \dfrac{y\cos(xy)}{1-x\cos(xy)}$



帶入$(1, \pi)$，得到$m = \dfrac{\pi\cos(\pi)}{1-1\cos(\pi)} = -\dfrac{\pi}{2}$

造出直線方程式，$y-\pi = -\dfrac{\pi}{2}(x-1)$

$2y-2\pi = -\pi(x-1)$

$2y+\pi x-2\pi-\pi = 0$

$2y + \pi x - 3\pi = 0$



### Answer

$2y + \pi x - 3\pi = 0$



## Exercise 18

### Statement

利用隱函數微分法，求曲線在給定點之切線方程式。

$\sin 2x - \cos 3y = 1$，$(\dfrac{\pi}{4}, \dfrac{\pi}{2})$



### Solution

微分等號左右兩邊

$\dfrac{d}{dx}(\sin 2x - \cos 3y) = \dfrac{d}{dx}(1)$

$\dfrac{d}{dx}\sin 2x - \dfrac{d}{dx}\cos 3y = 0$

令$u = 2x, v = 3y$，則$\dfrac{d}{dx}\sin u - \dfrac{d}{dx} \cos v = 0$

$\dfrac{d}{du} \sin u \dfrac{du}{dx} - \dfrac{d}{dv} \cos v \dfrac{dv}{dx} = 0$

$\cos u\dfrac{d}{dx}u - (-\sin v)\dfrac{d}{dx} v = 0$

$\cos u\dfrac{d}{dx}u + \sin v\dfrac{d}{dx} v = 0$

還原$u,v$，得到

$\cos(2x)\dfrac{d}{dx}(2x) + \sin(3y)\dfrac{d}{dx}(3y) = 0$

$2\cos(2x) + \sin(3y)\dfrac{d}{dy}(3y)\dfrac{dy}{dx} = 0$

$2\cos(2x) + 3\sin(3y) \dfrac{dy}{dx}  = 0$

$3\sin(3y)\dfrac{dy}{dx} = -2\cos(2x)$

$\dfrac{dy}{dx} = \dfrac{-2\cos(2x)}{3\sin(3y)}$



帶入$(\dfrac{\pi}{4}, \dfrac{\pi}{2})$，得到

$m = \dfrac{-2\cos(\dfrac{\pi}{2})}{3\sin(\dfrac{3\pi}{2})} = \dfrac{0}{-3} = 0$

造出直線方程式

$y = \dfrac{\pi}{2}$



### Answer

$y = \dfrac{\pi}{2}$



## Exercise 19

### Statement

求$\dfrac{d^2y}{dx^2}$

$x^2+2y^2=3$



### Answer

先求$\dfrac{dy}{dx}$

$\dfrac{d}{dx}(x^2+2y^2) = \dfrac{d}{dx}(3)$

$\dfrac{d}{dx}(x^2) + \dfrac{d}{dx}(2y^2) = 0$

$2x + \dfrac{d}{dy}(2y^2)\dfrac{dy}{dx} = 0$

$2x + 4y\dfrac{dy}{dx} = 0$

$\dfrac{dy}{dx} = \dfrac{-2x}{4y} = -\dfrac{x}{2y}$



再求$\dfrac{d^2x}{dx^2}$

$\dfrac{d^2x}{dx^2} = \dfrac{d}{dx}(-\dfrac{x}{2y})$

$= -\dfrac{2y\dfrac{d}{dx}(x) - x\dfrac{d}{dx}(2y)}{(2y)^2}$

$= -\dfrac{2y - x\dfrac{d}{dx}(2y)}{4y^2}$

$= -\dfrac{2y-x\dfrac{d}{dy}(2y)\dfrac{dy}{dx}}{4y^2}$

$= -\dfrac{2y-2\dfrac{dy}{dx}}{4y^2}$

帶入$\dfrac{dy}{dx}$，得到$\dfrac{d^2x}{dx^2} = - \dfrac{2y-2\dfrac{-x}{2y}}{4y^2}$

$= -\dfrac{2y-\dfrac{-x}{y}}{4y^2}$

$= \dfrac{2y+\dfrac{x}{y}}{4y^2}$

$= \dfrac{\dfrac{2y^2}{y}+\dfrac{x}{y}}{4y^2}$

$= \dfrac{2y^2+x}{4y^3}$

題目給定$2y^2+x=3$，因此

$\dfrac{d^2x}{dx^2} = \dfrac{3}{4y^3}$



### Answer

$\dfrac{d^2x}{dx^2} = \dfrac{3}{4y^3}$



## Exercise 20

### Statement

求$\dfrac{d^2y}{dx^2}$

$\sin x + \cos y = 1$



### Answer

求$\dfrac{dy}{dx}$

$\dfrac{d}{dx}(\sin x + \cos y) = \dfrac{d}{dx}(1)$

$\dfrac{d}{dx}\sin x + \dfrac{d}{dx}\cos y = 0$

$\cos x + \dfrac{d}{dy}\cos y \dfrac{dy}{dx} = 0$

$(-\sin y)\dfrac{dy}{dx} = -\cos x$

$\dfrac{dy}{dx} = \dfrac{\cos x}{\sin y}$



求$\dfrac{d^2y}{dx^2}$

$\dfrac{d}{dx}(\dfrac{\cos x}{\sin y})$

$= \dfrac{(\sin y)\dfrac{d}{dx}(\cos x) - (\cos x)\dfrac{d}{dx}(\sin y)}{\sin^2 y}$

$= \dfrac{(\sin y)(-\sin x) - (\cos x)\dfrac{d}{dy}(\sin y)\dfrac{dy}{dx}}{\sin^2 y}$

$= \dfrac{-\sin x\sin y - (\cos x)(\cos y)\dfrac{dy}{dx}}{\sin^2 y}$

帶入$\dfrac{dy}{dx}$，得到

$\dfrac{d}{dx}(\dfrac{\cos x}{\sin y}) = \dfrac{-\sin x\sin y - \cos x\cos y\dfrac{\cos x}{\sin y}}{\sin^2 y}$

$= \dfrac{-\sin x\sin y - \dfrac{\cos^2 x\cos y}{\sin y}}{\sin^2 y}$

$= \dfrac{\dfrac{-\sin x\sin y\sin y}{\sin y} - \dfrac{\cos^2 x\cos y}{\sin y}}{\sin^2 y}$

$= \dfrac{{-\sin x\sin^2 y} - {\cos^2 x\cos y}}{\sin^3 y}$

$= -\dfrac{{\sin x\sin^2 y} + {\cos^2 x\cos y}}{\sin^3 y}$

### Answer

$\dfrac{d^2y}{dx^2} = -\dfrac{{\sin x\sin^2 y} + {\cos^2 x\cos y}}{\sin^3 y}$

​	

## Exercise 21

### Statement

求$\dfrac{d^2y}{dx^2}$

$x^3-y^3 = 8$



### Solution

先求$\dfrac{dy}{dx}$

$\dfrac{d}{dx}(x^3) - \dfrac{d}{dx}(y^3) = \dfrac{d}{dx}(8)$

$3x^2 - \dfrac{d}{dy}(y^3)\dfrac{dy}{dx} = 0$

$3x^2 - 3y^2\dfrac{dy}{dx} = 0$

$\dfrac{dy}{dx} = \dfrac{-3x^2}{-3y^2} = \dfrac{x^2}{y^2}$



求$\dfrac{d^2y}{dx^2}$

$\dfrac{d^2y}{dx^2} = \dfrac{d}{dx}(\dfrac{x^2}{y^2}) = \dfrac{(y^2)\dfrac{d}{dx}(x^2) - (x^2)\dfrac{d}{dx}(y^2))}{y^4}$

$= \dfrac{2xy^2 - (x^2)\dfrac{d}{dy}(y^2)\dfrac{dy}{dx}}{y^4}$

帶入$\dfrac{dy}{dx}$

$\dfrac{d^2y}{dx^2} = \dfrac{2xy^2 - 2x^2y \dfrac{dy}{dx}}{y^4}$

$= \dfrac{2xy^2 - 2x^2y\dfrac{x^2}{y^2}}{y^4}$

$= \dfrac{2xy^2 - \dfrac{2x^4}{y}}{y^4}$

$= \dfrac{\dfrac{2xy^3}{y} - \dfrac{2x^4}{y}}{y^4}$

$= \dfrac{2xy^3-2x^4}{y^5}$

$= \dfrac{2x(y^3-x^3)}{y^5}$

又因$x^3-y^3=8$，因此$y^3-x^3=-8$

所以$\dfrac{d^2y}{dx^2} = \dfrac{2x(-8)}{y^5} = \dfrac{-16x}{y^5}$

### Answer

$\dfrac{d^2y}{dx^2} = \dfrac{-16x}{y^5}$