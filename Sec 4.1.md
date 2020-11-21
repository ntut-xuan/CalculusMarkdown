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



## Exercise 3

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = x^2-2x+3,\ [-2, 3]$



### Solution

<img src="https://i.imgur.com/gEkAKOE.png" alt="image-20201120181503577"  />

觀察圖形，得最小值為$2$，最大值為$11$。



### Answer

最小值為$2$，最大值為$11$。



## Exercise 5

### Statement

利用圖形求函數的最大值與最小值。

$f(x) = \left\{\begin{array}\ x, & -1\le x \le 0 \\ 2-x, & \space\space\space0<x\le 2 \end{array}\right.$



### Solution

![image-20201120184849768](https://i.imgur.com/MNXoBJQ.png)

注意一下圈圈的點是不存在的，觀察一下圖形可得知最大值不存在、最小值為$-1$。



### Answer

最大值不存在、最小值為$-1$。



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



## Exercise 22

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = 4x^{\frac{1}{3}}+x^{\frac{4}{3}}$



## Exercise 24

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = x^4-2x^2+1$



## Exercise 26

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = \dfrac{x}{x^2+1}$



## Exercise 28

### Statement

利用一階導數檢定法，求函數遞增，遞減的區間與相對極值。

$f(x) = \dfrac{x^2-1}{x^2+1}$



## Exercise 30

### Statement

試證對任意$x>1$，$2\sqrt{x}>3-\dfrac{1}{x}$均成立。



## Exercise 32

### Statement

假設$f(x)=ax^2+bx+1$在$x=-1$時有相對極大值$2$，求$a$、$b$之值。



## Exercise 34

### Statement

假設函數$f(x) = ax^3+bx^2+cx+d$圖形在點$(0,1)$有相對極小值，在$(1, 2)$有相對極大值，求此函數$f$



## Exercise 36

### Statement

假設$f(x) = x^{\frac{1}{x^2}}$，求$f$在$(0, \infty)$上的最大值。



## Exercise 38

### Statement

試證如果$0<\alpha<1$，則對所有$x > -1$，恆滿足$\beta > \dfrac{2x-1}{x}$。



## Exercise 40

### Statement

找一最大值$\delta$，使得對任意$x>0$，恆滿足$\delta < e^{\frac{x+1}{x}}$



## Exercise 41

### Statment

找一最小值$\alpha$，使得對任意$x>0$，恆滿足$(1+\dfrac{1}{x})^{x+a} > e$

