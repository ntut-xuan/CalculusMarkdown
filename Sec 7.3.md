# 洪輝霖微積分Practice Ch 7-3

###### tags: `微積分題目紀錄`



## Problem 1

### Statement

求底下曲線的弧長。

$y = \ln(\sin x)$，$x \in [\dfrac{\pi}{4}, \dfrac{\pi}{2}]$



### Solution

$\dfrac{dy}{dx} = \dfrac{d}{dx}(\ln(\sin x)) = \dfrac{\cos(x)}{\sin (x)} = \cot(x)$

弧長$L = \displaystyle \int^a_b \sqrt{(\dfrac{dy}{dx})^2+1}dx = \displaystyle \int^\frac{\pi}{2}_\frac{\pi}{4} \sqrt{(\cot x)^2+1}dx = \int^\frac{\pi}{2}_\frac{\pi}{4} \csc x dx = -\ln(|\csc(x)+\cot(x)|) \bigg |^\frac{\pi}{2}_\frac{\pi}{4} = \ln(\sqrt{2}+1)$



### Answer

$\ln(\sqrt{2}+1)$



## Problem 2

### Statement

求底下曲線的弧長。

$y = \ln(\cos x)$，$x \in [0, \dfrac{\pi}{4}]$



### Solution

$\dfrac{dy}{dx} = \dfrac{d}{dx}(\ln(\cos x)) = -\tan x$

弧長$L = \displaystyle \int^a_b \sqrt{(\dfrac{dy}{dx})^2+1}dx = \int^\frac{\pi}{4}_0 \sqrt{(-\tan x)^2+1}dx = \int^\frac{\pi}{4}_0 \sec x dx = \ln(|\sec(x)+\tan(x)|)\bigg|^\frac{\pi}{4}_0 = \ln(|\sqrt{2}+1)$



### Answer

$\ln(\sqrt{2}+1)$



## Problem 3

### Statement

求底下曲線的弧長。

$y = \dfrac{x^3}{6} + \dfrac{1}{2x}$，$x \in [1, 2]$



## Problem 4

### Statement

求底下曲線的弧長。

$x = \dfrac{y^2}{2}-\dfrac{\ln(y)}{4}$，$y \in [1, 2]$



### Answer

$\dfrac{3}{2}+\dfrac{1}{4}\ln(2)$



## Problem 5

### Statement

求底下曲線的弧長。

$y = x^2$，$x \in [0, 1]$



### Answer

$\dfrac{\sqrt{5}}{2}+\dfrac{1}{4}\ln(\sqrt{5}+2)$



## Problem 6

### Statement

求底下曲線的弧長。

$y = \dfrac{2}{3}x^\frac{3}{2}+2$，$x \in [0, 1]$



### Answer

$\dfrac{2}{3}(2\sqrt{2}-1)$



## Problem 7

### Statement

求底下曲線的弧長。

$y = \dfrac{e^x+e^{-x}}{2}$，$x \in [0, 1]$



### Answer

$\dfrac{1}{2}(e-\dfrac{1}{e})$



## Problem 8

### Statement

求底下曲線的弧長。

$x = \dfrac{1}{4}y^2+1$，$y \in [0, 2]$



### Solution

$\dfrac{dx}{dy} = \dfrac{1}{2}y$

弧長$L = \displaystyle \int^2_0\sqrt{(\dfrac{1}{2}y)^2+1}dy = \int^2_0\sqrt{\dfrac{1}{4}y^2+1}dy = \dfrac{1}{2}\int^2_0 \sqrt{y^2+4}dy$

- 計算$\displaystyle \dfrac{1}{2} \int^2_0 \sqrt{y^2+4}dy$，令$y = 2\tan(u)$，則$dy = 2\sec^2(u)du$，$u = \arctan(\dfrac{y}{2})$

  因此$\displaystyle \dfrac{1}{2} \int^2_0 \sqrt{y^2+4}dy = \int^\frac{\pi}{4}_0 \sqrt{4\tan^2u + 4} \sec^2(u) du = 2\int^\frac{\pi}{4}_0 \sec^3(u)du$

- 計算$\displaystyle \int \sec^3(u)du$，令$v = \sec(u)$，$dt =\sec^2(u)du$

  則$dv = \tan(u)\sec(u)$，$t = \tan(u)$

  因此$\displaystyle \int \sec^3(u)du = \tan(u)\sec(u) - \int\tan^2(u)\sec(u)du$

  $\displaystyle = \tan(u)\sec(u) - \int(\sec^2(u)-1)\sec(u)du$

  $\displaystyle = \tan(u)\sec(u) - \int\sec^3(u)du + \int \sec(u)du$

  $\displaystyle = \tan(u)\sec(u) - \int\sec^3(u)du+\ln(|\sec(u)+\tan(u)|)$

  $\Longleftrightarrow \displaystyle 2\int\sec^3(u)du = \tan(u)\sec(u) + \ln(|\sec(u)+\tan(u)|)$

  $\Longleftrightarrow \displaystyle \int\sec^3(u)du = \dfrac{\tan(u)\sec(u) + \ln(|\sec(u)+\tan(u)|)}{2}$

- 故$2\displaystyle \int^\frac{\pi}{4}_0 \sec^3(u)du = \tan(u)\sec(u)+\ln(|\sec(u)+\tan(u)|)\bigg|^\frac{\pi}{4}_0$

  $= \sqrt{2} + \ln(\sqrt{2}+1)$

### Answer

$\sqrt{2} + \ln(\sqrt{2}+1)$



## Problem 9

### Statement

$y = e^x, x \in [0, 1]$



### Solution

$\dfrac{dy}{dx} = e^x$

因此$L = \displaystyle \int^1_0\sqrt{(e^x)^2+1}dx = \int^1_0 \sqrt{e^{2x}+1}dx$

令$u = \sqrt{e^{2x}+1}$，則$du = \dfrac{e^{2x}}{\sqrt{e^{2x}+1}}dx = \dfrac{u^2-1}{u}dx$

因此$dx = \dfrac{u}{u^2-1}du$

故$\displaystyle \int^1_0 \sqrt{e^{2x}+1}dx = \int^{\sqrt{e^2+1}}_{\sqrt{2}} \dfrac{u^2}{u^2-1}du = \int^\sqrt{e^2+1}_\sqrt{2} 1 + \dfrac{1}{u^2-1}du$

$= u + \dfrac{1}{2}\ln(|\dfrac{u-1}{u+1}|)\bigg|^\sqrt{e^2+1}_\sqrt{2} = \sqrt{e^2+1} - \sqrt{2} + \dfrac{1}{2}\ln(|\dfrac{\sqrt{e^2+1}-1}{\sqrt{e^2+1}+1}|) - \dfrac{1}{2}\ln(|\dfrac{\sqrt{2}-1}{\sqrt{2}+1}|)$

$= u + \dfrac{1}{2}\ln(|\dfrac{u-1}{u+1}|)\bigg|^\sqrt{e^2+1}_\sqrt{2} = \sqrt{e^2+1} - \sqrt{2} + \dfrac{1}{2}\ln(|\dfrac{\sqrt{e^2+1}-1}{\sqrt{e^2+1}+1}|)-\ln(|\sqrt{2}-1|)$



### Answer

$u + \dfrac{1}{2}\ln(|\dfrac{u-1}{u+1}|)\bigg|^\sqrt{e^2+1}_\sqrt{2} = \sqrt{e^2+1} - \sqrt{2} + \dfrac{1}{2}\ln(|\dfrac{\sqrt{e^2+1}-1}{\sqrt{e^2+1}+1}|)-\ln(|\sqrt{2}-1|)$



## Problem 10

### Statement

求底下曲線的弧長。

$y = \displaystyle \int^x_1 \sqrt{4t^2-1}dt$，$x \in [1, -2]$



### Answer

$3$



## Problem 11

### Statement

假設有隻老鼠正在原點上，另有一隻貓在老鼠的正東方1公尺處，此時老鼠以等速向北移動，而貓以老鼠的兩倍速度追趕老鼠，貓的追捕路線為$y = \dfrac{1}{3}(\sqrt{x^3}-3\sqrt{x}+2)$，求貓抓到老鼠時兩者所跑的路徑長度為何。



## Problem 12

### Statement

求曲線$y = x^3$，$x \in [0, 1]$繞$x$軸所得的旋轉體表面積。



## Problem 13

### Statement

求曲線$y = 2\sqrt{x}$，$x \in [0, 3]$繞$x$軸所得的旋轉體表面積。



## Problem 14

### Statement

求曲線$y = 3\sqrt{x-2}$，$x \in [2, 6]$繞$x$軸所得的旋轉體表面積。



## Problem 15

### Statement

求曲線$y = \dfrac{x^3}{6}+\dfrac{1}{2x}$，$x \in [1, 2]$繞$x$軸所得的旋轉體表面積。



## Problem 16

### Statement

求曲線$y=2\sqrt{1-x^2}$，$x \in [-1, 1]$繞$x$軸所得的旋轉體表面積。



## Problem 17

### Statement

求曲線$x=e^y$，$y \in [0, 1]$繞$y$軸所得的旋轉體表面積。



## Problem 18

### Statement

求曲線$x=\sqrt{2y-y^2}$，$y \in [\dfrac{1}{2}, \dfrac{3}{2}]$繞$y$軸所得的旋轉體表面積。



## Problem 19

### Statement

求曲線$x=\sqrt{y^2+1}$，$y \in [0, 1]$繞$y$軸所得的旋轉體表面積。



## Problem 20

### Statement

試證半徑為$r$的球體表面積為$4\pi r^2$。



## Problem 21

### Statement

求曲線$y = \dfrac{e^x+e^{-x}}{2}$，$x \in [0, 1]$繞$x$軸所得的旋轉體表面積。