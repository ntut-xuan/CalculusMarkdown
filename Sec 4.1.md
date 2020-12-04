# 洪揮霖微積分Practice Ch4.1

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = x^2+1,\ [-1, \infty)$



### Solution

<img src="https://i.imgur.com/Z5Or6WQ.png" alt="image-20201120181150340" style="zoom: 67%;" />

觀察圖形，得最小值為$1$，最大值不存在。



### Answer

最小值為$1$，最大值不存在。



## Exercise 2

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = x^2 - 2,\ (-1, 0)$



### Solution

<img src="/home/xuan/圖片/Screenshots/2020-12-04 15-34-11 的螢幕擷圖.png" alt="2020-12-04 15-34-11 的螢幕擷圖"  />

觀察圖形，可以知道最大值與最小值均不存在，故沒有最大值與最小值。



### Answer

最大值與最小值均不存在。



## Exercise 3

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = x^2-2x+3,\ [-2, 3]$



### Solution

<img src="https://i.imgur.com/gEkAKOE.png" alt="image-20201120181503577"  />

觀察圖形，得最小值為$2$，最大值為$11$。



### Answer

最小值為$2$，最大值為$11$。



## Exercise 4

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = |x|, [-2, 1)$



### Solution

![2020-12-04 15-36-56 的螢幕擷圖](/home/xuan/圖片/Screenshots/2020-12-04 15-36-56 的螢幕擷圖.png)

觀察圖形，可以得知最大值為$2$，最小值為$0$。



### Answer

最大值為$2$，最小值為$0$。



## Exercise 5

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = \left\{\begin{array}\ x, & -1\le x \le 0 \\ 2-x, & \space\space\space0<x\le 2 \end{array}\right.$



### Solution

![image-20201120184849768](https://i.imgur.com/MNXoBJQ.png)

注意一下圈圈的點是不存在的，觀察一下圖形可得知最大值不存在、最小值為$-1$。



### Answer

最大值不存在、最小值為$-1$。



## Exercise 6

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = |x^2-4| + 1$



### Solution

![2020-12-04 15-39-13 的螢幕擷圖](/home/xuan/圖片/Screenshots/2020-12-04 15-39-13 的螢幕擷圖.png)

觀察圖形，可以得知最大值為$6$，最小值為$1$。



### Answer

最大值為$6$，最小值為$1$。



## Exercise 7

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = x^2-2x+2,\ [0, 3]$



### Solution

考慮臨界數時，考慮$f'(x) = 0$的點與$f'(x)$不存在的點。

$f'(x) = 2x-2$

考慮$f'(x)$不存在的點，定義域為$\mathbb{R}$因此沒有不存在的點。

考慮$f'(x)$為$0$的點，可知$x=1$時$f'(x)=0$。

因此臨界數$Critical Number \in \{1\}$

考慮最大最小值時，考慮邊界與$CriticalNumber$。

逐一代入得$f(0) = 2, f(1) = 1, f(3)=5$

可知最大值為$5$，最小值為$1$。



### Answer

最大值為$5$，最小值為$1$。



## Exercise 8

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = x^3-3x^2+1,\ [-2, 3]$



### Solution

考慮$f'(x) = 3x^2 - 6x$，極值可能發生在臨界數上，故考慮臨界數。

考慮$f'(x) = 0$，則$x \in \{0, 2\}$，

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

故臨界數$CriticalNumber \in \{0, 2\}$

遞增遞減區間通常被臨界數所分割，故考慮$(-\infty, 0), (0, 2), (2, \infty)$

考慮$(-\infty, 0)$，以$-1$考慮$f'(-1)$，則$f'(-1) > 0$，故$(-\infty, 0)$遞增。

考慮$(0, 2)$，以$1$考慮$f'(1)$，則$f'(1) < 0$，故$(0, 2)$遞減。 

考慮$(2, \infty)$，以$3$考慮$f'(3)$，則$f'(3) > 0$，故$(2, \infty)$遞增。

考慮$x = 0$，左右區間遞增遞減不同，故極值發生在$x = 0$上

考慮$x = 2$，左右區間遞增遞減不同，故極值發生在$x = 2$上

考慮極值與邊界，$f(0) = 1$，$f(2) = -3$，$f(-2) = 19$，$f(3) = 1$。

故最大值為$1$，最小值為$-19$。



### Answer

最大值為$1$，最小值為$-19$。



## Exercise 9

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = 3x^4+4x^3+1,\ [-2, 1]$



### Solution

考慮臨界數時，考慮$f'(x) = 0$的點與$f'(x)$不存在的點。

$f'(x) = 12x^3+12x^2$

考慮$f'(x)$不存在的點，定義域為$\mathbb{R}$因此沒有不存在的點。

考慮$f'(x)$為$0$的點，可知$0, -1$時$f'(x)=0$。

因此臨界數$Critical Number \in \{0, -1\}$

考慮最大最小值時，考慮邊界與$CriticalNumber$。

逐一代入得$f(0) = 1, f(-1) = 0, f(-2)=17, f(1) = 8$

可知最大值為$17$，最小值為$0$。



### Answer

最大值為$17$，最小值為$0$。



## Exercise 10

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = (x-3)\sqrt{x},\quad [0, 4]$



### Solution

考慮$f'(x)  = \dfrac{3x-3}{2\sqrt{x}}$，定義域為$x \ge 0$

考慮極值可能發生在臨界數，則考慮臨界數。

考慮$f'(x) = 0$，則$x \in \{1\}$

考慮$f'(x) = D.N.E.$，則$x \in \{0\}$

因此臨界數$CriticalNumber \in \{0, 1\}$

遞增遞減區間通常會被臨界數所分割，故考慮$(0, 1), (1, \infty)$

考慮$(0, 1)$，以$\dfrac{1}{2}$考慮$f'(\dfrac{1}{2})$，則$f'(\dfrac{1}{2}) < 0$，故$(0, 1)$區間遞減。

考慮$(1, \infty)$，以$2$考慮$f'(2)$，則$f'(2) > 0$，故$(1, \infty)$區間遞增。

考慮$x= 1$的情況，左右區間遞增遞減不同，故極值發生在$x = 1$上。

考慮邊界與極值，$f(0) = 0$，$f(1) = -2$，$f(4) = 2$

故最大值為$2$，最小值為$-2$。



### Answer

最大值為$2$，最小值為$-2$。



## Exercise 11

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = \dfrac{x}{x-1},\ [2,4]$



### Solution

考慮臨界數時，考慮$f'(x) = 0$的點與$f'(x)$不存在的點。

$f'(x) = \dfrac{-1}{(x-1)^2}$

考慮$f'(x)$不存在的點，定義域為$x\neq 1$，因此$x=1$為$CriticalNumber$。

考慮$f'(x)=0$，找不到任何一個$x$使得$f'(x) = 0$

因此臨界數$Critical Number \in \{1\}$

考慮最大最小值時，考慮邊界與$CriticalNumber$。

逐一代入得$f(2) = 2,\ f(4) = \dfrac{4}{3},\ f(1) = D.N.E.$

可知最大值為$2$，最小值為$\dfrac{4}{3}$。



### Answer

最大值為 $2$ ，最小值為 $\dfrac{4}{3}$ 。



## Exercise 12

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = \dfrac{x}{x^2+1},\quad [-1, 2]$



### Solution

考慮$f'(x)  = \dfrac{-x^2+1}{(x^2+1)^2}$

考慮極值可能發生在臨界數，則考慮臨界數。

考慮$f'(x) = 0$，則$x \in \{-1, 1\}$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$CriticalNumber \in \{-1, 1\}$

遞增遞減區間通常會被臨界數所分割，故考慮$(-1, 1), (1, 2)$

考慮$(-1, 1)$，以$\dfrac{1}{2}$考慮$f'(\dfrac{1}{2})$，則$f'(\dfrac{1}{2}) > 0$，故$(-1, 1)$區間遞增。

考慮$(1, 2)$，以$\dfrac{3}{2}$考慮$f'(2)$，則$f'(\dfrac{3}{2}) < 0$，故$(1, 2)$區間遞減。

考慮$x= 1$的情況，左右區間遞增遞減不同，故極值發生在$x = 1$上。

考慮邊界與極值，$f(-1) = -\dfrac{1}{2}$，$f(1)=\dfrac{1}{2}$，$f(2) = \dfrac{2}{5}$

故最大值為$\dfrac{1}{2}$，最小值為$-\dfrac{1}{2}$。



### Answer

最大值為$\dfrac{1}{2}$，最小值為$-\dfrac{1}{2}$。



## Exercise 13

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(t) = t\sqrt{4-t^2},\ [0, 2]$



### Solution

考慮臨界數時，考慮$f'(t) = 0$的點與$f'(t)$不存在的點。

$f'(t) =\dfrac{4-2t^2}{\sqrt{4-t^2}}$

考慮$f'(t) = 0$，可知$t = \pm\sqrt{2}$時，$f'(t) = 0$，其中$-\sqrt{2}$不合，因為不在區間內。

考慮$f'(t)=D.N.E$，可知$t = \pm 2$時，$f'(t) = D.N.E$，其中$-2$不合，因為不在區間內。

因此臨界數$Critical Number \in \{\sqrt{2}, 2\}$

考慮最大最小值時，考慮邊界與$CriticalNumber$。

逐一代入得$f(0) = 0,\ f(2) = 0,\ f(\sqrt{2}) = 2$

可知最小值為$0$，最大值為$2$



### Answer

最小值為 $0$ ，最大值為 $2$ 。



## Exercise 14

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = x-2\sqrt{x}, \quad [0, 9]$



### Solution

考慮$f'(x)  = \dfrac{\sqrt{x}-1}{\sqrt{x}}$

考慮極值可能發生在臨界數，則考慮臨界數。

考慮$f'(x) = 0$，則$x \in \{1\}$

考慮$f'(x) = D.N.E.$，則$x \in \{0\}$

因此臨界數$CriticalNumber \in \{0, 1\}$

遞增遞減區間通常會被臨界數所分割，故考慮$(0, 1), (1, 9)$

考慮$(0, 1)$，以$\dfrac{1}{2}$考慮$f'(\dfrac{1}{2})$，則$f'(\dfrac{1}{2}) < 0$，故$(0, 1)$區間遞減。

考慮$(1, 9)$，以$4$考慮$f'(4)$，則$f'(4) > 0$，故$(1, 9)$區間遞增。

考慮$x= 1$的情況，左右區間遞增遞減不同，故極值發生在$x = 1$上。

考慮邊界與極值，$f(0) = 0, f(1) = -1, f(9)=3$

故最大值為$3$，最小值為$-1$。



### Answer

最大值為$3$，最小值為$-1$。



## Exercise 15

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(t) = t-2\sin t,\ [0, \dfrac{\pi}{2}]$



### Solution

考慮臨界數時，考慮$f'(t) = 0$的點與$f'(t)$不存在的點。

$f'(t) = 1-2\cos t$

考慮$f'(t) = 0$，得到$t = \dfrac{\pi}{3}$

考慮$f'(t) = D.N.E$，$f'(t)$定義域為$\mathbb{R}$因此沒有不存在的點。

因此臨界數$Critical Number \in \{\dfrac{\pi}{3}\}$

考慮最大最小值時，考慮邊界與$CriticalNumber$。

逐一代入得$f(0) = 0,\ f(\dfrac{\pi}{3}) = \dfrac{\pi}{3}-\sqrt{3},\ f(\dfrac{\pi}{2}) = \dfrac{\pi}{2}-2$

可知最小值為$\dfrac{\pi}{3}-\sqrt{3}$，最大值為$0$。



### Answer

最小值為$\dfrac{\pi}{3}-\sqrt{3}$，最大值為$0$。



## Exercise 16

### Statement

利用臨界值與端點的函數值判斷，求函數的最大值與最小值。

$f(x) = xe^{-x^2+x}, \quad [-1, 1]$



### Solution

考慮$f'(x) = (-2x^2+x+1)e^{-x^2+x} = -(x-1)(2x+1)e^{-x^2+x}$

考慮極值可能發生在臨界數，則考慮臨界數。

考慮$f'(x) = 0$，則$x \in \{-\dfrac{1}{2}, 1\}$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$CriticalNumber \in \{-\dfrac{1}{2}, 1\}$

遞增遞減區間通常會被臨界數所分割，故考慮$(-1, -\dfrac{1}{2}), (-\dfrac{1}{2}, 1)$

考慮$(-1, -\dfrac{1}{2})$，以$-\dfrac{2}{3}$考慮$f'(-\dfrac{2}{3})$則$f'(-\dfrac{2}{3}) < 0$，故$(-1, -\dfrac{2}{3})$區間遞減。

考慮$(-\dfrac{1}{2}, 1)$，以$0$考慮$f'(0)$，則$f'(0) > 0$，故$(-\dfrac{1}{2}, 1)$區間遞增。

考慮$x= -\dfrac{1}{2}$的情況，左右區間遞增遞減不同，故極值發生在$x= -\dfrac{1}{2}$上。

考慮邊界與極值，$f(-1) = -e^{-2}, f(-\dfrac{1}{2}) = -\dfrac{1}{2\sqrt[4]{e^3}}$,  f(1) = 1$

故最大值為$1$，最小值為$-\dfrac{1}{2\sqrt[4]{e^3}}$。



### Answer

最大值為$1$，最小值為$-\dfrac{1}{2\sqrt[4]{e^3}}$。



## Exercise 17

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = 2x^3-6x+3$



### Solution

先求得一階導數，$f'(x) = 6x^2-6$

考慮極值可能發生在$CriticalNumber$

因此考慮$f'(x) = 0$與$f'(x) = D.N.E.$

由於一階導數的定義域為$\mathbb{R}$，因此不會發生$D.N.E.$的可能

考慮$f'(x) = 0$，得到$x = \pm 1$

因此$CriticalNumber \in \{-1, 1\}$

考慮極值的部分，將$CriticalNumber$帶入，$f(-1) = 7$，$f(1) = -1$

因此可得知最大值為$7$，最小值為$-1$ 

針對於遞增，遞減的區間，可由$f'(x) = 0$的點來分割區間

故考慮$(-\infty, -1), (-1, 1), (1, \infty)$

考慮$(-\infty, -1)$，以$-2$考慮$f'(-2)$，可知$f'(-2) > 0$，故遞增

考慮$(-1, 1)$，以$0$考慮$f'(0)$，可知$f'(0) < 0$，故遞減

考慮$(1, \infty)$，以$2$考慮$f'(2)$，可知$f'(2) > 0$，故遞增



### Answer

最大值為$7$，最小值為$-1$ 

遞增區間：$(-\infty, -1), (1, \infty)$ 

遞減區間：$(-1, 1)$ 



## Exercise 18

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = 2x^3+3x^2-12x+4$



### Solution

考慮$f'(x) = 6x^2+6x-12 = 6(x+2)(x-1)$ 

考慮極值通常發生在臨界數上，故我們考慮臨界數

考慮$f'(x) = 0$，則$x = \{-2, 1\}$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

因此可以知道臨界數$CriticalPoint \in \{-2, 1\}$

考慮遞增遞減區間通常被臨界數所分割，故我們考慮$(-\infty, -2),(-2, 1),(1, \infty)$

考慮$(-\infty, -2)$，以$-3$考慮$f'(-3)$，則$f'(-3) > 0$，故$(-\infty, -2)$區間遞增。

考慮$(-2, 1)$，以$0$考慮$f'(0)$，則$f'(0) < 0$，故$(-2, 1)$區間遞減。

考慮$(1, \infty)$，以$2$考慮$f'(2)$，則$f'(2) > 0$，故$(1, \infty)$區間遞增。

考慮$x = -2$，左右兩邊遞增遞減區間不同，故極值發生在$x = -2$上

考慮$x = 1$，左右兩邊遞增遞減區間不同，故極值發生在$x = 1$上

考慮極值發生的地方，得到相對最大值$f(-2) = 24$，相對最小值$f(1) = -3$。



### Answer

遞減區間：$(-2, 1)$

遞增區間：$(1, \infty),(-\infty, -2)$

相對最小值$f(1) = -3$，相對最大值$24$。



## Exercise 19

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = \dfrac{1}{3}x^3 + x^2 - 3x - 2$



### Solution

先求得一階導數，$f'(x) = x^2+2x-3$

考慮極值可能發生在$CriticalNumber$

因此考慮$f'(x) = 0$與$f'(x) = D.N.E.$

由於一階導數的定義域為$\mathbb{R}$，因此不會發生$D.N.E.$的可能

考慮$f'(x) = 0$，得到$x = 1, -3$

因此$CriticalNumber \in \{1, -3\}$

考慮極值的部分，將$CriticalNumber$帶入，$f(1) = \dfrac{-11}{3}$，$f(-3) = 0$

因此可得知最大值為$0$，最小值為$7$ 

針對於遞增，遞減的區間，可由$f'(x) = 0$的點來分割區間

故考慮$(-\infty, -3),(-3, 1),(1, \infty)$

考慮$(-\infty, -3)$，以$-4$考慮$f'(-4)$，可知$f'(-4) > 0$，故遞增

考慮$(-3, 1)$，以$0$考慮$f'(0)$，可知$f'(0) < 0$，故遞減

考慮$(1, \infty)$，以$2$考慮$f'(2)$，可知$f'(2) > 0$，故遞增



### Answer

最大值為$0$，最小值為$7$ 

遞增區間：$(-\infty, -3),(1, \infty)$

遞減區間：$(-3, 1)$



## Exercise 20

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = 3x^4-4x^3+1$

### Solution

先求得一階導數 $f'(x) = 12x^3-12x^2$

考慮 Critical Number 會出現在 $f'(x) = 0$ 或 $f'(x)$ does not exist 的地方

由於多項式函數 $f'(x) \in \mathbb{R}$ ，因此我們只要考慮 $f'(x)$ 為零的位置

將 $f'(x)$ 因式分解，得到 $f'(x) = 12x^2(x-1)$ 

![](https://i.imgur.com/ItXpc26.png) 

（綠色為原函數，紅色為一階導數）


我們可以得知 $f'(x)=0$ 會發生在 $x=0,1$ 的位置

而判斷函數的相對極值時會發生在 $f'(x)$ 變號的位置

因此在 $f'(x) = 0$ 重根時不會出現相對極值，所以只需要考慮 $x=1$ 的情況

由於 $f'(x)$ 為多項式且領導係數為正，我們可以知道 $f'(x)$ 在 $(1,\infty)$ 為遞增

而在 $(-\infty,1)$ 為遞減
### Answer

Local Minima: $f(1) = 0$

Local Maxima: None

遞增區間： $(1,\infty)$

遞減區間： $(-\infty,1)$

## Exercise 21

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = 3x^4+4x^3-12x^2+8$

### Solution

先求得一階導數，$f'(x) = 12x^3+12x^2-24x$

考慮極值可能發生在$CriticalNumber$

因此考慮$f'(x) = 0$與$f'(x) = D.N.E.$

由於一階導數的定義域為$\mathbb{R}$，因此不會發生$D.N.E.$的可能

考慮$f'(x) = 0$，得到$x = 0, 1, -2$

因此$CriticalNumber \in \{0, 1, -2\}$

考慮極值的部分，將$CriticalNumber$帶入，$f(0) = 8$，$f(1) = 3$，$f(-2) = -24$

因此可得知相對最大值為$8$，相對最小值為$-24, 3$ 

針對於遞增，遞減的區間，可由$f'(x) = 0$的點來分割區間

故考慮$(-\infty, -2),(-2, 0),(0, 1),(1, \infty)$

考慮$(-\infty, -2)$，以$-3$考慮$f'(-3)$，可知$f'(-3) < 0$，故遞減

考慮$(-2, 0)$，以$-1$考慮$f'(-1)$，可知$f'(-1) > 0$，故遞增

考慮$(0, 1)$，以$0.5$考慮$f'(0.5)$，可知$f'(0.5) < 0$，故遞減

考慮$(1, \infty)$，以$2$考慮$f'(2)$，可知$f'(2) > 0$，故遞增



### Answer

相對最大值為$8$，相對最小值為$-24, 3$ 

遞增區間：$(-2, 0),(1, \infty)$

遞減區間：$(-\infty, -2),(0, 1)$



## Exercise 22

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = 4x^{\frac{1}{3}}+x^{\frac{4}{3}}$

### Solution

先求得一階導數 $f'(x) = \frac{4}{3}x^{-\frac{2}{3}}+\frac{4}{3}x^{\frac{1}{3}}$

考慮 Critical Number 會出現在 $f'(x) = 0$ 或 $f'(x)$ does not exist 的地方

我們可以解出在 $x=-1$ 時 $f'(x) = 0$ ， 而在 $x=0$ 時 $f'(x)$ 則不存在

我們可以將 $f'(x)$ 的圖形畫出來

![](https://i.imgur.com/fGZE1LQ.png)

可以得知，在 $x=-1$ 時有 Local Minima，而在 $x=0$ 時並無相對極值且有垂直切線

因此，在 $(-1,\infty)$ 時，函數遞增

在 $(-\infty,-1)$ 時，函數遞減

### Answer 

Local Minima: $x=-1$

遞增區間： $(-1,\infty)$

遞減區間： $(-\infty,-1)$



## Exercise 23

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = x^3-3x^2-9x+2$



### Solution

$f'(x) = 3x^2-6x-9$

先求$Critical Number$發生的位置

考慮$f'(x) = 0$，則$x = -1$或者$x = 3$

考慮$f'(x) = D.N.E.$的情況，由於函數定義域為$\mathbb{R}$，因此$x \in \varnothing$。

因此$Critical Number \in \{-1, 3\}$

遞增與遞減區間將被$Critical Number$所分割

因此考慮$(-\infty, -1), (-1, 3), (3, \infty)$的遞增與遞減情況

考慮$(-\infty, -1)$，以$-2$考慮$f'(-2)$，得知$f'(-2) > 0$，因此$(-\infty, -1)$區間遞增，

考慮$(-1, 3)$，以$0$考慮$f'(0)$，得知$f'(0)<0$，因此$(-1, 3)$區間遞減，

考慮$(3, \infty)$，以$4$考慮$f'(4)$，得知$f'(4) > 0$，因此$(3, \infty)$區間遞增，

考慮界於$(-1)$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$(-1)$為極值發生的地方。

考慮界於$3$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$(3)$為極值發生的地方。

故考慮$f(3) = -25$，$f(-1)=7$，得到相對最大值為$7$，相對最小值為$-25$



### Answer

相對最大值為$7$，相對最小值為$-25$。



## Exercise 24

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = x^4-2x^2+1$



### Solution

$f'(x) = 4x^3-4x$

考慮CriticalNumber，則

考慮$f'(x) = 0$，則$x = 0$或$x = \pm1$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

因此$CriticalNumber \in \{-1, 0, 1\}$

遞增遞減區間會由$CriticalNumber$所分割

因此考慮三個區間$(-\infty, -1), (-1, 0),(0, 1),(1, \infty)$

考慮$(-\infty, -1)$，以$-2$考慮$f'(-2)$，則$f'(-2) < 0$，因此$(-\infty, -1)$區間遞減

考慮$(-1, 0)$，以$-0.5$考慮$f'(-0.5)$，則$f'(-0.5) > 0$，因此$(-1, 0)$區間遞增

考慮$(0 ,1)$，以$0.5$考慮$f'(0.5)$，則$f'(0.5) < 0$，因此$(0, 1)$區間遞減

考慮$(1, \infty)$，以$2$考慮$f'(2)$，則$f'(2) > 0$，因此$(1, \infty)$區間遞增

考慮界於$-1$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$-1$為極值發生的地方。

考慮界於$0$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$0$為極值發生的地方。

考慮界於$1$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$1$為極值發生的地方。

因此將$f(x)$帶入極值發生的地方，$f(-1) = 0, f(0) = 1, f(1) = 0$

因此相對最大值為$1$，相對最小值為$0$。



### Answer

相對最大值為$1$，相對最小值為$0$。



## Exercise 25

### Statemnet

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = xe^{-x^2}$



### Solution

$f'(x) = (1-2x^2)e^{-x^2}$

先求$Critical Number$發生的位置

考慮$f'(x) = 0$，則$x = \pm\dfrac{\sqrt{2}}{2}$

考慮$f'(x) = D.N.E.$的情況，由於函數定義域為$\mathbb{R}$，因此$x \in \varnothing$。

因此$Critical Number \in \{\dfrac{\sqrt{2}}{2}, \dfrac{-\sqrt{2}}{2} \}$

遞增與遞減區間將被$Critical Number$所分割

因此考慮$(-\infty, -\dfrac{\sqrt{2}}{2}),(-\dfrac{\sqrt{2}}{2}, \dfrac{\sqrt{2}}{2}) ,(\dfrac{\sqrt{2}}{2}, \infty)$的遞增與遞減情況

考慮$(-\infty, -\dfrac{\sqrt{2}}{2})$，以$-2$來考慮$f'(-2)$，得$f'(-2) < 0$，因此$(-\infty, -\dfrac{\sqrt{2}}{2})$遞減

考慮$(-\dfrac{\sqrt{2}}{2}, \dfrac{\sqrt{2}}{2})$，以$0$來考慮$f'(0)$，得$f'(0) > 0$，因此$(-\dfrac{\sqrt{2}}{2}, \dfrac{\sqrt{2}}{2})$遞增

考慮$(\dfrac{\sqrt{2}}{2}, \infty)$，以$2$來考慮$f'(2)$，得$f'(2)<0$，因此$(\dfrac{\sqrt{2}}{2}, \infty)$遞減

考慮界於$-\dfrac{\sqrt{2}}{2}$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$-\dfrac{\sqrt{2}}{2}$為極值發生的地方。

考慮界於$\dfrac{\sqrt{2}}{2}$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$\dfrac{\sqrt{2}}{2}$為極值發生的地方。

故考慮$f(-\dfrac{\sqrt{2}}{2}) = \dfrac{\sqrt{2}}{2}e^{\dfrac{-1}{2}}$，$f(-\dfrac{-\sqrt{2}}{2}) = \dfrac{-\sqrt{2}}{2}e^{\dfrac{-1}{2}}$，得到相對最大值為$\dfrac{\sqrt{2}}{2}e^{\dfrac{-1}{2}}$，相對最小值為$\dfrac{-\sqrt{2}}{2}e^{\dfrac{-1}{2}}$



### Answer

遞增區間：$(-\dfrac{\sqrt{2}}{2}, \dfrac{\sqrt{2}}{2})$

遞減區間：$(-\infty, -\dfrac{\sqrt{2}}{2})$，$(\dfrac{\sqrt{2}}{2}, \infty)$

相對最大值為$\dfrac{\sqrt{2}}{2}e^{\dfrac{-1}{2}}$，相對最小值為$\dfrac{-\sqrt{2}}{2}e^{\dfrac{-1}{2}}$



## Exercise 26

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = \dfrac{x}{x^2+1}$



### Solution

考慮$f'(x) = \dfrac{(x^2+1)-2x^2}{(x^2+1)^2} = \dfrac{-x^2+1}{(x^2+1)^2}$

考慮CriticalNumber，因此

考慮$f'(x) = 0$，則$x \in \{1, -1\}$時會使$f'(x) = 0$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

因此$CriticalNumber \in \{1, -1\}$

考慮遞增遞減區間會被$CriticalNumber$所分割，因此

考慮$(-\infty, -1), (-1, 1), (1, \infty)$

考慮$(-\infty, -1)$，以$-2$帶入$f'(-2)$，則$f'(-2) < 0$，故$(-\infty, -1)$遞減

考慮$(-1, 1)$，以$0$帶入$f'(0)$，則$f'(0) > 0$，故$(-1, 1)$遞增

考慮$(1, \infty)$，以$2$帶入$f'(2)$，則$f'(2) < 0$，故$(1, \infty)$遞減

考慮界於$-1$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$-1$為極值發生的地方。

考慮界於$1$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$1$為極值發生的地方。

因此將$f(x)$帶入極值發生的地方，則$f(-1) = -\dfrac{1}{2}$，且$f(1) = \dfrac{1}{2}$

因此相對最大值為$-\dfrac{1}{2}$，相對最小值為$\dfrac{1}{2}$



### Answer

相對最大值為$-\dfrac{1}{2}$，相對最小值為$\dfrac{1}{2}$。



## Exercise 27

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = \sqrt[3]{x^2-x^3}$



### Solution

$f'(x) = \dfrac{(2x-3x^2)}{3\sqrt[3]{(x^2-x^3)^2}}$

考慮$f'(x) = 0$，則$x = \dfrac{2}{3}$

考慮$f'(x) = D.N.E.$，則$x \in \{0, 1\}$

因此$Critical Number \in \{0, \dfrac{2}{3}, 1\}$

遞增與遞減區間將被$Critical Number$所分割

因此考慮$(-\infty, 0), (0, \dfrac{2}{3}), (\dfrac{2}{3}, 1), (1, \infty)$的遞增與遞減情況

考慮$(-\infty, 0)$，以$-1$來考慮$f'(-1)$，得$f'(-1) < 0$，因此$(-\infty, 0)$遞減

考慮$(0, \dfrac{2}{3})$，以$\dfrac{1}{3}$來考慮$f'(\dfrac{1}{3})$，得$f'(\dfrac{1}{3}) > 0$，因此$(0, \dfrac{2}{3})$遞增。

考慮$(\dfrac{2}{3}, 1)$，以$0.9$來考慮$f'(0.9)$，得$f'(0.9)<0$，因此$(\dfrac{2}{3}, 1)$遞減。

考慮$(1, \infty)$，以$2$來考慮$f'(2)$，得$f'(2) < 0$，因此$(1, \infty)$遞減。

考慮界於$0$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$0$為極值發生的地方。

考慮界於$\dfrac{2}{3}$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$\dfrac{2}{3}$為極值發生的地方。

考慮界於$1$的兩邊遞增遞減情況，由於兩邊遞增遞減情況相同，得知$1$不為極值發生的地方。

故考慮$f(0) = 0$，$f(\dfrac{2}{3})  = \dfrac{\sqrt[3]{4}}{3}$，因此相對最大值為$\dfrac{\sqrt[3]{4}}{3}$，相對最小值為$0$。



### Answer

遞增區間：$(0, \dfrac{2}{3})$

遞減區間：$(-\infty, 0)$，$(\dfrac{2}{3}, 1)$，$(1, \infty)$

相對最大值為$\dfrac{\sqrt[3]{4}}{3}$，相對最小值為$0$。



## Exercise 28

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = \dfrac{x^2-1}{x^2+1}$



### Solution

$f'(x) = \dfrac{4x^3}{(x^2+1)^2}$

考慮$f'(x) = 0$，則$x \in \{0\}$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

因此$CriticalNumber \in \{0\}$

考慮遞增遞減區間會被$CriticalNumber$所分割，因此考慮區間$(-\infty, 0),(0, \infty)$

考慮區間$(-\infty, 0)$，以$-1$考慮$f'(-1)$，則$f'(-1) = -1$，因此$(-\infty, 0)$區間遞減

考慮區間$(0, \infty)$，以$1$考慮$f'(1)$，則$f'(1) = 1$，因此$(0, \infty)$區間遞增

考慮界於$0$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$0$為極值發生的地方。

因此將$f(x)$代入極值發生的地方，得到$f'(0) = \dfrac{-1}{1} = -1$

故相對最小值為$-1$，相對最大值不存在。



### Answer

相對最小值為$-1$，相對最大值不存在。



## Exercise 29

### Statement

試證對任意$x \ge 0$，$\sin x \le x$恆成立。



### Solution

考慮$\sin x - x \le 0$，令$f(x) = \sin x - x$

一階導數$f'(x) = \cos x - 1$

考慮$Critical Number$發生的位置

考慮$f'(x) = 0$，得$x = 0$，

考慮$f'(x) = D.N.E$，由於定義域為$\mathbb{R}$，故$x \in \empty$

遞增遞減區間將可能被$CriticalNumber$所分割

因此考慮$(-\infty, 0), (0, \infty)$

考慮$(-\infty, 0)$，以$-\pi$考慮$f'(-\pi)$，得知$\cos(-\pi) < 0$

考慮$(0, \infty)$，以$\pi$考慮$f'(\pi)$，得知$\cos(\pi) < 0$

故在$(0, \infty)$區間中$\sin x - x$必定遞減，也就是$\sin x \le  x$

也因此，對任意$x \ge 0$，$\sin x \le x$恆成立，證畢。



### Answer

See solution.



## Exercise 30

### Statement

試證對任意$x>1$，$2\sqrt{x}>3-\dfrac{1}{x}$均成立。



### Solution

考慮$2\sqrt{x}+\dfrac{1}{x}-3 > 0$

令$f(x) = 2\sqrt{x} + \dfrac{1}{x} - 3$，則$f'(x) = \dfrac{1}{\sqrt{x}} - \dfrac{1}{x^2}$

考慮$f'(x) = 0$，則$x \in \{1\}$，因此$1$為CriticalNumber之一。

考慮$f'(x) = D.N.E.$，則$\{x\ |\ x \le 0\}$

故考慮$(1, \infty)$的遞增區間，以$2$考慮$f'(2)$，則$f'(2) > 0$

因此$(1, \infty)$為遞增區間，又考慮$f(1)$，則$f(1) = 0$

故在$(1, \infty)$上的所有$x$之$f(x)$大於$0$，證畢。



### Answer

See solution.



## Exercise 31

### Statement

假設$f(x)=x^2+ax+b$在$x=1$時有相對極小值$3$，求$a、b$之值。



### Solution

$f'(x) = 2x+a$

考慮在$x=1$時有相對極小值3，則$f'(1) = 0$，也就是$2+a=0$，得$a=-2$。

因為極值發生在$x=1$上，考慮$f(1) = 1-2+b=3$，得到$b=4$。



### Answer

$(a, b) = (-2, 4)$



## Exercise 32

### Statement

假設$f(x)=ax^2+bx+1$在$x=-1$時有相對極大值$2$，求$a$、$b$之值。



### Solution

考慮$f'(x) = 2ax+b$，則由於$x=-1$時有相對極大值，故$f'(-1) = 0$

因此$-2a+b=0$

考慮$f(x)$在$x=-1$時有相對極大值$2$，因此$f(-1)=a-b+1=2$

因此$a-b=1$

兩式解聯立，$\left\{\begin{array}7 -2a+b=0 \\ a-b=1\end{array}\right.$，得$a = -1$，且$b = -2$



### Answer

$a = -1,\ b = -2$



## Exercise 33

### Statement

假設$f(x)  = x^3+ax^2+bx+1$在$x=-1$時有相對極大值，在$x=3$時有相對極小值，求$a, b$之值。



### Solution

$f'(x) = 3x^2+2ax+b$

考慮$x=-1$時有相對極大值，在$x=3$時有相對極小值，因此$f'(-1) = 0, f'(3) = 0$

可得知$f'(x) = 3(x+1)(x-3) = 3x^2-6x-9$

比較係數，得到$2a=-6, a= -3$，且$b=-9$



### Answer

$(a, b) = (-3, -9)$



## Exercise 34

### Statement

假設函數$f(x) = ax^3+bx^2+cx+d$圖形在點$(0,1)$有相對極小值，在$(1, 2)$有相對極大值，求此函數$f$



### Solution

$f'(x) = 3ax^2+2bx+c$，則$f'(0) = 0, f(1) = 0$，故$f'(x) = x(x-1) = x^2-x$，可知$c=0$

$f(0) = d = 1$，可知$d=1$

考慮$f(1) = a+b+1 = 2$，則$a+b=1$

考慮$f'(1) = 3a+2b = 0$，則$3a+2b=0$

則$a = -2$，且$b = 3$



故$a = -2, b = 3, c = 0, d = 1$



### Answer

$a = -2, b = 3, c = 0, d = 1$



## Exercise 35

### Statement

假設$f(x) = x^3-|1-3x^2|$，$x \in [-2, 3]$。求$f$在$[-2, 3]$上的最大值。



### Solution

$f'(x) = 3x^2 - \dfrac{18x^3-6x}{|1-3x^2|}$ 

考慮$Critical Number$的部分

考慮$f'(x) = 0$，得到$x \in \{0, 2\}$

考慮$f'(x) = D.N.E.$，得到$x \in \{\pm(\dfrac{\sqrt{3}}{3})\}$

因此$Critical Number \in \{-\dfrac{\sqrt{3}}{3}, 0, \dfrac{\sqrt{3}}{3}, 2\}$

考慮邊界與$CriticalNumber$

一一帶入$f(x)$，得$f(-2) = -19, f(-\dfrac{\sqrt{3}}{3}) = \dfrac{-\sqrt{3}}{9}, f(0) = -1, f(\dfrac{\sqrt{3}}{3}) = \dfrac{\sqrt{3}}{3}, f(2)= -3, f(3) = 1$

可知最大值為$1$。



### Answer

最大值為$1$。



## Exercise 36

### Statement

假設$f(x) = x^{\frac{1}{x^2}}$，求$f$在$(0, \infty)$上的最大值。



### Solution

$f(x) = x^{x^{-2}}$，則$f'(x) = x^{\frac{1-3x^2}{x^2}} (-2\ln x + 1)$

考慮在區間$(0, \infty)$內的Critical Number，則得$CriticalNumber \in \{\sqrt{e}\}$

遞增遞減區間由$CriticalNumber$分割，則考慮$(0, \sqrt{e}),(\sqrt{e}, \infty)$

考慮$(0, \sqrt{e})$，以$1$考慮$f'(1)$，則$f'(1) > 0$，故$(0, \sqrt{e})$遞增。

考慮$({\sqrt{e}}, \infty)$，以$e$考慮$f'(e)$，則$f'(e) > 0$，故$(\sqrt{e}, \infty)$遞減。

考慮界於$\sqrt{e}$的兩邊遞增遞減情況，由於兩邊遞增遞減情況不同，得知$\sqrt{e}$為極值發生的地方。

將發生極值的地方帶入$f(x)$，得到$f(e) = e^\frac{1}{2e}$



### Answer

$f$在$(0, \infty)$的最大值為$e^\frac{1}{2e}$。




## Exercise 37

### Statement

試證如果$\alpha > 1$，則對所有$x > -1$，恆滿足$(1+x)^{\alpha} \ge 1+\alpha x$。



### Solution

考慮$(1+x)^{\alpha} - \alpha x - 1 \ge 0$，令$f(x) = (1+x)^{\alpha} - \alpha x - 1$

$f'(x) = \alpha(1+x)^{\alpha -1} - \alpha$

考慮$\alpha \in odd$，則$a - 1 \in Even$

因此$Critical Number \in \{-2, 0\}$

遞增遞減區間會被$CriticalNumber$分割，故考慮$(-\infty, -2),(-2, 0),(0, \infty)$

考慮$(-\infty, -2)$，以$-3$考慮$f'(-3)$，則$f'(-3) > 0$，故$(-\infty, -2)$遞增。

考慮$(-2, 0)$，以$-1$考慮$f'(-1)$，則$f'(-1) < 0$，故$(-2, 0)$遞減。

考慮$(0, \infty)$，以$1$考慮$f'(1)$，則$f'(1) > 0$，故$(0, \infty)$遞增。

我們可以知道極值發生在$x=-2$與$x=0$上，故$f(0) = \alpha(1+0)^{\alpha-1} - \alpha = \alpha - \alpha = 0$

故我們知道$(-2, 0)$均大於0，$(0, \infty)$也均大於$0$，因此區間$[-1, \infty]$均大於0，成立。

考慮$\alpha \in Even$，則$a - 1 \in Odd$

因此$Critical Number \in \{0\}$

遞增遞減區間會被$CriticalNumber$分割，故考慮$(-\infty, 0), (0, \infty)$

考慮$(-\infty, 0)$，以$-3$考慮$f'(-3)$，則$f'(-3) < 0$，故$(-\infty, 0)$遞減。

考慮$(0, \infty)$，以$1$考慮$f'(1)$，則$f'(1) > 0$，故$(0, \infty)$遞增。

因此極值發生在$x = 0$上，故考慮$f(0)=\alpha(1+0)^{\alpha-1} - \alpha = \alpha - \alpha = 0$

故我們知道$(-\infty, 0)$均大於0，$(0, \infty)$也均大於$0$，因此區間$[-1, \infty]$均大於0，成立。

因此$\alpha \in Even, Odd$均考慮，使得$\alpha \in \mathbb{R}$均被考慮到，證畢。



### Answer

See solution.



## Exercise 38

### Statement

試證如果$0<\alpha<1$，則對所有$x > -1$，恆滿足$(1+x)^\alpha \le  1 + \alpha x$。



### Solution

考慮$(1+x)^{\alpha} - \alpha x - 1 \le 0$，則令$f(x) = (1+x)^{\alpha} - \alpha x - 1 \le 0$

當$0 < \alpha < 1$時，$f(x)$的定義域為$x \ge -1$。

$f'(x) = \alpha(1+x)^{\alpha - 1} - \alpha = \alpha((1+x)^{\alpha-1}-1)$

由於$0 < \alpha < 1$，則$\alpha - 1$必定小於$0$，也就使得$(1+x)^{\alpha-1} < 1$，故$(1+x)^{\alpha - 1}-1 < 0$。

考慮極值通常發生在臨界數$CriticalPoint$的地方。

考慮$f'(x) = 0, x \in D(f)$，得$x \in 0$

考慮$f'(x) = D.N.E., x > -1$，得$x \in \varnothing$

遞增遞減區間通常由臨界數分割，因此考慮$(-1, 0), (0, \infty)$

考慮若$1+x < 0$，則$(1 + x)^{\alpha - 1} > 1$，若$1 + x > 0$，則$(1 + x)^{\alpha - 1} < 1$

因此可知$(-1, 0)$為遞增區間，$(0, \infty)$為遞減區間。

考慮$x = 0$，左右兩邊遞增遞減區間不同，故極值發生在$x = 0$上。

可知$f(0) = 0$，因此對於$(-1, 0)$遞增到$0$為止，對於$(0, \infty)$從$0$開始遞減

故對於$(-1, \infty)$均小於$0$，證畢。



### Answer

See solution.



## Exercise 39

### Statement

找一最小值$\beta$，使得對任意$x > 0$，恆滿足$\beta > \dfrac{2x-1}{x}$



### Solution

考慮$\beta - \dfrac{2x-1}{x} > 0$，令$f(x) = \beta - \dfrac{2x-1}{x}$

則$f'(x) = -\dfrac{2x-(2x-1)}{x^2} = -\dfrac{1}{x^2}$

考慮CriticalNumber

考慮$f'(x) = 0$，則$x \in \varnothing$

考慮$f'(x) = D.N.E.$，則$x \in \{0\}$

因此$CriticalNumber \in \{0\}$

遞增遞減區間會被Critical Number所分割

故考慮區間$(-\infty, 0), (0, \infty)$

考慮$(-\infty, 0)$，以$-1$考慮$f'(-1)$，則$(-\infty, 0)$遞增。

由於要找到一個最小值$\beta$使得$\beta - \dfrac{2x-1}{x}$恆大於0

因此我們可以考慮$\beta$遞增至$x$趨近$\infty$時是否趨近於某個數字。

故考慮$\displaystyle \lim_{x\rightarrow \infty} \dfrac{2x-1}{x} = 2$

因此我們可以取$\beta = 2$，使得對於任意的$x>0$，恆滿足$\beta > \dfrac{2x-1}{x}$。



### Answer

$\beta = 2$



## Exercise 40

### Statement

找一最大值$\delta$，使得對任意$x>0$，恆滿足$\delta < e^{\frac{x+1}{x}}$



### Solution

考慮$\delta$為常數，故我們兩邊微分，得到$\dfrac{d}{dx} \delta < \dfrac{d}{dx} e^\frac{x+1}{x} \Rightarrow 0 < -\dfrac{e^\frac{x+1}{x}}{x^2}$

令$f'(x) = -\dfrac{e^\frac{x+1}{x}}{x^2}$，由於極值通常發生在臨界數，故我們考慮臨界數。

考慮$f'(x) = 0, x > 0$，則$x \in \varnothing$

考慮$f'(x) = D.N.E.,  x > 0$，則$x \in \varnothing$

可以發現沒有臨界數，故沒有極值。

考慮區間$(0, \infty)$，以$1$來考慮$f'(1)$，則$f'(1) < 0$，故區間$(0, \infty)$遞減。

因此我們可以說對任意的$x > 0$，其值必定會遞減至$\displaystyle \lim_{x\rightarrow \infty} f(x)$

因此我們考慮$\displaystyle \lim_{x\rightarrow \infty} f(x) = \lim_{x\rightarrow \infty} e^\frac{x+1}{x} = e^1 = e$

故我們可以取$\delta = e$，使得對任意的$x > 0$，均有$f(x) > e$。



## Exercise 41

### Statment

找一最小值$\alpha$，使得對任意$x>0$，恆滿足$(1+\dfrac{1}{x})^{x+\alpha} > e$

### Solution

$(1 + \dfrac{1}{x})^{x+\alpha} > e$

$(x+\alpha)\ln(1+\dfrac{1}{x}) > 1$

$(x+\alpha) > \dfrac{1}{\ln(1+\dfrac{1}{x})}$

$\alpha > \dfrac{1}{\ln(1+\dfrac{1}{x})} - x$

令$f(x) = \dfrac{1}{\ln(1+\dfrac{1}{x})} - x$

則我們確認$\displaystyle \lim_{x\rightarrow \infty} f(x) = \dfrac{1}{\ln(1+\dfrac{1}{x})}-x$

代換成$\displaystyle \lim_{x\rightarrow 0} f(x) = \lim_{x\rightarrow 0}(\dfrac{1}{\ln(1+x)}  - \dfrac{1}{x}) = \lim_{x\rightarrow 0}\dfrac{x-\ln(1+x)}{x\ln(1+x)}$

運用羅畢達法則，得到$\displaystyle \lim_{x\rightarrow 0} \dfrac{1-\dfrac{1}{1+x}}{\ln(1+x) + \dfrac{x}{1+x}} = \lim_{x\rightarrow 0} \dfrac{1+x-1}{(1+x)\ln(1+x)+x} = \lim_{x\rightarrow 0} \dfrac{x}{(1+x)\ln(1+x)+x}$

再次運用羅畢達法則，得到$\displaystyle \lim_{x\rightarrow 0} \dfrac{1}{\ln(1+x)+\dfrac{1+x}{1+x}+1} = \displaystyle \lim_{x\rightarrow 0} \dfrac{1}{\ln(1+x)+2} = \dfrac{1}{\ln(1)+2} = \dfrac{1}{2}$

因此$\displaystyle \lim_{x\rightarrow \infty} f(x) = \dfrac{1}{\ln(1+\dfrac{1}{x})}-x = \dfrac{1}{2}$

接著我們確認$f(x)$在$(0, \infty)$是否為遞增的，則考慮$f'(x)$是否大於0。

因此$f'(x) = \dfrac{1}{x^2\ln(1+\dfrac{1}{x})^2+x\ln(1+\dfrac{1}{x})^2} - 1$

以$1$考慮$f'(1)$，得到$f'(1) = \dfrac{1}{2\ln(2)^2} - 1 > 0$，故遞增

綜合上述，$f(x)$在$(0, \infty)$遞增，且$f(x)$在趨近於無限時$\displaystyle \lim_{x\rightarrow \infty} f(x) = \dfrac{1}{2}$，因此$\alpha$取$\dfrac{1}{2}$時可滿足$(1+\dfrac{1}{x})^{x+\alpha} > e$



