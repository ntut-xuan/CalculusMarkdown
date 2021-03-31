# 洪輝霖微積分Practice Ch 7-1

###### tags: `微積分題目紀錄`



## Problem 24

### Statement

求在圖形$y = \dfrac{1}{x^2+4}$底下，$x$軸上方的區域面積。



### Solution

$y = \dfrac{1}{x^2+4}$每點均恆正，考慮$\displaystyle \int^\infty_{-\infty} \dfrac{1}{x^2+4}dx$

$\displaystyle \int^\infty_{-\infty} \dfrac{1}{x^2+4}dx = \lim_{a\rightarrow \infty}\lim_{b\rightarrow -\infty} \int^a_b \dfrac{1}{x^2+4}dx = \lim_{a\rightarrow \infty}\lim_{b\rightarrow -\infty}\dfrac{1}{2}\tan^{-1}(\dfrac{x}{2})\bigg|^a_b = \dfrac{1}{2}(\dfrac{\pi}{4} - \dfrac{-\pi}{4}) = \dfrac{\pi}{2}$ 



### Answer

$\dfrac{\pi}{2}$



## Problem 25

### Statement

求介於圖形$y=xe^{-x^2}$與$x$軸之間的區域面積，如下圖。

![image-20210331194345883](https://i.imgur.com/1zWdGgP.png)

### Solution

考慮負無限大積到0，與從0積到無限大。

$\displaystyle \int^0_{-\infty} 0 - xe^{-x^2}dx + \int^\infty_0 xe^{-x^2} - 0dx = -\int^0_{-\infty} xe^{-x^2}dx + \int^\infty_0 xe^{-x^2}dx$

計算定積分$\displaystyle -\int^0_{-\infty}xe^{-x^2}dx$

令$u = -x^2$，則$du = -2xdx$，因此$dx = \dfrac{du}{-2x}$

$\displaystyle -\int^0_{-\infty}xe^{-x^2}dx = -\lim_{a\rightarrow -\infty} \int^0_{a}xe^{-x^2}dx =  -\lim_{a\rightarrow -\infty}\int^0_axe^{u}\dfrac{du}{-2x} = \dfrac{1}{2}\lim_{a\rightarrow-\infty}\int^0_ae^udu = \dfrac{1}{2}\lim_{a\rightarrow-\infty}e^u\bigg|^0_a = \dfrac{1}{2}(1 - 0) = \dfrac{1}{2}$



計算定積分$\displaystyle \int^\infty_0 xe^{-x^2}dx$

令$u = -x^2$，則$du = -2xdx$，因此$dx = \dfrac{du}{-2x}$

$\displaystyle \int^\infty_0 xe^{-x^2}dx = \lim_{a\rightarrow \infty} \int^{-a^2}_0 xe^u\dfrac{du}{-2x} = -\dfrac{1}{2}\lim_{a\rightarrow \infty}\int^{-a^2}_0e^udu = -\dfrac{1}{2}(\lim_{a\rightarrow \infty}e^{-a^2} - 1) = -\dfrac{1}{2}(0-1) = \dfrac{1}{2}$



因此$\displaystyle -\int^0_{-\infty} xe^{-x^2}dx + \int^\infty_0 xe^{-x^2}dx = \dfrac{1}{2} + \dfrac{1}{2} = 1$



### Answer

$1$



## Problem 26

### Statement

求圖形$y=\sqrt{1-x^2}$與$x$軸所包圍的面積。



### Solution

令$y = 0$，可知$x = \pm 1$時與$y=0$有交點。

帶入$x = 0$，可知當$x \in [-1, 1]$時，$y = \sqrt{1-x^2}$在$y=0$上方。



因此，我們積分$\displaystyle \int^1_{-1} \sqrt{1-x^2}dx$

令$x = \sin(u)$，則$dx = \cos(u)du$，$u = \arcsin(x)$

$\displaystyle \int^1_{-1} \sqrt{1-x^2} dx = \int^\frac{\pi}{2}_{\frac{-\pi}{2}} \sqrt{1-\sin(u)^2}\cos(u)du = \int^\frac{\pi}{2}_{\frac{-\pi}{2}} \cos^2(u)du = \int^\frac{\pi}{2}_{\frac{-\pi}{2}} \dfrac{1+\cos(2u)}{2}du = (\dfrac{u}{2} + \dfrac{\sin(2u)}{4})|^\frac{\pi}{2}_\frac{-\pi}{2}$ 

$= (\dfrac{\pi}{4} + 0) - (-\dfrac{\pi}{4}+0) = \dfrac{\pi}{2}$



### Answer

$\dfrac{\pi}{2}$



## Problem 27

### Statement

求介於圖形$y = \dfrac{1}{x^2+3x+2}$、$y=0$與$x \ge 0$之間的區域面積，如下圖。

<img src="https://i.imgur.com/o9sHiXv.png" alt="image-20210331173340865" style="zoom:67%;" />

### Solution

考慮從$0$積到趨近於無限大。

$\displaystyle \int^\infty_0 \dfrac{1}{x^2+3x+2} dx = \lim_{a\rightarrow \infty} \int^a_0 \dfrac{1}{x^2+3x+2}dx = \lim_{a\rightarrow \infty} \int^a_0 \dfrac{1}{x^2+3x+\dfrac{9}{4}-\dfrac{9}{4}+2}dx = \lim_{a\rightarrow \infty} \int^a_0 \dfrac{1}{(x+\dfrac{3}{2})^2-\dfrac{1}{4}}dx$

令$u = x + \dfrac{3}{2}$，則$du = dx$

$\displaystyle \lim_{a\rightarrow \infty} \int^a_0 \dfrac{1}{(x+\dfrac{3}{2})^2-\dfrac{1}{4}}dx = \lim_{a\rightarrow \infty}\int^a_\frac{3}{2} \dfrac{1}{u^2-\dfrac{1}{4}}du = \lim_{a\rightarrow \infty} \int^a_\frac{3}{2} \dfrac{A}{u-\dfrac{1}{2}} + \dfrac{B}{u+\dfrac{1}{2}}du$

算出$A$與$B$，得到$A = 1, B = -1$

$\displaystyle \lim_{a\rightarrow \infty} \int^a_\frac{3}{2} \dfrac{1}{u-\dfrac{1}{2}} - \dfrac{1}{u+\dfrac{1}{2}}du = \left.\lim_{a\rightarrow \infty} [\ln(|u-\dfrac{1}{2}|) - \ln(|u+\dfrac{1}{2}|)]\right\vert^a_\frac{3}{2} = \lim_{a \rightarrow \infty}\ln(|\dfrac{a-\dfrac{1}{2}}{a+\dfrac{1}{2}}|) -(-\ln(2)) = 0 + \ln(|2|) = \ln(2)$



### Answer

$\ln(2)$



## Problem 28

### Statement

求介於圖形$y = xe^{-|x|}$與$x$軸之間的區域面積。

<img src="https://i.imgur.com/39Z5i2E.png" alt="image-20210331174338944" style="zoom:67%;" />



### Solution

考慮負無限大積到0，與從0積到無限大。

$\displaystyle \int^0_{-\infty} 0-xe^{x}dx + \int^\infty_0 xe^{x}-0dx = \displaystyle \int^0_{-\infty} -xe^{x}dx + \int^\infty_0 xe^{-x}dx$

計算定積分$\displaystyle \int^0_{-\infty} -xe^xdx$

$\displaystyle \int^0_{-\infty} -xe^xdx = -\lim_{a\rightarrow -\infty} \int^0_{a}xe^xdx = -\lim_{a\rightarrow -\infty}(xe^x-e^x)\bigg|^0_a$

$\displaystyle -\lim_{a\rightarrow -\infty}(xe^x-e^x)\bigg|^0_a = -[(0e^0 - e^0) - (\lim_{a\rightarrow -\infty}ae^a - \lim_{a\rightarrow -\infty}e^a)] = -[(-1-0)-(0-0)] = 1$

故$\displaystyle \int^0_{-\infty} -xe^xdx = 1$



計算定積分$\displaystyle \int^{\infty}_{0} xe^{-x}dx$

$\displaystyle  \int^\infty_0 xe^{-x}dx = \lim_{a\rightarrow \infty} \int^a_0 xe^{-x}dx = \lim_{a\rightarrow \infty}(xe^{-x}-e^{-x})\bigg|^a_0$

$\displaystyle \lim_{a\rightarrow \infty}(xe^{-x}-e^{-x})\bigg|^a_0 = \lim_{a\rightarrow \infty}ae^{-a} - \lim_{a\rightarrow \infty}e^{-a} - (0e^{0}-e^0) = 0-0-(0-1) = 1$

故$\displaystyle \int^{\infty}_{0} xe^{-x}dx = 1$



$\displaystyle \int^0_{-\infty} -xe^{x}dx + \int^\infty_0 xe^{-x}dx = 1 + 1 = 2$

故圖形$y = xe^{-|x|}$與$x$軸之間的區域面積為$2$。



### Answer

$2$



## Problem 29

### Statement

若兩圖形$y=x^2-k$和$y=k-x^2$所包圍的區域面積為576，求$k$之值。



### Solution

求兩圖形交點。

$x^2-k = k-x^2$，得到$x^2 = k$，因此$x = \pm\sqrt{k}, k > 0$

因此我們考慮從$-\sqrt{k}$積到$\sqrt{k}$

考慮兩圖形誰在上誰在下，帶入$x = 0$可知第二個函數比第一個函數，在區間$[-\sqrt{k},  \sqrt{k}]$的值來得大

寫出積分式$\displaystyle \int^\sqrt{k}_{-\sqrt{k}}k-x^2-(x^2-k)dx  = \int^\sqrt{k}_{-\sqrt{k}} - 2x^2+2kdx = (\dfrac{-2}{3}x^3 + 2kx)\bigg|^\sqrt{k}_{-\sqrt{k}}$

$(\dfrac{-2}{3}x^3 + 2kx)\bigg|^\sqrt{k}_{-\sqrt{k}} = (\dfrac{-2}{3}k\sqrt{k}+2k\sqrt{k})-(\dfrac{2}{3}k\sqrt{k}-2k\sqrt{k}) = \dfrac{8}{3}k\sqrt{k} = 576$

得到$k = 36$。



### Answer

$k = 36$



## Problem 30

### Statement

已知$f(x) = x^3+x+1$，求$\displaystyle \int^3_1 f^{-1}(x)dx$



### Solution

考慮$x = 0$時，$f(0) = 1$

考慮$x = 1$時，$f(1) = 3$

因為$f(x)$與$f^{-1}(x)$以$y=x$對稱，故$\displaystyle \int^3_1 f^{-1}(x)dx = \int^1_0(x^3+x+1) - xdx$

$\displaystyle  \int^1_0(x^3+1)dx = (\dfrac{x^4}{4}+x)\bigg|^1_0 = \dfrac{1}{4}+1 = \dfrac{5}{4}$



### Answer

$\displaystyle \int^3_1 f^{-1}(x)dx = \dfrac{5}{4}$

