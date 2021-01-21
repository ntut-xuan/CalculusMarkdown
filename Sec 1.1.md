# 洪輝霖微積分Practice Ch 1.1

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

假設$f(x) = 2x^3-x+1$，求

1. $f(2)$
2. $f(-1)$
3. $f(t+1)$
4. $f(x^2)$
5. $f(\dfrac{1}{x})$



### Solution 1.1

$f(2) = 2\times2^3-2+1=15$



### Solution 1.2

$f(-1) = 2\times(-1)^3+1+1 = 0$



### Solution 1.3

$f(t+1) = 2(t+1)^3-(t+1)+1 = 2(t^3+3t^2+3t+1)-t-1+1 = 2t^3+6t^2+5t+2$



### Solution 1.4

$f(x^2) = 2(x^2)^3 - x^2 + 1 = 2x^6-x^2+1$



### Solution 1.5

$f(\dfrac{1}{x}) = 2(\dfrac{1}{x})^3 - (\dfrac{1}{x}) + 1 = \dfrac{2}{x^3} - \dfrac{1}{x} + 1$



### Answer

$f(2) = 15$

$f(-1) = 0$

$f(t+1) = 2t^3+6t^2+5t+2$

$f(x^2) = 2x^6-x^2+1$

$f(\dfrac{1}{x}) = \dfrac{2}{x^3} - \dfrac{1}{x} + 1$



## Exercise 2

### Statement

假設$f(t) = \dfrac{2t^2}{\sqrt{t-1}}$，求

1. $f(2)$
2. $f(2x+1)$



### Solution 2.1

$f(2) = \dfrac{2\times 2^2}{\sqrt{2-1}} = 8$



### Solution 2.2

$f(2x+1) = \dfrac{2(2x+1)^2}{\sqrt{2x+1-1}} = \dfrac{2(4x^2+4x+1)}{\sqrt{2x}} = \dfrac{8x^2+8x+2}{\sqrt{2x}}$



### Answer

$f(2) = 8$

$f(2x+1) = \dfrac{8x^2+8x+2}{\sqrt{2x}}$



## Exercise 3

### Statement

假設$f(x) = \left\{\begin{array}\ x^2+1, & x\le 0 \\ \sqrt{x}, & x> 0\end{array}\right.$，求

1. $f(-2)$
2. $f(0)$
3. $f(1)$



### Solution 3.1

$-2 \le 0$，因此$f(-2) = (-2)^2+1=5$



### Solution 3.2

$0 \le 0$，因此$f(0) = 0^2+1 = 1$



### Solution 3.3

$1 > 0$，因此$f(1) = \sqrt{1} = 1$



### Answer

$f(-2) = 5$

$f(0) = 1$

$f(1) = 1$



## Exercise 4

### Statement

假設$f(x) = \left\{\begin{array}\ 1-2x, & x< -1 \\ 3x+2, & x \ge -1\end{array}\right.$，求

1. $f(-3)$
2. $f(-1)$
3. $f(0)$



### Solution 4.1

$-3 \le -1$，因此$f(-3) = 1-2\times(-3) = 7$



### Solution 4.2

$-1 \ge 0$，因此$f(-1) = 3\times(-1)+2 = -1$



### Solution 4.3

$0 \le -1$，因此$f(0) = 3\times0 +2 = 2$



### Answer

$f(-3) = 7$

$f(-1) = -1$

$f(0) = 2$



## Exercise 5

### Statement

若$f(x) = x^2-2x+k$且$f(1) = 3$，求$k$值



### Solution

$f(1) = 1^2-2\times1+k = -1+k$

又$f(1) = 3$，因此$-1+k=3$，$k=4$



### Answer

$k = 4$



## Exercise 6

### Statement

若$g(t) = |t-1|+k$且$g(-1) = 0$，求$k$值



### Solution

$g(-1) = |-1-1|+k = |-2|+k= 2+k$

又$g(-1) = 0$，因此$2+k=0$，$k=-2$



### Answer

$k = -2$



## Exercise 7

### Statement

用一張1200平方公分的厚紙板做成一個沒有上蓋的長方體紙盒，若紙盒的底部為一正方形且其邊長為$x$，試將紙盒體積表示為$x$的函數。



### Solution

已知底部為正方形，因此我們有一個正方形，四個相同的長方形組成的長方體。

因此我們不知道高度，故我們假設高度為$y$

所以我們可以列式，$x^2 + 4xy = 1200$，$y = \dfrac{1200-x^2}{4x}$

因此體積可以列成$x\times x\times y = x^2 \times \dfrac{1200-x^2}{4x} = \dfrac{1200x-x^3}{4}$

由於體積必須要是正的，邊長也必須是正的，故我們必須考慮$x > 0, \dfrac{1200x-x^3}{4} > 0$，也就是$x>0, 1200x-x^3>0$，可得$0 < x < 20\sqrt{3}$

### Answer

$\dfrac{1200x-2x^3}{4}$，$0 < x < 20\sqrt{3}$



## Exercise 8

### Statement

若一正方體的體積為$x$立方公分，將其表面積表示為$x$的函數



### Solution

設正方體邊長為$y$，已知$y\times y\times y=x$，故$y^3=x$，也就是$y = \sqrt[3]{x}$

表面積為$y\times y\times 6 = \sqrt[3]{x}\times \sqrt[3]{x}\times 6 = 6\sqrt[3]{x^2}$

體積必為正整數，因此$x > 0$



### Answer

$6\sqrt[3]{x^2}$，$x > 0$



## Exercise 9

### Statement

若一等腰直角三角形的面積為$x$平方公分，試將其周長表示為$x$的函數。



### Solution

面積為底乘高除以2，因此我們假設斜邊為$y$，則底邊為$\sqrt{y^2+y^2} = \sqrt{2}y$，高為$\sqrt{y^2-(\dfrac{\sqrt{2}}{2}y)^2} = \dfrac{\sqrt{2}y}{2}$

故$\dfrac{\sqrt{2}y\times \dfrac{\sqrt{2}y}{2}}{2} = x$，因此$y = \sqrt{2x}$

故周長為$2\sqrt{2x} + \sqrt{2}\sqrt{2x} = 2\sqrt{2x}+\sqrt{4x} = (2\sqrt{2}+2)\sqrt{x}$

面積為正整數，故$x > 0$



### Answer

$(2\sqrt{2}+2)\sqrt{x}$，$x > 0$



## Exercise 10

### Statement

若一正方體的表面積為$x$平方公分，將其邊長總和表示為$x$的函數。



### Solution

設邊長為$y$，表面積為$6y^2 = x$，，故$y = \sqrt{\dfrac{x}{6}}$

因此正方體有12個邊，故邊長總和為$12y = 12\sqrt{\dfrac{x}{6}} = \sqrt{24x}$

表面積為正整數，故$x > 0$



### Answer

$\sqrt{24x}$，$x > 0$



## Exercise 11

### Statement

一段繩子長100公分，剪成兩段，其中一段圍成正方形，另一段圍成圓形，若此正方形的邊長為$x$公分，試求此兩圖圖形的面積總和。



### Solution

已知一段圍成正方形，也就是繩子用掉了$4x$的長度，故圓形只剩下$100-4x$的長度可以圍。

我們可以使用圓周長公式，也就是$2r\pi$，得到$r = \dfrac{100-4x}{2\pi} = \dfrac{50-2x}{\pi}$

因此圓形面積為$r^2 = (\dfrac{50-2x}{\pi}) = \dfrac{2500-200x+4x^2}{\pi^2}$

正方形面積為$x^2$

故兩圖形的面積總和為$x^2 + \dfrac{2500-200x+4x^2}{\pi^2}$

邊長為正整數，故$x > 0$



### Answer

$x^2 + \dfrac{2500-200x+4x^2}{\pi^2}$，$x > 0$



## Exercise 12

### Statement

已知正三角形的周長為$x$公分，求此正三角形的面積。



### Solution

三角形的邊長為$\dfrac{x}{3}$，利用勾股定理可以求出高為$\sqrt{(\dfrac{x}{3})^2-(\dfrac{x}{6})^2} = \dfrac{\sqrt{3}x}{6}$

故面積為$\dfrac{\sqrt{3}x}{6}\times \dfrac{x}{3}\times \dfrac{1}{2} = \dfrac{\sqrt{3}x^2}{36}$



### Answer

$\dfrac{\sqrt{3}x^2}{36}$



## Exercise 13

### Statement

已知一圓形的周長為$x$公分，求此圓之面積。



### Solution

圓周長為$2r\pi$，因此$r = \dfrac{x}{2\pi}$

故圓面積為$r^2 = \dfrac{x^2}{4\pi}$



### Answer

$\dfrac{x^2}{4\pi}$



## Exercise 14

### Statement

假設一長方形的底邊在$x$軸上，上方兩頂點落在圓形$y = 1-x^2$上，若長方形的長為$t$，試將長方形的面積表為$t$的函數。



### Solution

兩頂點落在圓形上，故兩頂點會對稱$x=0$，且兩頂點距離為$t$。

故長方形的高度為$y(\dfrac{1}{2}t) = 1-\dfrac{1}{4}t^2 = \dfrac{4-t^2}{4}$

因此長方形的面積為$\dfrac{4-t^2}{4}\times t = \dfrac{4t-t^3}{4}$



### Answer

$\dfrac{4t-t^3}{4}$



## Exercise 15

### Statement

假設正四面體的邊長總和為$x$公分，試求其體積。



### Solution

正四面體有6條邊，故正四面體的邊長為$\dfrac{x}{6}$

因此正四面體的體積為$\dfrac{\sqrt{2}}{12}(\dfrac{x}{6})^3 = \dfrac{\sqrt{2}x^3}{2592}$



### Answer

$\dfrac{\sqrt{2}x^3}{2592}$



## Exercise 16

### Statement

求函數的定義域

$f(x) = \dfrac{2x+1}{x-1}$



### Solution

分式函數的分母不能為0，故$x - 1 \neq 0$，因此$x \neq 1$

因此函數的定義域為$x \neq 1$。



### Answer

$x \neq 1$



## Exercise 17

### Statement

求函數的定義域

$g(t)=\dfrac{t+1}{2t^2-t-1}$



### Solution

考慮分母不能為$0$，故$2t^2-t-1 \neq 0$

因此$t \neq \dfrac{-1}{2}, t \neq 1$

故定義域為$t \in (-\infty ,-\dfrac{1}{2}) \cup (-\dfrac{1}{2}, 1) \cup (1, \infty)$



### Answer

$t \in (-\infty ,-\dfrac{1}{2}) \cup (-\dfrac{1}{2}, 1) \cup (1, \infty)$



## Exercise 18

### Statement

求函數的定義域

$f(x) = \sqrt{9-x^2}$



### Solution

根號內必須要是非負整數，故我們考慮$9-x^2 \ge 0$，得到$-3 \le x \le 3$

因此$f$的定義域為$x \in [-3, 3]$



### Answer

$x \in [-3, 3]$



## Exercise 19

### Statement

求函數的定義域

$f(x) = \sqrt{x^2-2x-3}$



### Solution

根號內必須要是非負整數，故我們考慮$x^2-2x-3 \ge 0 \Rightarrow (x-3)(x+1)\ge 0 \Rightarrow -1 \le x, x\ge 3$

因此$f$的定義域為$x \in (-\infty, -1] \cup [3, \infty)$



### Answer

$x \in (-\infty, -1] \cup [3, \infty)$



## Exercise 20

### Statement

求函數的定義域

$f(x) = \sqrt{x-2} + \sqrt{4-x}$



### Solution

考慮根號內必須要是非負整數，因此考慮$x - 2 \ge 0$與$4-x \ge 0$

得到$x \ge 2$以及$x \le 4$

對兩者取交集，得到$2 \le x \le 4$

因此$f$的定義域為$x \in [2, 4]$



### Answer

$x \in [2, 4]$



## Exercise 21

### Statement

求函數的定義域

$f(x) = \dfrac{\sqrt{x-1}}{x^2-x-6}$



### Solution

考慮以下兩點並取交集

1. 根號內必須要是非負整數，因此$x - 1 \ge 0$
2. 分母不能為0，因此$x^2-x-6 \neq 0$

所以我們得到

1. $x \ge 1$
2. $x \neq 3, x \neq -2$

對兩點取交集，得到$f$的定義域為$x \in [1, 3) \cup (3, \infty)$



### Answer

$x \in [1, 3) \cup (3, \infty)$



## Exercise 22

### Statement

畫出下列函數圖形

$g(x) = \sqrt{x-2}$



### Solution

考慮函數的定義域，根號內必須要是非負整數，因此函數的定義域為$x \ge 2$

接著我們可以開始描點，$g(6) = 2$，$g(11) = 3$，$g(18) = 4$，$g(27) = 5$，$g(38) = 6$....

將描點的所有點連接起來，即可得到大略的函數圖形。



<img src="https://i.imgur.com/2MW9i06.png" alt="image-20210122002927003" style="zoom:67%;" />



### Answer

請見Solution



## Exercise 23

### Statment

畫出下列函數圖形

$h(x) = x^2-4x+3$



### Solution

考慮函數的定義域，定義域為$x \in \mathbb{R}$

接著我們可以開始描點

$h(-5) = 48, h(-4) = 35, h(-3) = 24, h(-2)=15, h(-1)=8$

$h(0)=3, h(1)=0, h(2)=-1, h(3)=0, h(4)=3, h(5)=8$

將描點的所有點連接起來，即可得到大略的函數圖形。

<img src="https://i.imgur.com/65VIlcn.png" alt="image-20210122003414458" style="zoom:67%;" />

### Answer

請見Solution



## Exercise 24

### Statement

畫出下列函數圖形

$f(x)=\dfrac{1}{2}x^2+1$



### Solution

考慮函數的定義域，定義域為$x \in \mathbb{R}$

接著我們可以開始描點

$f(4) = 9, f(2)=3, f(0)=1, f(-2) = 3, f(-4)=9$

將描點的所有點連接起來，即可得到大略的函數圖形。

<img src="https://i.imgur.com/pBOxjfD.png" alt="image-20210122003647449" style="zoom:67%;" />

### Answer

請見Solution



## Exercise 25

### Statement

畫出下列函數圖形

$f(x)=|x|+1$



### Solution

考慮函數的定義域，定義域為$x \in \mathbb{R}$

接著我們可以開始描點

$f(-2) = 3, f(-1)=2, f(0)=0, f(1)=2, f(2)=3$

將描點的所有點連接起來，即可得到大略的函數圖形。

<img src="https://i.imgur.com/QS6Rwhx.png" alt="image-20210122003915924" style="zoom:67%;" />

### Answer

請見Solution



## Exercise 26

### Statement

畫出下列函數圖形

$f(x)=|x^2-1|$



### Solution

考慮函數的定義域，定義域為$x \in \mathbb{R}$

接著我們可以開始描點

$f(-2)=3, f(-1)=0, f(0)=1, f(1)=0, f(2)=3$

將描點的所有點連接起來，即可得到大略的函數圖形。



![image-20210122010814946](https://i.imgur.com/qml8qN9.png)

### Answer

請見Solution



## Exercise 27

### Statement

畫出下列函數圖形

$f(x)=x^2-2|x|+1$



### Solution

考慮函數的定義域，定義域為$x \in \mathbb{R}$

接著我們可以開始描點

$f(-2)=1, f(-1)=0, f(0)=1, f(1)=0, f(2)=1$

將描點的所有點連接起來，即可得到大略的函數圖形。



<img src="https://i.imgur.com/pJTUM3s.png" alt="image-20210122004429365" style="zoom:67%;" />

### Answer

請見Solution



## Exercise 28

### Statement

畫出下列函數圖形

$f(t) = \dfrac{|t-2|}{t-2}$



### Solution

考慮函數的定義域，定義域為$t \in (-\infty, 2) \cup (2, \infty)$

若$t$小於2，則$f(t)=\dfrac{-(t-2)}{t-2} = -1$

若$t$大於2，則$f(t) = \dfrac{t-2}{t-2} = 1$

因此我們可以畫出圖形

<img src="https://i.imgur.com/vIIFZvm.png" alt="image-20210122004747419" style="zoom:67%;" />

### Answer

請見Solution



## Exercise 29

### Statement

畫出下列函數圖形

$f(x) = \left\{\begin{array}\ -x+1, & x\le 1 \\ x^2-2, & x > 1\end{array}\right.$



### Solution

這是兩個不同的函數組成的分段函數，因此我們可以分段處理

兩個函數均為多項式，因此定義域均為$x \in \mathbb{R}$

我們可以開始描點並畫出函數

第一個函數 $f(-3) = 4, f(-2)=3,f(-1) = 2, f(0) = 1, f(1) = 0$

第二個函數$f(1.0000001) \approx -1, f(2)=2, f(3)=7$

因此我們可以畫出圖形



<img src="https://i.imgur.com/7lGtNDu.png" alt="image-20210122010047530" style="zoom:67%;" />	



### Answer

請見Solution



## Exercise 30

### Statement

畫出下列函數圖形

$f(x) = \left\{\begin{array}\ -x-1, & x < -1 \\ 0, & -1 \le x\le1 \\ x+2, & x > 1\end{array}\right.$



### Solution

這是三個不同的函數組成的分段函數，因此我們可以分段處理

第一與第三個函數為多項式、第二個函數為常數函數，因此定義域為$x \in \mathbb{R}$

我們可以開始描點並畫出函數

第一個函數 $f(-3) = 2, f(-2)=1,f(-1) = 0, f(0) = 0, f(1) = 0$

第二個函數$f(1.0000001) \approx 3, f(2)=4, f(3)=5$

因此我們可以畫出圖形



<img src="https://i.imgur.com/aY5q9Mc.png" alt="image-20210122010427834" style="zoom:67%;" />

### Answer

請見Solution



## Exercise 31

### Statement

畫出下列函數圖形

$f(x) = ||x^2-1|-2|$



### Solution

考慮函數的定義域，定義域為$x \in \mathbb{R}$

接著我們可以開始描點

$f(-2)=1, f(-1)=0, f(0)=1, f(1)=0, f(2)=1$

將描點的所有點連接起來，即可得到大略的函數圖形。



![image-20210122011023752](https://i.imgur.com/6vpAHZc.png)

### Answer

請見Solution



## Exercise 32

### Statement

假設$f(x)=\sqrt{x+2}$、$g(x)=2x+1$、$h(x)=x^2-1$，求

1. $(g \circ f)(x)$
2. $(f\circ h)(x)$
3. $(g \circ h)(2)$
4. $g(g(1))$



### Solution 32.1

$(g\circ f)(x) = g(f(x))=2f(x)+1=2\sqrt{x+2}+1$



### Solution 32.2

$(f \circ h)(x) = \sqrt{h(x)+2} = \sqrt{x^2-1+2} = \sqrt{x^2+1}$



### Solution 32.3

$(g \circ h)(2) = 2h(2)+1 = 2(3)+1 = 7$



### Solution 32.4

$g(g(1)) = g(3) = 7$



### Answer

1. $(g\circ f)(x) =2\sqrt{x+2}+1$
2. $(f \circ h)(x) = \sqrt{x^2+1}$
3. $(g \circ h)(2) = 7$
4. $g(g(1)) = 7$



## Exercise 33

### Statement

假設$f(x-1)=2x+3$，求

1. $f(0)$
2. $f(x)$



### Solution 33.1

我們可以令$x = 1$，這樣就能使得$f(x-1) = f(0)$

因此$f(0)=2+3 = 5$



### Solution 33.2

我們可以令$x-1$變成$x$，也就是把$x$放入$x+1$

因此$f(x) = 2(x+1)+3 = 2x+2+3 =2x+5$



### Answer

1. $5$
2. $2x+5$



## Exercise 34

### Statement

假設$f(x) = x-1$且$g(x)=2x+3$，求一函數$h(x)$使得$g(x) = f(h(x))$



### Solution

$f(h(x)) = h(x)-1$

我們要使得$f(h(x)) = g(x)$，也就是令$h(x)-1 = 2x+3$

因此$h(x) = 2x+4$



### Answer

$h(x) = 2x+4$



## Exercise 35

### Statement

假設$f(x) = \dfrac{2}{x+\dfrac{2}{x+\dfrac{2}{x+\dfrac{2}{x+...}}}}$，求$f(1)$



### Solution

令$f(x) = \dfrac{2}{x+f(x)}$，因此$f(1) = \dfrac{2}{1+f(1)} \Rightarrow (f(1))^2+f(1)-2=0$

令$u = f(1)$，則$u^2+u-2=0$，因此$u = -2$或$u = 1$

但$f(x)$是分式，且必定大於0，因此$u=-2$的情況不存在，故$f(1) = 1$



### Answer

$f(1) = 1$