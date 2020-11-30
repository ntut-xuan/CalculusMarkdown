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



## Exercse 11

### Statement

試證明對任意的$x \in \mathbb{R}$，恆有$|\sin x| \le |x|$



## Exercise 13

### Statement

假設$f(x) = x^{\frac{1}{5}}$，$x \in [32, 33]$，試利用均值定理證明$2 < \sqrt[5]{33} < 2.0125$



## Exercise 15

### Statement

假設曲線$y = x^2$，$x \in (-1, 2)$，$A(-1, 1)$和$B(2 ,4)$為曲線上兩點，求曲線上一點$C$，使得$\Delta ABC$的面積最大。



## Exercise 17

### Statement

假設$f(x) = x^{\frac{2}{3}}$，試證明找不到$c \in [-1, 1]$，使得$f'(c) = 0$。並解釋為何不滿足洛爾定理。