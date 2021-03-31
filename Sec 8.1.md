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
