# 洪揮霖微積分Practice Ch4.2

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

假設$f(x) = 4x^3+4x+1$，試證$f(x) = 0$洽有一個實數解。



### Solution

先證明存在性，使用中間值定理，考慮$f(0) = 1$，且$f(-1) = -7$

因此根存在於$(0, 1)$之間，故根必定存在。



再證明唯一性，若存在兩個根，使得$x_1 \neq x_2$，且$f(x_1) = f(x_2) = 0$，$f$在$[x_1, x_2]$連續，則：

根據洛爾定理，存在一點$c \in (x_1, x_2), x_1 < x_2$，則$f'(c) = 0$

$f'(x) = 12x^2+4$，但$f'(x)$對於所有的$x$，$f'(x) > 0$

矛盾，故$f(x) = 0$恰有一個實數解。



### Answer

See Solution.



## Exercise 2

### Statement

甲乙兩人賽跑，起跑點同時出發且同時抵達終點，中間的過程互有快慢。試問至少存在某個時刻，兩人具有相同加速度。



### Solution

假設$f(x) = $甲的位置 - 乙的位置，且$f'(x) =$ 甲的速度 - 乙的速度。

由於甲乙兩人同時出發且同時到達，因此我們可以確定在某兩個時間點$x_1, x_2$，$f(x_1) = f(x_2)$。

因此我們可以使用羅勒定理，存在一個$c$，使得$f'(c) = 0$

也就至少存在某個時刻$c$，使得甲乙兩人加速度相同。



### Answer

See solution.



## Exercise 3

### Statement

試求所有滿足均值定理的$c$值，若沒有，請敘述原因。

$f(x) = x^2-x+3$，$x \in [-2, 2]$



### Solution

從函數上可以知道在$[-2, 2]$是連續的，且$(-2, 2)$是可微的。

考慮$f'(x) = 2x-1$，則我們使用MVT，找出所有的$f'(c) = \dfrac{f(b)-f(a)}{b-a}$

令$b = -2, a = 2$，則$f(-2) = 4+2+3=9$，$f(2) = 4-2+3=5$

因此考慮找出所有的$f'(c) = \dfrac{f(-2)-f(2)}{-2-2} = \dfrac{4}{-4} = -1$

考慮$2c-1=-1$，得到$c = 0$



### Answer

在$c = 0$時，滿足均值定理。



## Exercise 4

### Statement

試求所有滿足均值定理的$c$值，若沒有，請敘述原因。

$f(x) = x^\frac{2}{3}, x \in [-1, 8]$



### Solution

考慮$x = 0$的連續性與可微性。

先考慮連續性。

$\displaystyle \lim_{x\rightarrow 0^-} x^\frac{2}{3} = \lim_{x\rightarrow 0^+} x^\frac{2}{3} = 0$

根據極限定義，得到$\displaystyle \lim_{x\rightarrow 0} x^\frac{2}{3} = 0$

考慮$f(0) = 0$，則$\displaystyle \lim_{x\rightarrow 0} x^\frac{2}{3} = f(0)$，因此$f$在$x=0$時連續。



再考慮可微性。

$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)-f(0)}{x-0} = \lim_{x\rightarrow 0^+} \dfrac{x^\frac{2}{3}}{x} = \lim_{x\rightarrow 0^+} x^{-\frac{1}{3}} = D.N.E.$

故$x=0$時不可微。



根據$MVT$，若$[a, b]$均連續，$(a, b)$均可微，則存在一點$c$使得$f'(c) = \dfrac{f(b)-f(a)}{b-a}$

但在$(a, b)$時，$x=0$不可微，故不滿足均值定理，因此找不到滿足均值定理的$c$點。



### Answer

See solution.



## Exercise 5

### Statement

試求所有滿足均值定理的$c$值，若沒有，請敘述原因。

$f(x) = x^3-x^2+3$，$x \in [-3, 3]$



### Solution

從函數可以知道在$[-3, 3]$是連續的，且$(-3, 3)$是可微的。

考慮$f'(x) = 3x^2-2x$，則我們使用MVT，找出所有的$f'(c) = \dfrac{f(b)-f(a)}{b-a}$

令$b = -3, a = 3$，則$f(-3) = -27 - 9 + 3 = -33$，$f(3) = 27-9+3=21$

因此考慮找出所有的$f'(c) = \dfrac{-33-21}{-3-3} = \dfrac{-54}{-6} = 9$

考慮$3c^2-2c = 9$，因此$3c^2-2c-9 = 0$，得到$c = \dfrac{1\pm2\sqrt{7}}{3}$



### Answer

$c = \dfrac{1\pm2\sqrt{7}}{3}$時，滿足均值定理。



## Exercise 6

### Statement

試求所有滿足均值定理的$c$值，若沒有，請敘述原因。

$f(x) = \dfrac{x}{x+2}, x \in [0, 3]$



### Solution

考慮定義域，得到$x \neq -2$時均有定義，不在區間$[0, 3]$內，故在區間內均連續。

$f'(x) = \dfrac{2}{(x+2)^2}$，在$x \neq -2$時均可微。

因此在區間$[0, 3]$內均連續，在$(0, 3)$內均可微，故滿足均值定理。

考慮$f(0) = 0, f(3) = \dfrac{3}{5}$，則我們考慮$c$，使得$f'(c) = \dfrac{0-\dfrac{3}{5}}{0-3} = \dfrac{1}{5}$

得到$c = \pm\sqrt{10}-2$，其中$-\sqrt{10}-2$ 不合，因為不在區間內。



### Answer

$c =\sqrt{10}-2$



## Exercise 7

### Statement

試求所有滿足均值定理的$c$值，若沒有，請敘述原因。

$f(x) = \left\{\begin{array}\ x^2, & 0\le x <1 \\ 2-x, & 1 \le x \le 2\end{array}\right.$



### Solution

從函數上可以知道在$0 \le x < 1$時，$x^2$連續且可微，且在$1\le x \le 2$時，$2-x$連續且可微。

因此我們只需要考慮在接點是否連續且可微即可。

先考慮在$x=1$的連續性。

$\displaystyle \lim_{x\rightarrow 1^+} f(x) = \lim_{x\rightarrow 1^+}(2-x)= 2-1 = 1$

$\displaystyle \lim_{x\rightarrow 1^-} f(x) = \lim_{x\rightarrow 1^-} x^2 = 1^2 = 1$

根據極限定義得知$\displaystyle \lim_{x\rightarrow 1} f(x) = 1$

又考慮$f(1) = 2-1= 1$，故$\displaystyle \lim_{x\rightarrow 1}f(x) = f(1)$，故$f(x)$在$x=1$時連續。

再考慮$x=1$的可微性。

考慮$x=1$的兩邊導數。

$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{f(x)-f(1)}{x-1} = \lim_{x\rightarrow 1^+} \dfrac{2-x-1}{x-1} = \lim_{x\rightarrow 1^+}\dfrac{1-x}{x-1} = \lim_{x\rightarrow 1^+}-1 = -1$

$\displaystyle \lim_{x\rightarrow 1^-} \dfrac{f(x)-f(1)}{x-1} = \lim_{x\rightarrow 1^-}\dfrac{x^2-1}{x-1} = \lim_{x\rightarrow 1^-} x+1 = 1+1 = 2$

兩邊導數不同，故不可微。

因此沒有任何的$c$滿足均值定理，因為$f$在$(0, 2)$的可微性不成立。



### Answer

沒有任何的$c$滿足均值定理，因為$f$在$(0, 2)$的可微性不成立。



## Exercise 9

### Statement

試證明對任意的$x > 0$，恆有$\sin x < x$



### Solution

考慮$\sin x - x < 0 $，則令$f(x) = \sin x - x$

$f'(x) = \cos(x) - 1$

考慮$Critical Point$發生在$x \in 2n\pi, n \in \mathbb{Z}$，又每$2\pi$一個循環 ($\cos 2\pi = \cos 0$)

所以若$(0, 2\pi)$遞減，則$(2\pi, 4\pi)$遞減、($4\pi, 6\pi$)遞減...，可得$(0, \infty)$遞減。

因此考慮$(0, 2\pi)$區間，以$\dfrac{\pi}{2}$考慮$f'(\dfrac{\pi}{2}) < 0$，故遞減。

考慮在點$x=0$上的極值，得到$f(0)=0-0=0$

故對於任意的$x>0$，$f(x)$恆小於$0$，故$\sin x < x$成立。



### Answer

See solution.



## Exercise 10

### Statement

試證明對任意的$x \in \mathbb{R}$，恆有$|\sin x| \le |x|$



### Solution

考慮$|\sin x| - |x| \le 0$，令$f(x) = |\sin x| - |x|$

$f'(x) = \dfrac{\sin x \cos x}{|\sin x|} - \dfrac{x}{|x|}$

考慮$f'(x) = 0$，則沒有任何一個$x$能夠滿足，故$x \in \varnothing$

考慮$f'(x) = D.N.E.$，則$x \in n\pi, n\in \mathbb{Z}$

因此$Critical Point$發生在$x \in n\pi, n\in\mathbb{Z}$，又$2\pi$一個循環$(\sin2\pi = \sin 0)$

所以我們考慮兩個區間$(-2\pi, -\pi), (-\pi, 0), (0, \pi), (\pi, 2\pi)$的遞增遞減情況

考慮$(-2\pi, -\pi)$，以$-\dfrac{3\pi}{2}$考慮$f'(-\dfrac{3\pi}{2}) > 0$，故$(-2\pi, -\pi)$遞增。

考慮$(-\pi, 0)$，以$-\dfrac{\pi}{2}$考慮$f'(-\dfrac{\pi}{2})>0$，故$(-\pi, 0)$遞增。

考慮$(0, \pi)$，以$\dfrac{\pi}{2}$考慮$f'(\dfrac{\pi}{2}) < 0$，故$(0, \pi)$遞減。

考慮$(\pi, 2)$，以$\dfrac{3\pi}{2}$考慮$f'(\dfrac{3\pi}{2}) < 0$，故$(\pi, 2\pi)$遞減。

故極值發生在$x=0$上，考慮$f(0) = |0|-|0| = 0$

因此$|\sin x|-|x| \le 0$成立，故對任意的$x \in \mathbb{R}$，恆有$|\sin x| \le |x|$。



### Answer

See solution.



## Exercise 12

### Statement

假設對任意的$x \in \mathbb{R}$，恆有$2 \le f'(x) \le 4$ 且 $f(1) = 5$，求$f(6)$可能的最大值和最小值。



### Solution

利用均值定理，考慮$f(1)-f(6) = f'(c)(1-6), \quad 2\le c\le 4$

已知$f(1)=5$，則$f(6) = -f'(c)(1-6)+f(1) = 5f'(c)+5$

已知對任意的$x \in \mathbb{R}$，$2 \le f'(x) \le 4$

我們考慮$f'(x)=2$，得到$f(6) = 5\times2+5 = 15$

考慮$f'(x) = 4$，得到$f(6) = 5\times 4 + 5 = 25$

因此最大值為$25$，最小值為$15$。



### Answer

最大值為$25$，最小值為$15$。



## Exercise 13

### Statement

假設$f(x) = x^{\frac{1}{5}}$，$x \in [32, 33]$，試利用均值定理證明$2 < \sqrt[5]{33} < 2.0125$



### Solution

$f(x) = x^\frac{1}{5},\ 32\le x\le 33$

根據$MVT$，可以知道$2 \le \sqrt[5]{33} \le 2.0125 \Rightarrow 2 \le \sqrt[5]{33}\le 2 + \dfrac{1}{80}$

又根據$MVT$，$f(33)-f(32)=f'(t)(33-32),\quad 32\le t\le 33$

所以$f(33) = f'(t) + f(32) = f'(t) + 2,\quad 32 \le t \le 33$

$f'(x) = \dfrac{1}{5}x^\frac{-4}{5} = \dfrac{1}{5\sqrt[5]{x^4}}$，$f''(x) \dfrac{-4}{25}x^\frac{-9}{5}$，可知$f'(x)$在$(0, \infty)$區間遞減，$f(x)$在$(0, \infty)$遞增。

考慮$t = 32$，$f'(32) = \dfrac{1}{5\sqrt[5]{32^4}} = \dfrac{1}{80}$，且在$f'(x)$函數中，若$x>0$則$f'(x) > 0$

所以$0 < f'(33) < f'(32)$，故$f'(t)$在$32 \le t \le 33$的最大值為$\dfrac{1}{80}$

所以可以知道$2 +f'(33) \le f(33) \le 2 + \dfrac{1}{80}$，又$f'(33) > 0$，故$2 < f(33) < 2 + \dfrac{1}{80}$



### Answer

See solution.



## Exercise 15

### Statement

假設曲線$y = x^2$，$x \in (-1, 2)$，$A(-1, 1)$和$B(2 ,4)$為曲線上兩點，求曲線上一點$C$，使得$\Delta ABC$的面積最大。



### Solution

令$m_{AB} = \dfrac{1-4}{-1-2} = 1$

利用均值定理，找出斜率與$m_{AB} = 1$相同的點。

令$f(x) = x^2$，則$f'(x) = 2x$

因此考慮$f'(c) = 1$，也就是$2c = 1$的點，得到$c = \dfrac{1}{2}$

因此我們可以令$C = (\dfrac{1}{2}, \dfrac{1}{4})$，使得$\Delta ABC$的面積最大。



### Answer

$C = (\dfrac{1}{2}, \dfrac{1}{4})$



## Exercise 17

### Statement

假設$f(x) = x^{\frac{2}{3}}$，試證明找不到$c \in [-1, 1]$，使得$f'(c) = 0$。並解釋為何不滿足洛爾定理。



### Solution

考慮$x=0$時

$\displaystyle \lim_{x\rightarrow 0^+} x^\frac{2}{3} = \lim_{x\rightarrow 0^-} x^\frac{2}{3} = 0$，利用極限定義得到$\displaystyle \lim_{x\rightarrow 0} x^\frac{2}{3} = 0$

又$f(0) = 0$，所以$\displaystyle \lim_{x\rightarrow 0} x^\frac{2}{3} = f(0)$，利用連續定義得知$f$在$x=0$時連續。

接著考慮可微性

考慮$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)-f(0)}{x-0} = \lim_{x\rightarrow 0^+} \dfrac{x^\frac{2}{3}}{x} = \lim_{x\rightarrow 0} x^{-\frac{1}{3}} = D.N.E.$

故在$x=0$時不可微。

洛爾定理要求$f(a)=f(b)$，且f在$[a, b]$時連續，且在$(a, b)$可微時能夠找到一個$c$使得$f'(c) = 0$。

但在區間$[-1, 1]$時，$x=0$時不可微，故不滿足洛爾定理。