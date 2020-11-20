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