# 洪輝霖微積分Practice Ch 8-1

###### tags: `微積分題目紀錄`



## Problem 1

### Statement

將下列方程式用參數式表示。

$x - 2y = 3$



### Solution

令$x = t$，則$t-2y=3$，$y = -\dfrac{3-t}{2}$

則可以得到兩個參數式，$\left\{\begin{array}\ x=t \\ y = -\dfrac{3-t}{2} \end{array}\right.$，$t \in \mathbb{R}$



### Answer

$\left\{\begin{array}\ x=t \\ y = -\dfrac{3-t}{2} \end{array}\right.$，$t \in \mathbb{R}$



## Problem 2

### Statement

將下列方程式用參數式表示。

$x^2+y^2 = 4$



### Solution

令$x = t$，則$t^2+y^2=4$，因此$y = \sqrt{4-t^2}$

則可以得到兩個參數式，$\left\{\begin{array}\ x = t \\ y=\sqrt{4-t^2} \end{array}\right.$，$t \in [-2, 2]$



### Answer

$\left\{\begin{array}\ x = t \\ y=\sqrt{4-t^2} \end{array}\right.$，$t \in [-2, 2]$



## Problem 3

### Statement

將下列方程式用參數式表示。

$y=x^2+1$



### Solution

令$x = t$，則$y = t^2+1$

則可以得到兩個參數式，$\left\{\begin{array}\ x=t \\ y=t^2+1\end{array}\right.$，$t \in \mathbb{R}$



### Answer

$\left\{\begin{array}\ x=t \\ y=t^2+1\end{array}\right.$，$t \in \mathbb{R}$



## Problem 4

### Statement

將下列方程式用參數式表示。

$\dfrac{x^2}{4}+\dfrac{y^2}{9} = 1$



### Solution

$\dfrac{x^2}{4}+\dfrac{y^2}{9} = 1$

$\Rightarrow 9x^2+4y^2=36$

令$x = t$，則$y = \sqrt{\dfrac{36-9t^2}{4}}$

則可以得到兩個參數式，$\left\{\begin{array}\ x=t \\ y=\sqrt{\dfrac{36-9t^2}{4}} \end{array}\right.$，$t \in [-2, 2]$

### Answer

$\left\{\begin{array}\ x=t \\ y=\sqrt{\dfrac{36-9t^2}{4}} \end{array}\right.$，$t \in [-2, 2]$



## Problem 5

### Statement

求下列參數曲線在給定之點的切線斜率。

$x=3t-t^3, y=t^2, t = 1$



### Solution

$\dfrac{dy}{dx} = \dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}} = \dfrac{2t}{3-3t^2}$

故$\dfrac{dy}{dx}|_{t=1} = \dfrac{2}{0} = D.N.E.$



### Answer

不存在



## Problem 6

### Statement

求下列參數曲線在給定之點的切線斜率。

$x=2t-1, y=t^2-3t, t=1$



### Solution

$\dfrac{dy}{dx} = \dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}} = \dfrac{2t-3}{2}$

故$\dfrac{dy}{dx}|_{t=1} = \dfrac{2-3}{2} = \dfrac{-1}{2}$



### Answer

$\dfrac{-1}{2}$



## Problem 7

### Statement

求下列參數曲線在給定之點的切線斜率。

$x=t^2+1, y=t^3-t, t = 2$



### Solution

$\dfrac{dy}{dx} = \dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}} = \dfrac{3t^2-1}{2t}$

故$\dfrac{dy}{dx}|_{t=2} = \dfrac{3\times4-1}{2\times 2} = \dfrac{11}{4}$



### Answer

$\dfrac{11}{4}$



## Problem 8

### Statement

求下列參數曲線在給定之點的切線斜率。

$x=2\cos 2t, y=3\sin 2t, t = -1$



### Solution

$\dfrac{dy}{dx} = \dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}} = \dfrac{6\cos2t}{-4\sin2t} = \dfrac{3}{-2}\cot(2t)$

則$\dfrac{dy}{dx}|_{t=-1} = -\dfrac{3}{2}\cot(-2) = \dfrac{3}{2}\cot(2)$



### Answer

$\dfrac{3}{2}\cot(2)$



## Problem 9

### Statement

求下列參數曲線在給定之點的切線斜率。

$x=e^{2t}, y = (1+\sin3t)^2, t = 0$



### Solution

$\dfrac{dy}{dx} = \dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}} = \dfrac{2(1+\sin 3t)(3\cos 3t)}{2e^{2t}}$

則$\dfrac{dy}{dx}|_{t=0} = \dfrac{2\times1\times3}{2e^0} = \dfrac{6}{2} = 3$



### Answer

$3$



## Problem 10

### Statement

若參數式為$x=t^2+1$，$y=t^3-t$，求$\dfrac{d^2y}{dx^2}$與曲線在$t \in (0, 1)$時的凹性(上凹或下凹)



### Solution

$\dfrac{d^2y}{dx^2} = \dfrac{d}{dx}(\dfrac{dy}{dx}) = \dfrac{\dfrac{d}{dt}\dfrac{dy}{dx}}{\dfrac{dx}{dt}} = \dfrac{\dfrac{d}{dt}\dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}}}{\dfrac{dx}{dt}} = \dfrac{\dfrac{d}{dt}(\dfrac{3t^2-1}{2t})}{2t} = \dfrac{2t(6t)-(3t^2-1)2}{8t^3} = \dfrac{12t^2-6t^2+2}{8t^3} = \dfrac{6t^2+2}{8t^3} = \dfrac{3t^2+1}{4t^3}$

$\dfrac{d^2y}{dx^2}|_{t=\frac{1}{2}} = \dfrac{\dfrac{3}{4}+1}{\dfrac{4}{8}} = \dfrac{7}{2} > 0$，故上凹。



### Answer

$\dfrac{3t^2+1}{4t^3}$，上凹。



## Problem 11

### Statement

若參數式為$x=t-e^t$，$y=t+e^{-t}$，求$\dfrac{d^2y}{dx^2}$與曲線在$t \in (0, 1)$時的凹性(上凹或下凹)



### Solution

$\dfrac{d^2y}{dx^2} = \dfrac{d}{dx}(\dfrac{dy}{dx}) = \dfrac{\dfrac{d}{dt}\dfrac{dy}{dx}}{\dfrac{dx}{dt}} = \dfrac{\dfrac{d}{dt}\dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}}}{\dfrac{dx}{dt}} = \dfrac{d}{dt}(\dfrac{1-e^{-t}}{1-e^t}) \div (1-e^t) = \dfrac{(1-e^t)(e^{-t})-(1-e^{-t})(-e^t)}{(1-e^t)^3}$

$= \dfrac{e^{-t}-1 + e^t-1}{(1-e^t)^3} = \dfrac{e^t+e^{-t}-2}{(1-e^t)^3}$



令$\dfrac{e^t+e^{-t}-2}{(1-e^t)^3} = 0$，則$t \in \emptyset$，故若任意的$t$屬於函數定義域帶入式子中，即可知道函數是上凹或者下凹。

則令$t = \ln(2)$，得到$\dfrac{2+\dfrac{1}{2}-2}{(1-2)^3} < 0$，故圖形下凹。



### Answer

$\dfrac{e^t+e^{-t}-2}{(1-e^t)^3}$，下凹



## Problem 12

### Statement

已知曲線$C$的參數式為$x=t^2$，$y=t^3-3t$，求

1. 曲線在點$(3, 0)$的切線方程式
2. 曲線$C$在哪些點有水平切線
3. 曲線$C$在哪些點有垂直切線



### Solution

$\dfrac{dy}{dx} = \dfrac{\dfrac{dy}{dt}}{\dfrac{dx}{dt}} = \dfrac{3t^2-3}{2t}$，則曲線在$(3, 0)$，可知$t = \pm\sqrt{3}$

$\dfrac{dy}{dx}|_{t = \sqrt{3}} = \dfrac{6}{2\sqrt{3}} = \sqrt{3}$，故斜率為$m = \sqrt{3}$

$\dfrac{dy}{dx}|_{t = -\sqrt{3}} = -\dfrac{6}{2\sqrt{3}} = -\sqrt{3}$，故斜率為$m = -\sqrt{3}$

則切線方程式為$y = \sqrt{3}(x-3)$或者$y = -\sqrt{3}(x-3)$

找水平切線，令$3t^2-3 = 0$，故$t = \pm 1$，帶入式子可得水平切線發生的點有$(1, 2)$或者$(1, -2)$。

找垂直切線，令$2t = 0$，故$t = 0$，可知垂直切線發生在$(0, 0)$上。



### Answer

1. $3x+\sqrt{3}y=9$和$3x-\sqrt{3}y=9$
2. $(1, -2)$和$(1, 2)$
3. $(0, 0)$



## Problem 13

### Statement

已知曲線$C$的參數式為$x=t^3-3t$，$y=3t^2-9$，求曲線$C$在哪些點有水平切線和垂直切線？



### Solution

先求$\dfrac{dy}{dx}$，得到$\dfrac{dy}{dx} = \dfrac{6t}{3t^2-3}$

求水平切線時，先令$\dfrac{dy}{dx} = 0$，因此得到$t = 0$，水平切線發生在$(x, y) = (0, -9)$

求垂直切線時，先令$\dfrac{dy}{dx}=D.N.E.$，因此得到$3t^2-3=0$，得到$t = \pm 1$

故垂直切線發生在$(x, y) = (-2,-6)$與$(x, y) = (2, -6)$



### Answer

水平切線發生在$(x, y) = (0, -9)$

垂直切線發生在$(x, y) = (2, -6)$與$(x, y) = (-2, -6)$



## Problem 14

### Statement

已知曲線$C$的參數式為$x=2-t^2$，$y=t^3-12t$，求曲線$C$在哪些點有水平切線和垂直切線？



### Solution

先求$\dfrac{dy}{dx}$，得到$\dfrac{dy}{dx} = \dfrac{3t^2-12}{2-2t}$

求水平切線時，令$\dfrac{dy}{dx} = 0$，故$3t^2-12 = 0$，得到$t = \pm 2$

故水平切線發生在$(x, y) = (-2, 16)$與$(x, y) = (-2, -16)$

求垂直切線時，令$\dfrac{dy}{dx} = D.N.E.$，因此$2-2t=  0$，得到$t = 1$

故垂直切線發生在$(x, y) = (1, -11)$



### Answer

水平切線發生在$(x, y) = (-2, 16)$與$(x, y) = (-2, -16)$

垂直切線發生在$(x, y) = (1, -11)$



## Problem 15

### Statement

已知曲線$C$的參數式為$x=\cos t$，$y=\sin t \cos t$，求曲線在點$(0, 0)$的切線方程式。



### Solution

求$\dfrac{dy}{dx}$，得到$\dfrac{dy}{dx} = \dfrac{\cos2t}{-\sin t} = -\dfrac{\cos2t}{\sin t}$

發生在點$(0, 0)$，因此$t = \dfrac{\pi}{2}, t = \dfrac{3\pi}{2}$



帶入$\dfrac{dy}{dx}$得到$-\dfrac{\cos(\pi)}{\sin \dfrac{\pi}{2}} = 1, \dfrac{-\cos(3\pi)}{\sin(\dfrac{3\pi}{2})} = -1$

故有兩條切線$x+y=0$，$x-y=0$。



### Answer

$x+y=0$，$x-y=0$



## Problem 16

### Statement

已知擺線的參數式為$x = 3(\theta - \sin \theta)$，$y = 3(1 - \cos \theta)$，求擺線一個擺幅底下和$x$軸所包圍的區域面積。



### Solution

求一個函數的面積：$\displaystyle \int^a_b y dx$

所求$dx = 3(1 - \cos(\theta))d\theta$，擺線一個擺幅即為從$0$至$2\pi$

故積分$\displaystyle \int^{2\pi}_{0} 3(1-\cos\theta)3(1 - \cos\theta)d\theta = 9\int^{2\pi}_0 1-2\cos(\theta)+\cos^2(\theta)d\theta$

$= \displaystyle 9(\theta - 2\sin(\theta) + \dfrac{2\theta+\sin(2\theta)}{4})\bigg|^{2\pi}_0 = 27\pi$



### Answer

$27\pi$



## Problem 17

### Statement

已知橢圓的參數式為$x = 2\cos(\theta)$，$y = 3\sin(\theta)$，求橢圓面積。



### Solution

令$y = 0$，則$\theta = 0, \theta =  \pi$，也就是$x = 2, x = -2$

因此我們考慮從$0$積到$\pi$，$dx = -2\sin(\theta)d\theta$

可得$\displaystyle \int^\pi_0 3\sin(\theta) (-2\sin\theta) d\theta = -6\int^\pi_0 \sin^2\theta d\theta = -3\pi = 3\pi$ (x軸下面積)。

由於橢圓對稱於$x$軸，故我們將下面積乘以2，得到橢圓面積$6\pi$



### Answer

$6\pi$

