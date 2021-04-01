# 洪輝霖微積分Practice Ch 7-2

###### tags: `微積分題目紀錄`



## Problem 24

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$y=x^2$、$y=0$、$x=1$，旋轉軸$y$軸。



### Solution

先畫出圖。

![image-20210329203700302](https://i.imgur.com/yClUbP9.png)

可知有兩個交點：$(0, 0), (1,1)$。

所求體積

圓柱殼半徑：$d(x) = x$

函數高度：$h(x) = x^2$

則我們可以知道，當$x=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

則我們可以寫出$V = \displaystyle \int^1_0 2\pi d(x)h(x)dx = \int^1_0 2\pi x^3dx = 2\pi\int^1_0x^3dx = \dfrac{\pi}{2}x^4|^1_0 = \dfrac{\pi}{2}$



### Answer

$V = \dfrac{\pi}{2}$



## Problem 25

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$y=\sin(x^2)$、$y=0$、$x=0$，$x=\sqrt{\pi}$，旋轉軸$y$軸。





### Solution

先畫出圖。

![image-20210329204959883](https://i.imgur.com/BGzZ2Ol.png)

可知有兩個交點：$(0, 0), (\sqrt{\pi}, 0)$。

所求體積

圓柱殼半徑：$d(x) = x$

圓柱殼高度：$h(x) = \sin(x^2)$

則我們可以知道，當$x=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

則我們可以寫出$V = \displaystyle \int^\sqrt{\pi}_0 2\pi d(x)h(x)dx = \int^\sqrt{\pi}_0 2\pi x\sin(x^2)dx = 2\pi \int^\sqrt{\pi}_0 x\sin(x^2)dx = -2\pi\cos(x^2)|^\sqrt{\pi}_0 = 2\pi$



### Answer

$V = 2\pi$



## Problem 26

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$y = \dfrac{1}{x}$、$y=0$、$x=1$、$x=2$，旋轉軸$y$軸。



### Solution

先畫出圖。

![image-20210329210958841](https://i.imgur.com/nuc4uJJ.png)

可知有兩個交點：$(1, 1), (2, \dfrac{1}{2})$

所求體積

圓柱殼半徑：$d(x) = x$

圓柱殼高度：$h(x) = \dfrac{1}{x}$

則我們可以知道，當$y=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

則我們可以寫出$V = \displaystyle \int^2_1 2\pi d(x) h(x) dx = 2\pi \int^2_1 d(x)h(x) dx = 2\pi \int^2_1 1dx = 2\pi(x)|^2_1 = 2\pi$



### Answer

$V = 2\pi$



## Problem 27

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$y=x^2+1$、$y=2$，旋轉軸$x$軸。



### Solution

![image-20210329213303840](https://i.imgur.com/1FBRwuI.png)

由於對稱軸為$x$，故我們考慮以$y = 1$積至$y = 2$

所求體積

圓柱殼半徑：$d(y) = y$

圓柱殼高度：$h(y) = 2\sqrt{y-1}$

則我們可以知道，當$x=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

則我們可以寫出$V = \displaystyle \int^2_{1} 2\pi d(y) h(y) dy = \int^2_{1} 4\pi y\sqrt{y-1}dy = 4\pi \int^1_{-1} y\sqrt{y-1}dy$

令$u = \sqrt{y-1}$，則$du = \dfrac{1}{2\sqrt{y-1}}dy$，$dy = 2udu$

$V = \displaystyle 4\pi \int^2_{1} y\sqrt{y-1}dy = 4\pi \int^1_{0} (u^2+1)\times u\times 2u du = 4\pi \int^1_0 2u^4 + 2u^2du = 8\pi(\dfrac{u^5}{5} + \dfrac{u^3}{3})|^1_0 = \dfrac{64\pi}{15}$



### Answer

$V = \dfrac{64\pi}{15}$



## Problem 28

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$x=2y-y^2$、$x=0$，旋轉軸$x$軸。



### Solution

對$x = 2y - y^2$做配方法，$x = 2y-y^2-1+1 = (-y^2+2y-1)+1 = -(y-1)^2+1$

故我們可以畫出一個頂點為$(1, 1)$，開口向左的二次函數，如圖。

![image-20210329214411186](https://i.imgur.com/JZqqoad.png)

由於對稱軸為$x$，故我們考慮以$y=0$積至$y = 2$

所求體積

圓柱殼半徑：$d(y) = y$

圓柱殼高度：$h(y) = 2y-y^2$

則我們可以知道，當$y=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

我們可以寫出$V = \displaystyle \int^2_{0} 2\pi d(y) h(y) dy = \int^2_{0} 2\pi y(2y-y^2)dy = 2\pi \int^2_0 2y^2-y^3dy = 2\pi (\dfrac{2}{3}y^3 - \dfrac{1}{4}y^3)|^2_0 = \dfrac{32\pi}{3}-4\pi = \dfrac{20\pi}{3}$



### Answer

$V = \dfrac{20\pi}{3}$



## Problem 29

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$y = e^{2x}$，$x = 0$，$x = 1$，$y = 0$，旋轉軸$y$軸



### Solution

先畫出圖。

<img src="https://i.imgur.com/trOhQ0U.png" alt="image-20210329215418316" style="zoom: 67%;" />

對稱軸為$y$，所以我們考慮從$x=0$積到$x = 1$。

所求體積

圓柱殼半徑：$d(x) = x$

圓柱殼高度：$h(x) = e^{2x}$

則我們可以知道，當$x=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

我們可以寫出$V = \displaystyle \int^1_02\pi d(x)h(x)dx = \int^1_0 2\pi xe^{2x}dx = 2\pi \int^1_0 xe^{2x}dx$

令$u = 2x$，則$du = 2dx$，$dx = \dfrac{du}{2}$

$V = \displaystyle  2\pi \int^1_0 xe^{2x}dx = 2\pi (\dfrac{xe^{2x}}{2} - \int^1_0 \dfrac{e^{2x}} {2} dx)|^1_0 = 2\pi(\dfrac{xe^{2x}}{2} - \dfrac{e^{2x}}{4})|^1_0 = 2\pi(\dfrac{e^2}{2}-\dfrac{e^2}{4}+\dfrac{1}{4}) = \dfrac{\pi(e^2+1)}{2}$



## Problem 30

### Statement

利用圓柱殼法求下列包圍區域對旋轉軸旋轉所得的固體體積。

$y=e^{-x}$、$x=0$、$x=1$、$y=0$、旋轉軸$y$軸



### Solution

先畫出圖。

![image-20210330140748107](https://i.imgur.com/gHXUYGS.png)

對稱軸為$y$，我們考慮從$x=0$積到$x=1$。

所求體積

圓柱殼半徑：$d(x) = x$

圓柱殼高度：$h(x) = e^{-x}$

則我們可以知道，當$x=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

我們可以寫出$V = \displaystyle \int^1_02\pi d(x)h(x)dx = \int^1_0 2\pi xe^{-x}dx = 2\pi \int^1_0 xe^{-x}dx$

利用分部積分法，令$u = x$，$dv = e^{-x}dx$

則$du = dx$，$v = -e^{-x}$

因此$V = \displaystyle 2\pi \int^1_0 xe^{-x}dx = 2\pi[(-xe^{-x})|^1_0 - \int^1_0 -e^{-x}dx] = 2\pi(-xe^{-x}-e^{-x})|^1_0 = 2\pi(-2e^{-x}+1)= -4\pi e^{-x} + 2\pi$



### Answer

$V = -4\pi e^{-x} + 2\pi$



## Problem 36

### Statement

$y = x^2 + 1,\ y = 2,\text{ rotating by }y = 1$



### Solution

先畫圖

![image-20210401124809828](https://i.imgur.com/yN0ui0I.png)

對稱軸為$y=-1$，我們考慮從$y=1$積到$y=2$。

所求體積

圓柱殼半徑：$d(y) = (y+1)$

圓柱殼高度：$h(y) = 2\sqrt{y-1}$

則我們可以知道，當$x=a$時，圓柱殼$A(a) = 2\pi d(a) h(a)$

我們可以寫出$\displaystyle \int^2_1 2\pi(y+1)(2\sqrt{y-1})dy$

令$u = \sqrt{y-1}$，則$du = \dfrac{dy}{2\sqrt{y-1}}$。因此$dy = 2\sqrt{y-1}du = 2udu$

因此$\displaystyle \int^2_1 2\pi(y+1)(2\sqrt{y-1})dy = 4\pi\int^1_0(u^2+2)(u)(2u)du = 8\pi\int^1_0(u^4+2u^2)du = 8\pi (\dfrac{u^5}{5}+\dfrac{2u^3}{3})\bigg|^1_0 = \dfrac{104}{15}\pi$



### Answer

$\dfrac{104}{15}\pi$

