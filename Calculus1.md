# 微積分Practice Ch1

###### tags: `微積分題目紀錄`

## Sec 1.1

### Exercise 21

#### Statement

Evaluate the difference quotient for the given function.
Simplify your answer.

$f(x) = 4+3x-x^2$, 	$\dfrac{f(3+h)-f(3)}{h}$



#### Solution

$f(3+h) = 4+3(3+h)-(3+h)^2$

$f(3) = 4+3\times 3 - 3^2 = 4$

$\dfrac{4+3(3+h)-(3+h)^2-4}{h}$

$= \dfrac{4+9+3h-9-6h-h^2-4}{h}$

$=\dfrac{-3h-h^2}{h} = -3-h$



#### Answer

$\dfrac{f(3+h)-f(3)}{h} = -3-h$



### Exercise 25



#### Statement

Find the domain of the function.

$f(x) = \dfrac{x+4}{x^2-9}$



#### Solution

$f(x) = \dfrac{x+4}{(x-3)(x+3)}$

考慮定義域分母不能為0，因此$x \neq 3,\ x \neq -3$

$\therefore D \in (-\infty, -3) \cup (-3, 3) \cup (3, \infty)$



#### Answer

$D \in (-\infty, -3) \cup (-3, 3) \cup (3, \infty)$



### Exercise 26

#### Statement

Find the domain of the function.

$f(x) = \dfrac{2x^3-5}{x^2+x-6}$



#### Solution

$f(x) = \dfrac{2x^3-5}{x^2+x-6} = \dfrac{2x^3-5}{(x+3)(x-2)}$

考慮定義域分母不能為0，因此$x \neq -3,\ x \neq 2$

$\therefore D \in (-\infty, -3) \cup (-3, 2) \cup (2, \infty)$



#### Answer

$D \in (-\infty, -3) \cup (-3, 2) \cup (2, \infty)$



### Exercise 28

#### Statement

Find the domain of the function.

$g(t) = \sqrt{3-t} - \sqrt{2+t}$



#### Solution

考慮根號內大於等於0，寫出不等式。

$\left\{ \begin{array}\ 3-t\ge0 \\ 2+t\ge0 \end{array}\right.$

可以得到

$\left\{\begin{array}\ t \le 3 \\ t \ge -2\end{array}\right.$

因此，可以得到 $t \in [-2, 3]$



#### Answer

$t \in [-2, 3]$



### Exercise 29

#### Statement

Find the domain of the function.

$h(x) = \dfrac{1}{\sqrt[4]{x^2-5x}}$



#### Answer

考慮定義域，根號內不能小於0，因此

$x^2-5x\ge 0$

$\iff x(x-5)\ge 0$

$\therefore x \ge 5, x \le 0$

因此，$D \in (-\infty,0] \cup [5, \infty)$



#### Solution

$D \in (-\infty,0] \cup [5, \infty)$



### Exercise 34

#### Statement

Find the domain and sketch the graph of the function.

$H(t) = \dfrac{4-t^2}{2-t}$



#### Solution

$H(t) = \dfrac{4-t^2}{2-t}$

考慮定義域，分母不能為0。

因此 $t \neq 2$，$D \in (-\infty, 2) \cup (2, \infty)$

圖表請見以下。



#### Answer

$D \in (-\infty, 2) \cup (2, \infty)$

![image-20200924022301199](https://i.imgur.com/WMLOx38.png)



### Exercise 37

#### Statement

Find the domain and sketch the graph of the function.

$G(x) = \dfrac{3x+|x|}{x}$



#### Solution

考慮定義域，$x \neq 0$。

因此$D = (-\infty, 0) \cup (0, \infty)$

圖表請見以下。



#### Answer

$D = (-\infty, 0) \cup (0, \infty)$

![image-20200924022545045](https://i.imgur.com/LVmbEsm.png)



### Exercise 38

#### Statement

Find the domain and sketch the graph of the function.

$g(x) = |x| - x$



#### Solution

這是一個多項式，因此$D \in \mathbb{R}$

圖表請見下圖。



#### Answer

$D \in \mathbb{R}$

![image-20200924022825037](https://i.imgur.com/cUybSj2.png)



###　Exercise 39

#### Statement

Find the domain and sketch the graph of the function.

$f(x) = \left\{\begin{array}\ x+2 & \rm{if}\ x < 0 \\ 1-x & \rm{if}\ x \ge 0\end{array}\right.$



#### Solution

這是一個多項式，因此$D \in \mathbb{R}$

圖表請見下圖。



#### Answer

$D \in \mathbb{R}$

![image-20200924023456781](https://i.imgur.com/Y8DMrt9.png)



### Exercise 63

#### Statement

Determine whether $f$ is even, odd, or neither. If you
have a graphing calculator, use it to check your answer visually.

$f(x) = 1+3x^2-x^4$



#### Solution

If $f$ is odd, then $-f(x) = f(-x)$

Verify:

$1+3x^2-x^4$

$= 1+(3(-x)^2)-(-x)^4$

$= 1+3x^2-x^4 \neq -1-3x^2+x^4$

s.t. $f$ isn't odd.



If $f$ is even, then $f(x) = f(-x)$

Verify:

$1+3x^2-x^4$

$f(-x) = 1+(3(-x)^2)-(-x)^4$

$= 1+3x^2-x^4 = 1+3x^2-x^4$

s.t. $f$ is even.



#### Answer

$f(x)$ is even.

![image-20200924024128697](https://i.imgur.com/WSeBwwk.png)



## Sec 1.2

### Exercise 19

#### Statement

The graph of $f(x)$ is given. Match each equation with its graph and give reasons for your choices.

$(a)\ y = f(x-4)$

$(b)\ y = f(x)+3$

$(c)\ y = \dfrac{1}{3}f(x)$

$(d)\ y = -f(x+4)$

$(e)\ y = 2f(x+6)$



![image-20200924223804363](https://i.imgur.com/I1jEUdl.png)



#### Solution

$y=af(x+c)+k$代表函數的座標從$(-c, k)$開始，且每個曲線上的值乘以$a$倍。

因此$(1) = (b), (2) = (e), (3) = (a), (4) = (c), (5) = (d)$



#### Answer

$a\rightarrow 3,\ b \rightarrow 1,\ c \rightarrow 4,\ d \rightarrow 5,\ e \rightarrow 2$



### Exercise 41

#### Statement

Find the functions (a) $f \circ g$, (b) $g \circ f$, (c) $f \circ f$, and (d) $g \circ g$ and their domains.

$f(x) = 1 - 3x$, $g(x) = \cos x$



#### Solution

$f(g(x)) = 1-3(\cos x)$, $\cos$的定義域為$\mathbb{R}$, 因此$D \in \mathbb{R}$

$g(f(x)) = \cos(1-3x)$, $\cos$的定義域為$\mathbb{R}$, 因此$D \in \mathbb{R}$

$f(f(x)) = 1-3(1-3x) = 1-3+9x = 9x-2$, 這是一個多項式，因此$D \in \mathbb{R}$

$g(g(x)) = \cos(\cos x)$，$\cos$的定義域為$\mathbb{R}$, 因此$D \in \mathbb{R}$



#### Answer

$f(g(x)) = 1-3(\cos x)$, $D \in \mathbb{R}$

$g(f(x)) = \cos(1-3x)$, $D \in \mathbb{R}$

$f(f(x)) = 9x-2$, $D \in \mathbb{R}$

$g(g(x)) = \cos(\cos x)$, $D \in \mathbb{R}$



### Exercise 42

#### Statement

Find the functions (a) $f \circ g$, (b) $g \circ f$, (c) $f \circ f$, and (d) $g \circ g$ and their domains.

$f(x) = \sqrt{x},\ g(x) = \sqrt[3]{1-x}$



#### Solution

$f(g(x)) = \sqrt{\sqrt[3]{1-x}}$，$g(x)$的定義域為$\mathbb{R}$，且$f(x)$的定義域為$[0, \infty)$

因此為了讓$f(x)$內根號的值為正數，$g(x) \ge 0$，因此$f(g(x))$的定義域為$D \in (-\infty, 1]$



$g(f(x)) = \sqrt[3]{1-\sqrt{x}}$，$g(x)$的定義域為$\mathbb{R}$，且$f(x)$的定義域為$[0, \infty)$

因此為了讓$f(x)$內根號的值為非負整數，$x \ge 0$，因此$g(f(x))$的定義域為$D \in [0, \infty)$



$f(f(x)) = \sqrt{\sqrt{x}}$，我們只需要讓最內部的根號的值為非負整數，那麼也會符合外層根號的要求。

因此當$x \ge 0$的時候內部根號為非負整數，因此$f(f(x))$的定義域為$D \in [0, \infty)$



$g(g(x)) = \sqrt[3]{1-\sqrt[3]{1-x}}$，兩個函數的定義域都是$\mathbb{R}$，因此$D \in \mathbb{R}$



#### Answer

$f(g(x)) = \sqrt{\sqrt[3]{1-x}}$, $D \in (-\infty, 1]$

$g(f(x)) = \sqrt[3]{1-\sqrt{x}}$, $D \in [0, \infty)$

$f(f(x)) = \sqrt{\sqrt{x}}$, $D \in [0, \infty)$

$g(g(x)) = \sqrt[3]{1-\sqrt[3]{1-x}}$, $D \in \mathbb{R}$



### Exercise 43

#### Statement

Find the functions (a) $f \circ g$, (b) $g \circ f$, (c) $f \circ f$, and (d) $g \circ g$ and their domains.

$f(x) = x + \dfrac{1}{x}$, $g(x) = \dfrac{x+1}{x+2}$



#### Solution

$f(g(x)) = f(\dfrac{x+1}{x+2}) = \dfrac{x+1}{x+2} + \dfrac{x+2}{x+1}$

必須要注意一下分母的部分，$x + 2 \neq 0$, $x + 1 \neq 0$

因此$x \neq -2, x \neq -1$，$D \in (-\infty, -2) \cup (-2, -1) \cup (-1, \infty)$



$g(f(x)) = g(x+\dfrac{1}{x}) = \dfrac{x+\dfrac{1}{x}+1}{x+\dfrac{1}{x}+2} = \dfrac{x^2+x+1}{x^2+2x+1} = \dfrac{x^2+x+1}{(x+1)^2}$

必須要注意一下分母的部分，$x+1 \neq 0, x \neq 0$

因此$x \neq -1$，$D \in (-\infty, -1) \cup (-1, 0) \cup (0, \infty)$



$f(f(x)) = f(x+\dfrac{1}{x}) = x+\dfrac{1}{x} + \dfrac{1}{x+\dfrac{1}{x}} = x + \dfrac{1}{x}+\dfrac{x}{x^2+1}$

必須要注意一下分母的部分，$x \neq 0, x^2+1\neq 0$

因此$x \neq 0$，$D \in (-\infty, 0) \cup (0, \infty)$



$g(g(x)) = g(\dfrac{x+1}{x+2}) = \dfrac{\dfrac{x+1}{x+2}+1}{\dfrac{x+1}{x+2}+2} = \dfrac{x+1+x+2}{x+1+2(x+2)} = \dfrac{2x+3}{3x+5}$

必須要注意一下分母的部分，$3x + 5 \neq 0, x + 2 \neq 0$

因此$x \neq \dfrac{-5}{3}, x \neq -2$，$D \in (-\infty, \dfrac{-5}{3}) \cup (\dfrac{-5}{3}, 2) \cup (2, \infty)$



#### Answer

$f(g(x)) = \dfrac{x+1}{x+2} + \dfrac{x+2}{x+1}$, $D \in (-\infty, -2) \cup (-2, -1) \cup (-1, \infty)$

$g(f(x)) = \dfrac{x^2+x+1}{(x+1)^2}$, $D \in (-\infty, -1) \cup (-1, 0) \cup (0, \infty)$

$f(f(x)) = x + \dfrac{1}{x}+\dfrac{x}{x^2+1}$, $D \in (-\infty, 0) \cup (0, \infty)$

$g(g(x)) = \dfrac{2x+3}{3x+5}$, $D \in (-\infty, -2) \cup (-2, \dfrac{-5}{3}) \cup (\dfrac{-5}{3}, \infty)$



## Sec 1.3

### Exercise 3

#### Statement

For the function $f$ whose graph is given, state the value of each quantity, if it exists. If it does not exist, explain why.

$(a) \displaystyle \lim_{x\rightarrow 1}$

$(b) \displaystyle \lim_{x\rightarrow 3^-} f(x)$

$(c) \displaystyle \lim_{x\rightarrow 3^+} f(x)$

$(d)\ \displaystyle \lim_{x\rightarrow 3} f(x)$

$(e)\ f(3)$



#### Solution

$(a) \displaystyle \lim_{x\rightarrow 1} f(x) = 2$

考慮有點「充分靠近」$(1,f(1))$的左側與右側，

可以得知$\displaystyle \lim_{x\rightarrow 1^+} f(x) = 2$，且$\displaystyle \lim_{x\rightarrow 1^-} f(x) = 2$

因此，根據若為且若$\displaystyle \lim_{x\rightarrow a^-} f(x) = \lim_{x\rightarrow a^+} f(x) = L$

則$\displaystyle\lim_{x\rightarrow 1} f(x)$存在且$\displaystyle \lim_{x\rightarrow a} f(x) = L$的結論，得到$\displaystyle \lim_{x \rightarrow a} f(x) = 2$。



$(b) \displaystyle \lim_{x\rightarrow 3^-} f(x) = 1$

考慮有點充分靠近$(3,f(3))$的左側，

可以得知$\displaystyle \lim_{x\rightarrow 3^-} f(x) = 1$



$(c) \displaystyle \lim_{x\rightarrow 3^+} f(x) = 4$

考慮有點充分靠近$(3, f(3))$的右側

可以得知$\displaystyle \lim_{x\rightarrow 3^+}f(x) = 4$



$(d)\ \displaystyle \lim_{x\rightarrow 3} f(x) = D.N.E$

已知$\displaystyle \lim_{x\rightarrow 3^+} f(x) = 4$且$\displaystyle \lim_{x\rightarrow 3^-} f(x) = 1$

那麼根據若為且若$\displaystyle \lim_{x\rightarrow a^-} f(x) = \lim_{x\rightarrow a^+} f(x) = L$

則$\displaystyle\lim_{x\rightarrow a} f(x)$存在且$\displaystyle \lim_{x\rightarrow a} f(x) = L$的結論

我們可以知道該極限值不存在。



$(e)\ f(3) = 3$

從圖中可以看出來。



#### Answer

$(a) \displaystyle \lim_{x\rightarrow 1} f(x) = 2$

$(b) \displaystyle \lim_{x\rightarrow 3^-} f(x) = 1$

$(c) \displaystyle \lim_{x\rightarrow 3^+} f(x) = 4$

$(d)\ \displaystyle \lim_{x\rightarrow 3} f(x) = D.N.E$

$(e)\ f(3) = 3$



### Exercise 5

#### Statement

For the function $g$ whose graph is given, state the value of
each quantity, if it exists. If it does not exist, explain why.



![image-20200919230716928](https://i.imgur.com/tdZj7ui.png)

$(a)\displaystyle \lim_{t\rightarrow 0^-} g(t)$

$(b) \displaystyle \lim_{t\rightarrow 0^+} g(t)$

$(c) \displaystyle \lim_{t\rightarrow 0}\ g(t)$

$(d) \displaystyle \lim_{t\rightarrow 2^-}\ g(t)$

$(e)\displaystyle \lim_{t\rightarrow 2^+}\ g(t)$

$(f) \displaystyle \lim_{t\rightarrow 2}\ g(t)$

$(g)\ g(2)$

$(h) \displaystyle \lim_{t\rightarrow 4}\ g(t)$



#### Solution

$(a)\displaystyle \lim_{t\rightarrow 0^-} g(t) = -1$

考慮有點「充分靠近」$(0,f(0))$的左側

可以知道$\displaystyle \lim_{t\rightarrow 0^-} g(t)= -1$



$(b) \displaystyle \lim_{t\rightarrow 0^+} g(t) = -2$

考慮有點「充分靠近」$(0,f(0))$的右側

可以知道$\displaystyle \lim_{t\rightarrow 0^+} g(t)= -2$



$(c) \displaystyle \lim_{t\rightarrow 0}\ g(t) = D.N.E.$

我們已知$\displaystyle \lim_{t\rightarrow 0^-}g(t) = -1$，且$\displaystyle \lim_{t\rightarrow 0^+}\ g(t) = -2$

根據若為且若$\displaystyle \lim_{x\rightarrow a^-} f(x) = \lim_{x\rightarrow a^+} f(x) = L$

則$\displaystyle\lim_{x\rightarrow a} f(x)$存在且$\displaystyle \lim_{x\rightarrow a} f(x) = L$的結論

我們可以知道該極限值不存在。



$(d) \displaystyle \lim_{t\rightarrow 2^-}\ g(t) = 2$

我們可以考慮有點充分靠近$(2, f(2))$的左側

可以知道$\displaystyle \lim_{t\rightarrow 2^-} g(t) = 2$



$(e)\displaystyle \lim_{t\rightarrow 2^+}\ g(t) = 0$

我們可以考慮有點充分靠近$(2, f(2))$的右側

可以知道$\displaystyle \lim_{t\rightarrow 2^+} g(t) = 0$



$(f) \displaystyle \lim_{t\rightarrow 2}\ g(t) = D.N.E$

我們已知$\displaystyle \lim_{t\rightarrow 2^-}g(t) = 2$，且$\displaystyle \lim_{t\rightarrow 2^+}\ g(t) = 0$

根據若為且若$\displaystyle \lim_{x\rightarrow a^-} f(x) = \lim_{x\rightarrow a^+} f(x) = L$

則$\displaystyle\lim_{x\rightarrow a} f(x)$存在且$\displaystyle \lim_{x\rightarrow a} f(x) = L$的結論

我們可以知道該極限值不存在。



$(g)\ g(2) = 1$

從圖可以得知$g(2) = 1$



$(h) \displaystyle \lim_{t\rightarrow 4}\ g(t) = 3$

觀察某一點充分靠近$(4, g(4))$的左側，可以知道$\displaystyle \lim_{t\rightarrow 4^-} g(t) = 3$

觀察某一點充分靠近$(4, g(4))$的右側，可以知道$\displaystyle \lim_{t\rightarrow 4^+} g(t) = 3$

因此根據若為且若$\displaystyle \lim_{x\rightarrow a^-} f(x) = \lim_{x\rightarrow a^+} f(x) = L$

則$\displaystyle\lim_{x\rightarrow a} f(x)$存在且$\displaystyle \lim_{x\rightarrow a} f(x) = L$的結論

我們可以知道$\displaystyle \lim_{t\rightarrow 4} g(t) = 3$

#### Answer

$(a)\displaystyle \lim_{t\rightarrow 0^-} g(t) = -1$

$(b) \displaystyle \lim_{t\rightarrow 0^+} g(t) = -2$

$(c) \displaystyle \lim_{t\rightarrow 0}\ g(t) = D.N.E.$

$(d) \displaystyle \lim_{t\rightarrow 2^-}\ g(t) = 2$

$(e)\displaystyle \lim_{t\rightarrow 2^+}\ g(t) = 0$

$(f) \displaystyle \lim_{t\rightarrow 2}\ g(t) = D.N.E$

$(g)\ g(2) = 1$

$(h) \displaystyle \lim_{t\rightarrow 4}\ g(t) = 3$



### Exercise 11

#### Statement

Guess the value of the limit (if it exists) by evaluating the function at the given numbers (correct to six decimal places).

$\displaystyle \lim_{x\rightarrow 2} \dfrac{x^2-2x}{x^2-x-2}$

$x = 2.5,\ 2.1,\ 2.05,\ 2.005,\ 2.001,\ 1.9,\ 1.95,\ 1.99,\ 1.995,\ 1.999$



#### Solution

考慮這些點都很靠近$x=2$，因此我們可以直接乾脆把$f(2)$算出來。

我們先考慮$\dfrac{x^2-2x}{x^2-x-2}$的定義域$D$

$\dfrac{x^2-2x}{x^2-x-2} = \dfrac{x(x-2)}{(x-2)(x+1)}$

我們可以知道$D = (-\infty, -1) \cup (2, \infty)$

$x=2$不在定義域，因此直接求出$x=2$的點一定行不通

我們可以嘗試求出充分靠近$x=2$的$f(2)$，也就是計算$\displaystyle \lim_{x\rightarrow 2} \dfrac{x^2-2x}{x^2-x-2}$



$\displaystyle \lim_{x\rightarrow 2} \dfrac{x^2-2x}{x^2-x-2} =  \lim_{x\rightarrow 2} \dfrac{x(x-2)}{(x-2)(x+1)} = \lim_{x\rightarrow 2} \dfrac{x}{x+1}$

將$x=2$代入得到$\displaystyle \lim_{x\rightarrow 2} \dfrac{x}{x+1}\ = \dfrac{2}{3}$

因此這些點都會很靠近$\dfrac{2}{3}$



#### Answer

$\dfrac{2}{3}$



## Sec 1.4

### Exercise 1

#### Statement

Given that 

$\displaystyle \lim_{x\rightarrow 2} f(x) = 4$　　$\displaystyle \lim_{x\rightarrow 2} g(x) = -2$　　$\displaystyle\lim_{x\rightarrow 2} h(x) = 0$

find the limits that exist. If the limit does not exist, explain why.

$(a) \displaystyle \lim_{x\rightarrow 2}\ [f(x)+5g(x)]$

$(b) \displaystyle \lim_{x\rightarrow 2}\ [g(x)]^3$

$(c) \displaystyle \lim_{x\rightarrow 2} \sqrt{f(x)}$

$(d) \displaystyle \lim_{x\rightarrow 2} \dfrac{3f(x)}{g(x)}$

$(e) \displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)}{h(x)}$

$(f) \displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)h(x)}{f(x)}$



#### Solution

$(a) \displaystyle \lim_{x\rightarrow 2}\ [f(x)+5g(x)] = -6$

根據

1. $\displaystyle \lim_{x\rightarrow a}{[c\times f(x)]} = c\times \lim_{x\rightarrow a}{f(x)}$
2. $\displaystyle \lim_{x\rightarrow a} [f(x) + g(x)] = \lim_{x\rightarrow a} f(x) + \lim_{x\rightarrow a} g(x)$

可以知道

$\displaystyle \lim_{x\rightarrow 2} [f(x)+5g(x)] = \lim_{x\rightarrow 2}f(x) + \lim_{x\rightarrow 2} 5g(x) = \lim_{x\rightarrow 2} f(x) + 5\lim_{x\rightarrow 2}g(x)$

$= 4 + 5\times (-2) = 4 - 10 = -6$



$(b) \displaystyle \lim_{x\rightarrow 2}\ [g(x)]^3 = -8$

根據

$\displaystyle \lim_{x\rightarrow a} [g(x)]^c = (\lim_{x\rightarrow a}g(x))^c$ 

可以知道

$\displaystyle \lim_{x\rightarrow 2}\ [g(x)]^3 = [\lim_{x\rightarrow 2}\ g(x)]^3 = (-2)^3 = -8$



$(c) \displaystyle \lim_{x\rightarrow 2} \sqrt{f(x)} = 2$

根據

$\displaystyle \lim_{x\rightarrow a} [g(x)]^c = (\lim_{x\rightarrow a}g(x))^c$ 

可以知道

$\displaystyle \lim_{x\rightarrow 2}\ \sqrt{f(x)} = [\lim_{x\rightarrow 2}f(x)]^\frac{1}{2} = 4^\frac{1}{2} = 2$



$(d) \displaystyle \lim_{x\rightarrow 2} \dfrac{3f(x)}{g(x)} = -6$

根據

1. $\displaystyle \lim_{x\rightarrow a} \dfrac{f(x)}{g(x)} = \dfrac{\displaystyle \lim_{x\rightarrow a} f(x)}{\displaystyle \lim_{x\rightarrow a}g(x)}$
2. $\displaystyle \lim_{x\rightarrow a}{[c\times f(x)]} = c\times \lim_{x\rightarrow a}{f(x)}$

可以知道

$\displaystyle \lim_{x\rightarrow 2} \dfrac{3f(x)}{g(x)} = \dfrac{\displaystyle \lim_{x\rightarrow 2} 3f(x)}{\displaystyle \lim_{x\rightarrow 2}g(x)} = \dfrac{\displaystyle 3 \lim_{x\rightarrow 2} f(x)}{\displaystyle \lim_{x\rightarrow 2}g(x)} = \dfrac{3\times 4}{-2} = -6$



$(e) \displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)}{h(x)} = D.N.E.$

根據

$\displaystyle \lim_{x\rightarrow a} \dfrac{f(x)}{g(x)} = \dfrac{\displaystyle \lim_{x\rightarrow a} f(x)}{\displaystyle \lim_{x\rightarrow a}g(x)}$

可以知道

$\displaystyle \lim_{x\rightarrow a} \dfrac{f(x)}{h(x)} = \dfrac{\displaystyle \lim_{x\rightarrow a} f(x)}{\displaystyle \lim_{x\rightarrow a}h(x)} = \dfrac{4}{0}$

因此，該點極限值不存在。



$(f) \displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)h(x)}{f(x)} = 0$

根據

1. $\displaystyle \lim_{x\rightarrow a} \dfrac{f(x)}{g(x)} = \dfrac{\displaystyle \lim_{x\rightarrow a} f(x)}{\displaystyle \lim_{x\rightarrow a}g(x)}$
2. $\displaystyle \lim_{x\rightarrow a} [f(x)g(x)] = \lim_{x\rightarrow a} f(x) \times \lim_{x\rightarrow a} g(x)$

可以知道

$\displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)h(x)}{f(x)} = \dfrac{\displaystyle \lim_{x\rightarrow 2} [g(x)h(x)]}{\displaystyle \lim_{x\rightarrow 2}f(x)} = \dfrac{\displaystyle \lim_{x\rightarrow 2} g(x)\times \lim_{x\rightarrow 2} h(x)}{\displaystyle \lim_{x\rightarrow 2}f(x)} = \dfrac{-2\times 0}{4} = 0$



#### Answer

$(a) \displaystyle \lim_{x\rightarrow 2}\ [f(x)+5g(x)] = -6$

$(b) \displaystyle \lim_{x\rightarrow 2}\ [g(x)]^3 = -8$

$(c) \displaystyle \lim_{x\rightarrow 2} \sqrt{f(x)} = 2$

$(d) \displaystyle \lim_{x\rightarrow 2} \dfrac{3f(x)}{g(x)} = -6$

$(e) \displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)}{h(x)} = D.N.E.$

$(f) \displaystyle \lim_{x\rightarrow 2} \dfrac{g(x)h(x)}{f(x)} = 0$



### Exercise 5

#### Statement

$\displaystyle \lim_{t\rightarrow -2} \dfrac{t^4-2}{2t^2-3t+2} = $ ?



#### Solution

嘗試帶入-2，得到$\dfrac{(-2)^4-2}{2\times(-2)^2-3\times (-2) + 2} = \dfrac{14}{16} = \dfrac{7}{8}$



#### Answer

$\displaystyle \lim_{t\rightarrow -2} \dfrac{t^4-2}{2t^2-3t+2} = \dfrac{7}{8}$



### Exercise 7

#### Statement

$\displaystyle \lim_{x\rightarrow 8} (1+\sqrt[3]{x})(2-6x^2+x^3) = $ ?



#### Solution

這是一個多項式，所以$D \in \mathbb{R}$

將多項式帶入8

$(1 + \sqrt[3]{8})(2-6\times8^2 + 8^3) = 390$



#### Answer

$\displaystyle \lim_{x\rightarrow 8} (1+\sqrt[3]{x})(2-6x^2+x^3) = 390$



### Exercise 21

#### Statement

$\displaystyle \lim_{h\rightarrow 0} \dfrac{\sqrt{9+h}-3}{h} = $ ?



#### Solution

$\displaystyle \lim_{h\rightarrow 0} \dfrac{\sqrt{9+h}-3}{h} = \lim_{h\rightarrow 0} [\dfrac{\sqrt{9+h}-3}{h} \times \dfrac{\sqrt{9+h}+3}{\sqrt{9+h}+3}]$

=$\displaystyle \lim_{h\rightarrow 0} \dfrac{9+h-9}{h(\sqrt{9+h}+3)} = \lim_{h\rightarrow 0} \dfrac{h}{h(\sqrt{9+h}+3)} = \lim_{h\rightarrow 0} \dfrac{1}{(\sqrt{9+h}+3)}$

$\dfrac{1}{\sqrt{9}+3} = \dfrac{1}{6}$



#### Answer

$\displaystyle \lim_{h\rightarrow 0} \dfrac{\sqrt{9+h}-3}{h} = \dfrac{1}{6}$



### Exercise 25

#### Statement

$\displaystyle \lim_{x\rightarrow -4} \dfrac{\dfrac{1}{4} + \dfrac{1}{x}}{4+x} = $ ?



#### Solution

$\displaystyle \lim_{x\rightarrow -4} \dfrac{\dfrac{1}{4} + \dfrac{1}{x}}{4+x} = \lim_{x\rightarrow -4} \dfrac{\dfrac{x+4}{4x}}{4+x} = \lim_{x\rightarrow -4}\dfrac{x+4}{4x(x+4)} = \lim_{x\rightarrow -4}\dfrac{1}{4x}$

$= -\dfrac{1}{16}$



#### Answer

$\displaystyle \lim_{x\rightarrow -4} \dfrac{\dfrac{1}{4} + \dfrac{1}{x}}{4+x} = -\dfrac{1}{16}$



### Exercise 27

#### Statement

$\displaystyle \lim_{h\rightarrow 0} \dfrac{(x+h)^3-x^3}{h} = $ ?



#### Solution

$\displaystyle \lim_{h\rightarrow 0} \dfrac{(x+h)^3-x^3}{h} = \lim_{h\rightarrow 0} \dfrac{x^3+3x^2h + 3xh^2 + h^3 -x^3}{h}$

$=\displaystyle \lim_{h\rightarrow 0} \dfrac{3x^2h+3xh^2+h^3}{h} = \lim_{h\rightarrow 0} [3x^2+3xh+h^2]$

$=3x^2$



#### Answer

$\displaystyle \lim_{h\rightarrow 0} \dfrac{(x+h)^3-x^3}{h} = 3x^2$



### Exercise 33

#### Statement

If $4x-9 \le f(x) \le x^2-4x+7$ for $x \ge 0$, find $\displaystyle \lim_{x\rightarrow 4}f(x)$



#### Solution

我們可以利用夾擠定理，也就是

If $g(x) \le f(x) \le h(x)$, so that $\displaystyle \lim_{x\rightarrow c} g(x) \le \lim_{x\rightarrow c} f(x) \le \lim_{x\rightarrow c} h(x)$  

因此，$\displaystyle \lim_{x\rightarrow 4} {[4x-9]} \le \lim_{x\rightarrow 4} f(x) \le \lim_{x\rightarrow 4} {[x^2-4x+7]}$

$\displaystyle = 7 \le \lim_{x\rightarrow 4} f(x) \le 7$

因此$\displaystyle \lim_{x\rightarrow 4} f(x) = 7$



#### Answer

$\displaystyle \lim_{x\rightarrow 4} f(x) = 7$



### Exercise 43

#### Statement

Let $g(x) = \dfrac{x^2+x-6}{|x-2|}$

$(a)$ Find $\displaystyle (i)\ \lim_{x\rightarrow 2^+} g(x)$,   $(ii)$ $\displaystyle \lim_{x\rightarrow 2^-} g(x)$

$(b)$ Does $\displaystyle \lim_{x\rightarrow 2} g(x)$ exist?

$(c)$ Sketch the graph of $g$.



#### Solution

$\displaystyle (i)\ \lim_{x\rightarrow 2^+} g(x)$

我們可以知道$2^+ > 2$，因此$x - 2 > 0$

所以$g(x) = \dfrac{x^2+x-6}{x-2} = \dfrac{(x+3)(x-2)}{x-2} = (x+3)$

也因此，$\displaystyle \lim_{x\rightarrow 2^+} (x+3) = 5$



$(ii)$ $\displaystyle \lim_{x\rightarrow 2^-} g(x)$

我們可以知道$2^+ < 2$，因此$x - 2 < 0$

所以$g(x) = \dfrac{x^2+x-6}{-(x-2)} = \dfrac{(x+3)(x-2)}{-(x-2)} = -(x+3) = -x-3$

也因此，$\displaystyle \lim_{x\rightarrow 2^+} (-x-3) = -5$



$(b)$ Does $\displaystyle \lim_{x\rightarrow 2} g(x)$ exist?

No, 因為$\displaystyle \lim_{x\rightarrow 2^+} g(x) \neq \displaystyle \lim_{x\rightarrow 2^-} g(x)$

所以$\displaystyle \lim_{x\rightarrow 2} g(x) = D.N.E$



$(c)$ Sketch the graph of $g$.

![image-20200920010747178](https://i.imgur.com/SUeC22O.png)



#### Answer

$\displaystyle (i)\ \lim_{x\rightarrow 2^+} g(x) = 5$

$(ii)$ $\displaystyle \lim_{x\rightarrow 2^-} g(x) = -5$

$(b)$ $D.N.E.$

$(c)$ 在Solution內





### Exercise 54

#### Statement

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin 3x \sin 5x}{x^2} = $ ?



#### Solution

我們可以拆解成$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin 3x \sin 5x}{x^2} = \displaystyle \lim_{x\rightarrow 0} \dfrac{\sin 3x}{x} \times \dfrac{\sin 5x}{x}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{\sin 3x}{x} \times \lim_{x\rightarrow 0} \dfrac{\sin 5x}{x}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{3}{3} \dfrac{\sin 3x}{x} \times \lim_{x\rightarrow 0} \dfrac{5}{5} \dfrac{\sin 5x}{x}$

$= \displaystyle \lim_{x\rightarrow 0} 3\dfrac{\sin 3x}{3x} \times \lim_{x\rightarrow 0} 5 \dfrac{\sin 5x}{5x}$



$\displaystyle \because \lim_{x\rightarrow c} \dfrac{\sin x}{x} = 1$

$\therefore 3 \times 5 = 15$



#### Answer

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin 3x \sin 5x}{x^2} = 15$

### Practice 1

#### Statement

Find the limits.

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\cos x - 1}{x}$



#### Solution

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\cos x - 1}{x}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{(\cos x - 1)(\cos x + 1)}{x(\cos x + 1)}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{\cos^2x - 1}{x(\cos x + 1)}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{\sin^2x}{x(\cos x + 1)}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{\sin x}{(\cos x + 1)}$

$= \dfrac{0}{1+1} = \dfrac{0}{2} = 0$



## Sec 1.5

### Exercise 3

#### Statement

(a) From the graph of $f$, state the numbers at which $f$ is discontinuous and explain why.

(b) For each of the numbers stated in part (a), determine whether $f$ is continuous from the right, or from the left, or neither.

![image-20201002231205821](https://i.imgur.com/mzpNsgE.png)



#### Solution

(a)

對於連續的定義，若$x=a$在圖形上連續，則$\displaystyle \lim_{x\rightarrow a} f(a) = f(a)$，因此

$x=-4$不連續，因為$\displaystyle \lim_{x\rightarrow -4} f(x)$存在，但$f(-4)$不存在，不符合上述定義。

$x=-2$不連續，因為$\displaystyle \lim_{x\rightarrow -2} f(x)$不存在，但$f(-2)$存在，不符合上述定義。

$x=2$不連續，因為$\displaystyle \lim_{x\rightarrow 2} f(x)$不存在，但$f(2)$存在，不符合上述定義。

$x=4$不連續，因為$\displaystyle \lim_{x\rightarrow 4} f(x)$不存在，$f(4)$存在，不符合上述定義。

因此，$f$在點$x=-4,\ x= -2,\ x= 2,\ x =4$不存在。



(b)

考慮$x= -4,\ x = -2,\ x = 2,\ x = 4$

$x = -4$時，$\displaystyle \lim_{x\rightarrow -4^+} f(x) = \lim_{x\rightarrow -4^-} f(x)$，但是$f(-4)$沒有定義，因此與左界，右界均不連續(neither)

$x= -2$時，$\displaystyle \lim_{x\rightarrow -2^-} f(x) = f(-2)$，但是$\displaystyle \lim_{x\rightarrow -2^+} f(x) \neq f(-2)$，因此與左界連續(left)

$x=2$時，$\displaystyle \lim_{x\rightarrow 2^-} f(x) \neq f(2)$ ，但是$\displaystyle \lim_{x\rightarrow 2^+} f(x) = f(2)$ $，因此與右界連續(right)

$x = 4$時，$\displaystyle \lim_{x\rightarrow 4^-} f(x) = -\infty \neq f(4)$，$\displaystyle \lim_{x\rightarrow 4^+} f(x) = f(4)$，因此與右界連續(right)



#### Answer

(a) 

$f$在點$x=-4,\ x= -2,\ x= 2,\ x =4$不存在。



(b) 
$x = -4$時，與左界，右界均不連續(neither)
$x= -2$時，與左界連續(left)
$x=2$時，與右界連續(right)
$x = 4$時，與右界連續(right)



### Exercise 13

#### Statement

Use the definition of continuity and the properties of limits to show that the function is continuous at the given number $a$.

$f(x) = (x + 2x^3)^4, a = -1$



#### Solution

對於連續的定義，若$x=a$在圖形上連續，則$\displaystyle \lim_{x\rightarrow a} f(a) = f(a), \exist f(a)$

因此我們可以考慮$f(-1)$是否存在

首先先考慮$f(x)$的定義域，可以知道這是一個多項式，因此定義域$D \in \mathbb{R}$

帶入$f(-1) = (-1+2\times (-1)^3)^4 = (-3)^4 = 81$

此點存在因此$\displaystyle \lim_{x\rightarrow -1} f(x) = 81 = f(-1)$

因此點$a$在$f$連續。



#### Answer

透過Solution得知，點$a$在$f$連續。



### Exercise 15

#### Statement

Explain why the function is discontinuous at the given number $a$ . Sketch the graph of the function.

$f(x) = \dfrac{1}{x+2}, \quad a = -2$



#### Solution

考慮$f$的定義域$D$，由於分母不能為$0$，因此$D \in \mathbb{R} - \{-2\}$

因此我們可以知道$f(a)$沒有定義。

對於連續的定義，若$x=a$在圖形上連續，則$\displaystyle \lim_{x\rightarrow a} f(a) = f(a), \exist f(a)$，因此$f$在點$a$不連續。



$f(x) = \dfrac{1}{x+2}$的圖形如下。

![image-20201003003216340](https://i.imgur.com/izgsl4Z.png)

#### Answer

證明$a$不連續，請見Solution。

$f(x)$的圖形，請見Solution。



### Exercise 19

#### Statement

Explain, using Theorems 4, 5, 6, and 8, why the function is continuous at every number in its domain. State the domain.

$F(x) = \dfrac{2x^2-x-1}{x^2+1}$



#### Solution

考慮方程式的定義域，首先分母不能為0。

因此$x^2+1 \ge 0 $，可以知道這個方程式**恆正**，因此得到$F(x)$的定義域$D \in \mathbb{R}$

在實數域中每一點都存在，因此$F(x)$對於實數域的每一個$x$都連續。



#### Answer

說明請見Solution，定義域$D \in \mathbb{R}$



### Exercise 21

####  Statement

Explain, using Theorems 4, 5, 6, and 8, why the function is continuous at every number in its domain. State the domain.

$Q(x) = \dfrac{\sqrt[3]{x-2}}{x^3-2}$



#### Solution

考慮定義域，分母不能為0，因此$x \neq \sqrt[3]{2}$

而根號為3次方根，因此定義域$D$為$D \in (-\infty, \sqrt[3]{2}) \cup (\sqrt[3]{2}, \infty)$

當點$a$存在時，該點$a$的極限值等於$f(a)$，因此在定義域的每個點都連續。



#### Answer

說明請見Solution，定義域$D \in (-\infty, \sqrt[3]{2}) \cup (\sqrt[3]{2}, \infty)$



### Exercise 27

#### Statement

Use continuity to evaluate the limit.

$\displaystyle \lim_{x\rightarrow 4} \dfrac{5+\sqrt{x}}{\sqrt{5+x}}$



#### Solution

考慮式子的定義域$D$，首先分母必須要大於0，而根號內的數字必須要大於等於0。

因此$5+x \ge 0, \sqrt{5+x} > 0, \sqrt{x} > 0$，取聯集得到$x \ge  0$。

$x=4$在定義域中，因此此點連續，將$x=4$帶入式子得到$\dfrac{5+\sqrt{4}}{\sqrt{5+4}} = \dfrac{5+2}{3} = \dfrac{7}{3}$



因此$\displaystyle \lim_{x\rightarrow 4} \dfrac{5+\sqrt{x}}{\sqrt{5+x}} = \dfrac{7}{3}$



#### Answer

$\displaystyle \lim_{x\rightarrow 4} \dfrac{5+\sqrt{x}}{\sqrt{5+x}} = \dfrac{7}{3}$



### Exercise 29

#### Statement

Show that is continuous on $(-\infty, \infty)$.

$f(x)= \left\{\begin{array}\ x^2 & \rm{if}\ x < 1 \\ \sqrt{x} & \rm{if}\ x \ge 1 \end{array}\right.$



#### Solution

這是複合函數，對於一段函數，在定義域上的每個點都連續。

因此我們只需要知道複合函數的接點是否連續即可。



所以我們需要考慮$x = 1$時的limit。

也就是考慮$\displaystyle \lim_{x\rightarrow 1^+} f(x) = \lim_{x\rightarrow 1^-} f(x)$

當$x\rightarrow 1^+$，我們應該用第二個式子，因此$\displaystyle \lim_{x\rightarrow 1^+} \sqrt{x} = 1$

當$x\rightarrow 1^-$，我們應該用第一個式子，因此$\displaystyle \lim_{x\rightarrow 1^-}x^2=1$

因此$\displaystyle \lim_{x\rightarrow 1^+} f(x) = \lim_{x\rightarrow 1^-} f(x)$成立，$\displaystyle \lim_{x\rightarrow 1} f(x) = 1 = f(1)$



因此，對於每個定義域上的所有點都連續。



#### Answer

請見Solution。



### Exercise 33

#### Statement

For what value of the constant $c$ is the function $f$ continuous on $(-\infty, \infty)$ ?

$f(x)= \left\{\begin{array}\ cx^2+2x & \rm{if}\ x < 2 \\ x^3-cx & \rm{if}\ x \ge 2 \end{array}\right.$



#### Solution

這是複合函數，對於一段函數，在定義域上的每個點都連續。

因此我們只需要知道複合函數的接點是否連續即可。



因此我們希望，$\displaystyle \lim_{x\rightarrow 2^+} f(x) = \lim_{x\rightarrow 2^-} f(x)$

當$x\rightarrow 2^+$時，我們應該要使用第二個式子

因此$\displaystyle \lim_{x\rightarrow 2^+} f(x) = 2^3-2c = 8-2c$



當$x\rightarrow 2^-$時，我們應該要使用第一個式子

因此$\displaystyle \lim_{x\rightarrow 2^-} f(x) = cx^2+2x = 4c+4$



因此$\displaystyle \lim_{x\rightarrow 2^+} f(x) = \lim_{x\rightarrow 2^-} f(x)$, $8-2c = 4c+4 \Rightarrow 6c = 4 \Rightarrow c = \dfrac{2}{3}$



#### Answer

$c = \dfrac{2}{3}$



### Exercise 39

#### Statement

Use the Intermediate Value Theorem to show that there is a root of the given equation in the specified interval.

$x^4+x-3 = 0,\quad (1,2)$



#### Solution

考慮$f(x) = x^4+x-3$，$f(1) = 1+1-3 = -1$，$f(2) = 16+2-3 = 15$

透過介值定理告訴我們當$f$連續於$(a,b)$，其$f(c)$的值會落在$f(a)$與$f(b)$之間。



因此我們可以知道$(-1, 15)$存在$0$，為root。

因此$f(x)$存在root。



#### Answer

見Solution。




## Sec 1.6

### Exercise 1

#### Statement

For the function $f$ whose graph is given, state the following.

(a) $\displaystyle \lim_{x\rightarrow \infty} f(x)$　(b)$\displaystyle \lim_{x\rightarrow -\infty}f(x)$　(c) $\displaystyle \lim_{x\rightarrow 1}f(x)$

(d) $\displaystyle \lim_{x\rightarrow 3} f(x)$　(e) The equations of the asymptotes

![image-20201003013516867](https://i.imgur.com/ZaKdi40.png)

#### Solution

(a) $\displaystyle \lim_{x\rightarrow \infty} f(x)$

從圖上可以知道，曲線會逐漸趨近$y=-2$

因此$\displaystyle \lim_{x\rightarrow \infty} f(x) = -2$



(b) $\displaystyle \lim_{x\rightarrow -\infty}f(x)$

從圖上可以知道，曲線會逐漸趨近$y=2$

因此$\displaystyle \lim_{x\rightarrow -\infty} f(x) = 2$



(c) $\displaystyle \lim_{x\rightarrow 1}f(x)$

從圖上可以知道，左界與右界都會逐漸趨近$y=\infty$

因此$\displaystyle \lim_{x\rightarrow 1} f(x) = \infty$



(d) $\displaystyle \lim_{x\rightarrow 3} f(x)$

從圖上可以知道，左界與右界都會逐漸趨近$y=-\infty$

因此$\displaystyle \lim_{x\rightarrow 3} f(x) = -\infty$



(e) The equations of the asymptotes

漸進線為$x=1$、$x=3$、$y= -2$與$y=2$。



### Exercise 5

#### Statement

Sketch the graph of an example of a function that satisfies all of the given conditions.

$\displaystyle \lim_{x\rightarrow 2} f(x) = -\infty,\space \lim_{x\rightarrow \infty} f(x) = \infty,\space \lim_{x\rightarrow -\infty} f(x) = 0,\space \lim_{x\rightarrow 0^+}f(x) = \infty, \space \lim_{x\rightarrow 0^-}f(x) = -\infty$



#### Solution

![image-20201003021005177](https://i.imgur.com/Srqcqnl.png)

![image-20201003021123364](https://i.imgur.com/I06Tf4s.png)

#### Answer

請見Solution。



### Exercise 13

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow -3^+} \dfrac{x+2}{x+3}$



#### Solution

考慮$x=-2.9999999$，我們可以知道$x+2<0$，且$x+3>0$，因此為負。

又因為$\dfrac{-3+2}{-3+3} = \dfrac{-1}{0}$ ，我們可以估計這個值會是$\infty$

結合上述，我們可以知道$\displaystyle \lim_{x\rightarrow -3^+} \dfrac{x+2}{x+3} = -\infty$



#### Answer

$\displaystyle \lim_{x\rightarrow -3^+} \dfrac{x+2}{x+3} = -\infty$



### Exercise 15

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow 1} \dfrac{2-x}{(x-1)^2}$



#### Solution

考慮$x=0.999999$，可以知道$2-x>0$，$(x-1)^2>0$

又因$\displaystyle \lim_{x\rightarrow 1^-} \dfrac{2-x}{(x-1)^2} = \dfrac{1}{0}$，我們可以估計這個值會是$\infty$

結合上述，我們可以知道$\displaystyle \lim_{x\rightarrow 1^-} \dfrac{2-x}{(x-1)^2} = \infty$



考慮$x=1.000001$，可以知道$2-x>0$，$(x-1)^2>0$

又因$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{2-x}{(x-1)^2} = \dfrac{1}{0}$，我們可以估計這個值會是$\infty$

結合上述，我們可以知道$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{2-x}{(x-1)^2} = \infty$



根據定義$\displaystyle \lim_{x\rightarrow a^+} f(x) = L, \displaystyle \lim_{x\rightarrow a^-} f(x) = L \iff \displaystyle \lim_{x\rightarrow a} f(x) = L$

因此$\displaystyle \lim_{x\rightarrow 1} \dfrac{2-x}{(x-1)^2} = \infty$



#### Answer

$\displaystyle \lim_{x\rightarrow 1} \dfrac{2-x}{(x-1)^2} = \infty$



### Exercise 19

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{3x-2}{2x+1}$



#### Solution

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{3x-2}{2x+1} = \lim_{x\rightarrow \infty}\dfrac{3-\dfrac{2}{x}}{2+\dfrac{1}{x}} = \dfrac{3}{2}$



#### Answer

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{3x-2}{2x+1} = \dfrac{3}{2}$



### Exercise 21

#### Statement

Find the limit.

$\displaystyle \lim_{t\rightarrow \infty}\dfrac{\sqrt{t}+t^2}{2t-t^2}$



#### Solution

$\displaystyle \lim_{t\rightarrow \infty} \dfrac{\sqrt{t}+t^2}{2t-t^2} = \lim_{t\rightarrow \infty} \dfrac{\dfrac{\sqrt{t}}{t^2} + 1}{\dfrac{2t}{t^2}-1} = \lim_{t\rightarrow \infty} \dfrac{\dfrac{1}{\sqrt{t}} + 1}{\dfrac{2}{t}-1} = -1$

#### Answer

$\displaystyle \lim_{t\rightarrow \infty}\dfrac{\sqrt{t}+t^2}{2t-t^2} = -1$



### Exercise 25

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow \infty} (\sqrt{9x^2+x}-3x)$



#### Solution

$\displaystyle \lim_{x\rightarrow \infty} (\sqrt{9x^2+x}-3x) = \lim_{x\rightarrow \infty} \dfrac{9x^2+x-9x^2}{\sqrt{9x^2+x}+3x} = \lim_{x\rightarrow \infty} \dfrac{x}{\sqrt{9x^2+x}+3x}$

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x}{\sqrt{x^2(9+\dfrac{x}{x^2})}+3x} = \displaystyle \lim_{x\rightarrow \infty} \dfrac{x}{x\sqrt{(9+\dfrac{1}{x})}+3x}$

$\because \dfrac{1}{\infty} = 0$

$\therefore \displaystyle \lim_{x\rightarrow \infty} \dfrac{x}{x\sqrt{9}+3x} = \lim_{x\rightarrow \infty} \dfrac{x}{3x+3x} = \lim_{x\rightarrow \infty} \dfrac{x}{6x} = \lim_{x\rightarrow \infty} \dfrac{1}{6} = \dfrac{1}{6}$

#### Answer

$\displaystyle \lim_{x\rightarrow \infty} (\sqrt{9x^2+x}-3x) = \dfrac{1}{6}$



### Exercise 26

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow \infty}(\sqrt{x^2+ax}-\sqrt{x^2-bx})$



#### Solution

$\displaystyle \lim_{x\rightarrow \infty} (\sqrt{x^2+ax}-\sqrt{x^2-bx}) = \lim_{x\rightarrow \infty} \dfrac{x^2+ax-x^2-bx}{\sqrt{x^2+ax}+\sqrt{x^2-bx}} = \lim_{x\rightarrow \infty} \dfrac{ax-bx}{\sqrt{x^2+ax}+\sqrt{x^2-bx}} = \dfrac{a-b}{2}$




#### Answer

$\displaystyle \lim_{x\rightarrow \infty}(\sqrt{x^2+ax}-\sqrt{x^2-bx}) = \dfrac{a-b}{2}$



### Exercise 27

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^4-3x^2+x}{x^3-x+2}$



#### Solution

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^4-3x^2+x}{x^3-x+2} = \lim_{x\rightarrow \infty} \dfrac{\dfrac{x^4}{x^3}-\dfrac{3x^2}{x^3}+\dfrac{x}{x^3}}{1-\dfrac{x}{x^3}+\dfrac{2}{x^3}} = \lim_{x\rightarrow \infty} \dfrac{x - \dfrac{3}{x}+\dfrac{1}{x^2}}{1-\dfrac{1}{x^2}+\dfrac{2}{x^3}}$

$\displaystyle \lim_{x\rightarrow \infty} x = \infty$



#### Answer

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^4-3x^2+x}{x^3-x+2} = \infty$



### Exercise 29

#### Statement

$\displaystyle \lim_{x\rightarrow \infty} \cos x$



#### Solution

$\displaystyle \lim_{x\rightarrow \infty} \cos x$ 不存在，因為函數非遞增或者遞減。



#### Answer

$\displaystyle \lim_{x\rightarrow \infty} \cos x = D.N.E.$



### Exercise 35

#### Statement

Find the horizontal and vertical asymptotes of each curve. 

Check your work by graphing the curve and estimating the asymptotes.

$y=\dfrac{2x^2+x-1}{x^2+x-2}$



#### Solution

考慮定義域，當$x$不在定義域時會使函數值為$-\infty$或$\infty$，取決於分子分母的正負。

$y=\dfrac{2x^2+x-1}{x^2+x-2} = \dfrac{2x^2+x-1}{(x+2)(x-1)}$

當$x=-2$或$x=1$時，函數值為$-\infty$或$\infty$。

因此漸進線為$x=-2$與$x=1$。



考慮$x=\infty$，$x=-\infty$，可以知道無論正負，$y=2$

因此漸進線$y=2$



綜合以上，漸進線為$x=-2, x=1, y=2$

![image-20201003025640088](https://i.imgur.com/3tmqbkC.png)



#### Answer

$y=\dfrac{2x^2+x-1}{x^2+x-2}$的漸進線為$x=-2, x=1, y=2$



### Exercise 47

#### Statement

Find $\displaystyle \lim_{x\rightarrow \infty} f(x)$ if, for all $x > 5$

$\dfrac{4x-1}{x} < f(x) < \dfrac{4x^2+3x}{x^2}$



#### Solution

利用夾擠定理

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{4x-1}{x} < \lim_{x\rightarrow \infty} f(x) < \lim_{x\rightarrow \infty} \dfrac{4x^2+3x}{x^2}$

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{4-\dfrac{1}{x}}{1} < \lim_{x\rightarrow \infty} f(x) < \lim_{x\rightarrow \infty} 4+\dfrac{3x}{x^2}$

$\displaystyle 4 < \lim_{x\rightarrow \infty} f(x) < 4$

$\displaystyle \lim_{x\rightarrow \infty} f(x) = 4$

#### Answer

$\displaystyle \lim_{x\rightarrow \infty} f(x) = 4$

### Quiz 1

#### Statement

Find the limit.

$\displaystyle \lim_{x\rightarrow \infty} \sqrt[5]{x}\sin{\dfrac{3}{x}}$

#### Solution

$\displaystyle \lim_{x\rightarrow \infty} \sqrt[5]{x}\sin{\dfrac{3}{x}}$

$= \displaystyle \lim_{x\rightarrow 0} \sqrt[5]{\dfrac{1}{x}}\sin 3x$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{\sin 3x}{x^{\frac{1}{5}}}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{(\sin 3x)x^{\frac{4}{5}}}{x}$

$= \displaystyle \lim_{x\rightarrow 0} \dfrac{3(\sin 3x)x^{\frac{4}{5}}}{3x}$

$\because \displaystyle \lim_{x\rightarrow 0} \dfrac{\sin x}{x} = 1$

$\therefore \displaystyle \lim_{x\rightarrow 0} \dfrac{3(\sin 3x)x^{\frac{4}{5}}}{3x} = \displaystyle \lim_{x\rightarrow 0} 3x^{\frac{4}{5}} = 0$

#### Answer

$\displaystyle \lim_{x\rightarrow \infty} \sqrt[5]{x}\sin{\dfrac{3}{x}} = 0$



### Practice 1

#### Statement

$\displaystyle \lim_{x\rightarrow \infty} [\sqrt[3]{x(x-6)^2} - (ax+b)] = 0$

Find a, b.



#### Solution

考慮$\sqrt[3]{x(x-6)^2} \approx (ax+b)$，因此我們可以比較$x(x-6)^2$與$(ax+b)^3$的前兩項。

$x(x^2-12x+36) \approx a^3x^3+a^2bx^2+ab^2x+b^3$

$x^3 - 12x^2 + 36x \approx a^3x^3 + 3a^2bx^2 + 3ab^2x + b^3$

比較前兩項，得到

$a^3x^3 = x^3$

$3a^2bx^2 = -12x^2$

因此可以得到

$a = 1$, $b=-4$



#### Answer

$a= 1$, $b=-4$



### Practice 2

#### Statement

Evaluate $\displaystyle \lim_{x\rightarrow \infty} \ln(1+5x) - \ln(4+9x)$

#### Solution

$\displaystyle \lim_{x\rightarrow \infty} \ln(1+5x) - \ln(4+9x)$

$= \displaystyle \lim_{x\rightarrow \infty} \ln(\dfrac{1+5x}{4+9x})$

$= \displaystyle \lim_{x\rightarrow \infty} \ln(\dfrac{\dfrac{1}{x}+5}{\dfrac{4}{x}+9})$

$= \ln(\dfrac{5}{9})$



#### Answer

$\ln(\dfrac{5}{9})$