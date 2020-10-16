# 微積分Practice



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



## Sec 2.1

### Exercise 3

#### Statement

Find an equation of the tangent line to the curve at the given point.

$y=4x-3x^2,\quad (2,-4)$



#### Solution

我們可以微分函數來得到切線斜率

$y' = \dfrac{d}{dx} 4x - \dfrac{d}{dx} 3x^2$

$= 4-6x$



帶入$x=2$，得到該點的切線斜率

$m=4-6\times 2 = 4-12=-8$



利用點斜式造出直線方程

$y + 4 = -8(x-2) \Rightarrow y+4=-8x+16 \Rightarrow 8x+y-12=0$



#### Answer

$8x+y-12=0$



### Exercise 5

#### Statement

Find an equation of the tangent line to the curve at the given point.

$y=\sqrt{x},\quad (1,1)$



#### Solution

我們可以微分函數來得到切線斜率

$y' = \dfrac{d}{dx}x^{\frac{1}{2}} = \dfrac{1}{2}x^{\frac{-1}{2}}$



帶入$x=1$，得到該點的切線斜率

$m=\dfrac{1}{2}1^{\frac{-1}{2}} = \dfrac{1}{2}$



利用點斜式造出直線方程

$y-1=\dfrac{1}{2}(x-1) \Rightarrow 2y-2 = x-1 \Rightarrow 2y-x-1=0$



#### Answer

$2y-x-1=0$



### Exercise  6

#### Statement

Find an equation of the tangent line to the curve at the given point.

$y = \dfrac{2x+1}{x+2}$，$(1, 1)$



#### Solution

$y' = \dfrac{(x+2)\dfrac{d}{dx}(2x+1) - (2x+1)\dfrac{d}{dx}(x+2)}{(x+2)^2}$

$= \dfrac{(x+2)\times 2 - (2x+1)\times 1}{(x+2)^2}$

$= \dfrac{2x+4-2x-1}{(x+2)^2}$

$= \dfrac{3}{(x+2)^2}$



$x = 1,\ m = \dfrac{3}{(1+2)^2} = \dfrac{1}{3}$

可以造出式子，$y -1 = \dfrac{1}{3}(x-1) \Rightarrow y = \dfrac{1}{3}(x-1)+1$



#### Answer

$y = \dfrac{1}{3}(x-1) + 1$



### Exercise 11

#### Statement

If a ball is thrown into the air with a velocity of $40$ ft/s, its height (in feet) after seconds is given by $y=40t-16t^2$.

Find the velocity when $t = 2$



#### Solution

我們可以把$y=40t-16t^2$微分，來取得瞬時速度。

$y' = \dfrac{d}{dt} 40t - \dfrac{d}{dt}16t^2 = 40-32t$



帶入$t=2$得到$40-64=-24$

因此在$t=2$的瞬時速度為$-24\ ft/s$



#### Answer

$-24$ ft/s



### Exercise 13

#### Statement

The displacement (in meters) of a particle moving in a straight line is given by the equation of motion $s=\dfrac{1}{t^2}$

where $t$ is measured in seconds. Find the velocity of the particle at times $t=a$, $t=1$, $t=2$, and $t=3$



#### Solution

我們可以微分$s=\dfrac{1}{t^2}$。

$s' = \dfrac{d}{dt} \dfrac{1}{t^2}$

$= \dfrac{t^2\dfrac{d}{dt}1 - 1\dfrac{d}{dt}t^2}{(t^2)^2}$

$= \dfrac{0-2t}{t^4} = \dfrac{-2}{t^3}$



帶入$t=a$，得到$\dfrac{-2}{a^3}$

帶入$t=1$，得到$\dfrac{-2}{1}=-2$

帶入$t=2$，得到$\dfrac{-2}{8} = \dfrac{-1}{4}$

帶入$t=3$，得到$\dfrac{-2}{27}$



#### Answer

$t=a,\ s'(a) = \dfrac{-2}{a^3}$ m/s

$t=1,\ s'(1) = -2$ m/s

$t=2,\ s'(2) = \dfrac{-1}{4}$ m/s

$t=3,\ s'(3) = \dfrac{-2}{27}$ m/s



### Exercise 17

#### Statement

If an equation of the tangent line to the curve $y=f(x)$ at the point where $a=2$ is $y=4x-5$, find $f(2)$ and $f'(2)$



#### Solution

$a=x=2,\ y = 3 = f(2)$

$f'(x) = \dfrac{d}{dx} 4x - \dfrac{d}{dx} 5 = 4$

$f'(2) = 4$



#### Answer

$f(2) = 3$

$f'(2) = 4$



### Exercise 22

#### Statement

If $g(x)=x^4-2$, find $g'(1)$ and use it to find an equation of the tangent line to the curve $y=x^4-2$ at the point $(1, -1)$



#### Solution

$g'(x) = \dfrac{d}{dx} x^4 - \dfrac{d}{dx} 2 = 4x^3$

$g'(1) = 4\times 1^3 = 4 = m$



帶入點斜式

$y+1=4(x-1) = y+1=4x-4 = 4x-y-5=0$



#### Answer

$4x-y-5=0$



### Exercise 26

#### Statement

Find $f'(a)$

$f(t) = 2t^3+t$



#### Solution

$f'(t) = \dfrac{d}{dt}2t^3 + \dfrac{d}{dt}t = 6t^2+1$

$f'(a) = 6a^2+1$



#### Answer

$f'(a) = 6a^2+1$



### Exercise 27

#### Statement

Find $f'(a)$

$f(t) = \dfrac{2t+1}{t+3}$



#### Solution

$f'(t) = \dfrac{(t+3)\dfrac{d}{dt}(2t+1) - [(2t+1)\dfrac{d}{dt}(t+3)]}{(t+3)^2} = \dfrac{2(t+3)- (2t+1)}{(t+3)^2} = \dfrac{5}{(t+3)^2}$

$f'(a) = \dfrac{5}{(a+3)^2}$



#### Answer

$f'(a) = \dfrac{5}{(a+3)^2}$



### Exercise 29

#### Statement

Find $f'(a)$

$f(x) = \sqrt{1-2x}$



#### Solution

$f'(x) = \dfrac{d}{dx}\sqrt{1-2x}$

改寫式子，令$u=1-2x$

$f'(x) = \dfrac{d}{dx}\sqrt{u}$

$= \dfrac{d}{du}\sqrt{u} \dfrac{du}{dx}$

$= \dfrac{1}{2}u^{\frac{-1}{2}} \times u \dfrac{d}{dx}$

$= \dfrac{1}{2}u^{\frac{-1}{2}} \times (-2)$

$= -u^{\frac{-1}{2}}$



代回$u$得到$f'(x) = -(1-2x)^{\frac{-1}{2}} = -\dfrac{1}{\sqrt{1-2x}}$

因此$f'(a) = - \dfrac{1}{\sqrt{1-2a}}$

#### Answer

$f'(a) = -\dfrac{1}{\sqrt{1-2a}}$



### Exercise 35

#### Statement

Find $f'(a)$

$f(x) = \dfrac{4}{\sqrt{1-x}}$



#### Solution

$f(x) = 4\times (1-x)^{-\frac{1}{2}}$

$f'(x) = \dfrac{d}{dx}4 \times (1-x)^{-\frac{1}{2}} + 4\times \dfrac{d}{dx}(1-x)^{-\frac{1}{2}}$

$= 4\times \dfrac{d}{dx}(1-x)^{-\frac{1}{2}}$

令$u=1-x$，則

$f'(x) = 4\times \dfrac{d}{dx}u^{-\frac{1}{2}}$

$= 4\times \dfrac{-1}{2}u^{-\frac{3}{2}} \times \dfrac{d}{dx} (1-x)$

$= 4\times \dfrac{-1}{2}u^{-\frac{3}{2}} \times -1$

$= 2u^{-\frac{3}{2}}$

還原$u$，得到$f'(x) = 2(1-x)^{-\frac{3}{2}}$

因此$f'(a) = 2(1-a)^{-\frac{3}{2}}$



#### Answer

$f'(a) = 2(1-a)^{-\frac{3}{2}}$



### Exercise 31

#### Statement

Each limit represents the derivative of some function $f$ at some number $a$ . State such an $f$ and $a$ in each case.

$\displaystyle \lim_{h\rightarrow 0} \dfrac{(1+h)^{10}-1}{h}$



#### Solution

利用$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(x+h) - f(x)}{h}$的模板，我們可以知道



$f(x+h) = (1+h)^{10}$

$f(x) = 1$



因此我們可以推得，$f(x) = x^{10}$，且$x= 1 = a$



#### Answer

$f(x) = x^{10}, a = 1$



### Exercise 33

#### Statement

Each limit represents the derivative of some function $f$ at some number $a$ . State such an $f$ and $a$ in each case.

$\displaystyle \lim_{x\rightarrow 5} \dfrac{2^x-32}{x-5}$



#### Solution

利用$\displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$ 模板，我們可以推得

$f(x) = 2^x$，$a = 5$



#### Answer

$f(x) = 2^x$，$a=5$



### Exercise 44

#### Statement

The number of bacteria after t hours in a controlled laboratory experiment is $n=f(t)$

(a) What is the meaning of the derivative $f'(5)$ ? What are its units?

(b) Suppose there is an unlimited amount of space and nutrients for the bacteria. 

Which do you think is larger, $f'(5)$ or $f'(10)$? 

If the supply of nutrients is limited, would that affect your conclusion? Explain.



#### Solution

細菌的成長函數為一個曲線，$f'(5)$的意義為5小時後，當前的成長率，單位為(病毒數量/時)

因為成長函數是一個遞增曲線，因此$f'(10) > f'(5)$

nutrients is limited，會使細菌的成長曲線遞減

可能會使得某一個時段$a$與某一個時段$b$，$f'(a) > f'(b), a>b$



#### Answer

見Solution。



### Exercise 45

#### Statement

Let $T(t)$ be the temperature (in $^{\circ}F$) in Phoenix hours after midnight on September 10, 2008. 

The table shows values of this function recorded every two hours. 

What is the meaning $T'(8)$ of ? Estimate its value.



#### Solution

$T'(8)$的意義為早上8:00的溫度與時間比率，而$T'(8)$可以由t=6與t=10計算斜率來取得近似值。

$\dfrac{T(6)-T(10)}{6-10} = \dfrac{75-90}{-4} = 3.75^{\circ}F/hr$



#### Answer

見Solution。



## Sec 2.2

### Exercise 3

#### Statement

Match the graph of each function in (a)–(d) with the graph of its derivative in I–IV. Give reasons for your choices.



![image-20201013162130139](https://i.imgur.com/PYEShPM.png)



#### Solution 

觀察一下圖形，可以知道$a$的曲線上有兩個點的斜率為0。

因此微分後的曲線會通過$y=0$兩次，故選II。



觀察一下圖形，可以知道$b$的曲線上有兩個不可以微的點。

因為尖端是不可微的，故選IV



觀察一下圖形，可以知道$c$的曲線上有一個斜率為0的點

而且左右兩端都越來越趨近於0，因此左右兩邊的斜率趨近於0。

因此故選I



觀察一下圖形，可以知道$d$的曲線上有三個斜率為0的點

因此微分過後的曲線會通過$y=0$三次，故選III。



#### Answer

a → II, b → IV, c → I, d → III



### Exercise 19

#### Statement

Find the derivative of the function using the definition of derivative. 

State the domain of the function and the domain of its derivative.

$f(x) = \dfrac{1}{2}x - \dfrac{1}{3}$



#### Solution

$f'(x) = \dfrac{d}{dx} \dfrac{1}{2}x - \dfrac{d}{dx} \dfrac{1}{3}$

$= \dfrac{1}{2} - 0 = \dfrac{1}{2}$

$f'(x)$的定義域為$(-\infty, \infty)$



#### Answer

$f'(x)=\dfrac{1}{2}$，$f'(x)$的定義域為$(-\infty, \infty)$



### Exercise 20

#### Statement

Find the derivative of the function using the definition of derivative. 

State the domain of the function and the domain of its derivative.

$f(x) = 1.5x^2 - x + 3.7$



#### Solution

$f(x) = 1.5x^2-x+3.7$

$f'(x) = \dfrac{d}{dx} 1.5x^2 - \dfrac{d}{dx}x + \dfrac{d}{dx} 3.7$

$f'(x) = 3x - 1$

$f'(x)$的定義域為$(-\infty, \infty)$



#### Answer

$f'(x) = 3x-1$，$f'(x)$的定義域為$(-\infty, \infty)$



### Exercise 21

#### Statement

Find the derivative of the function using the definitionof derivative. 

State the domain of the function and the domain of its derivative.

$f(x) = x^2-2x^3$



#### Solution

$f'(x) = \dfrac{d}{dx}x^2 - \dfrac{d}{dx}2x^3$

$f'(x) = 2x - 6x^2$

這是一個多項式，因此$f'(x)$的定義域為$(-\infty, \infty)$



#### Answer

$f'(x) = 2x-6x^2$，定義譽為$(-\infty, \infty)$



### Exercise 22

#### Statement

Find the derivative of the function using the definitionof derivative. 

State the domain of the function and the domain of its derivative.

$g(t) = \dfrac{1}{\sqrt{t}}$



#### Solution

利用除法定理，$\dfrac{d}{dx} \dfrac{f(x)}{g(x)} = \dfrac{g(x)f'(x)-f(x)g'(x)}{g^2(x)}$

$g(t) = \dfrac{1}{\sqrt{t}} = \dfrac{1}{t^{\frac{1}{2}}}$

$g'(t) = \dfrac{t^{\frac{1}{2}}\times 0 - 1\times \dfrac{1}{2}t^{\frac{-1}{2}}}{t} = \dfrac{1}{2}t^\frac{-3}{2}$



#### Answer

$g'(t) = \dfrac{1}{2}t^{\frac{-3}{2}}$



### Exercise 25

#### Statement

Find the derivative of the function using the definitionof derivative. 

State the domain of the function and the domain of its derivative.

$G(t) = \dfrac{1-2t}{3+t}$



#### Solution

利用除法定理，$\dfrac{d}{dx} \dfrac{f(x)}{g(x)} = \dfrac{g(x)f'(x)-f(x)g'(x)}{g^2(x)}$

$G'(t) = \dfrac{(3+t)(-2) - (1-2t)(t)}{(3+t)^2}$

$= \dfrac{-2t-6-(-2t^2-t)}{(3+t)^2}$

$= \dfrac{-2t-6+2t^2+t}{t^2+6t+9}$

$= \dfrac{2t^2-t-6}{t^2+6t+9}$



#### Answer

$G'(t) = \dfrac{2t^2-t-6}{t^2+6t+9}$



### Exercise 31

#### Statement

The unemployment rate $U(t)$ varies with time. The table (from the Bureau of Labor Statistics) gives the percentage of unemployed in the US labor force from 1999 to 2008.

![image-20201013164856189](https://i.imgur.com/BLclawy.png)

(a) What is the meaning of $U'(t)$ ? What are its units?
(b) Construct a table of estimated values for $U'(t)$.



#### Solution

(a) $U'(t)$代表在時間$t$的時候，$U(t)$的變化率，單位為percentage / years。

(b) 

$U'(1999) \approx \dfrac{4.2-4.0}{1999-2000} \approx -0.2$

$U'(2000) \approx \dfrac{4.2-4.7}{1999-2001} \approx 0.25$

$U'(2001) \approx \dfrac{4.0-5.8}{2000-2002} \approx 0.9$

$U'(2002) \approx \dfrac{4.7-6.0}{2001-2003} \approx 0.65$

$U'(2003) \approx \dfrac{5.8-5.5}{2002-2004} \approx -0.15$

$U'(2004) \approx \dfrac{6.0-5.1}{2003-2005} \approx -0.45$

$U' (2005) \approx \dfrac{5.5-4.6}{2004-2006} \approx -0.45$

$U'(2006) \approx \dfrac{5.1-4.6}{2005-2007} \approx -0.25$

$U'(2007) \approx \dfrac{4.6-5.8}{2006-2008} \approx 0.6$

$U'(2008) \approx \dfrac{4.6-5.8}{2007-2008} \approx 1.2$



#### Answer

見Solution。



### Exercise 33

#### Statement

The graph of $f$ is given. State, with reasons, the numbers
at which $f$ is not differentiable.

![image-20201013171740350](https://i.imgur.com/xnQntOq.png)



#### Solution

從圖片上可以得知 ，$x=-4$時不可微，因為尖端不可微。

$x=0$時不可微，因為極限值不存在。

故不可微的點為$\{-4, 0\}$



#### Answer

不可微的點為$\{-4, 0\}$



### Exercise 40

#### Statement

The figure shows graphs of $f$, $f'$, $f''$ and $f'''$.

Identify each curve, and explain your choices.

![image-20201013172536891](https://i.imgur.com/AUybkDB.png)

#### Solution

$c, d$可以看成某函數$d$被微分後就會得到$c$，又因為函數圖形會越微定義域越小，因此我們可以得到$d = f, c = f'$。

$b$與$c$的關聯是$c$的左右端微分後為趨近於無限大，因此與$b$有關聯，因此$b = f''$

$b$的兩端微分後都會遞增，因此我們可以斷定$a = f'''$



#### Answer

$a = f''', b = f'', c = f', d = f$



### Exercise 41

#### Statement

The figure shows the graphs of three functions. One is the position function of a car, one is the velocity of the car, and one is its acceleration. 

Identify each curve, and explain your choices.



#### Solution

考慮$c$為車子的位置函數，那麼速度必定上升後下降，因此我們可以把速度函數考慮成$b$

那麼速度兩端微分都會趨近於0，剛好符合函數$a$的加速度函數，故為$a$



#### Answer

見Solution。



## Sec 3.5

### Exercise 32

#### Statement

Find $y'$ if $\arctan{xy} = 1 + x^2y$



#### Solution

If $\arctan{(xy)} = 1 + x^2y$, find $y'$



$\dfrac{d}{dx} \arctan{(xy)} = \dfrac{d}{dx} 1 + \dfrac{d}{dx} (x^2y)$

Let $u = xy$, s.t. $\dfrac{d}{dx} \arctan{u} = 0 + \dfrac{d}{dx}(x^2y)$

$\dfrac{1}{1+u^2} \dfrac{du}{dx} = \dfrac{d}{dx}(x^2y)$

$\dfrac{1}{1+u^2} \times xy \cdot \dfrac{d}{dx} = x^2\dfrac{d}{dx} y + x^2\cdot y\dfrac{d}{dx}$

$\dfrac{1}{1+(xy)^2} \times (x\dfrac{d}{dx}y + \dfrac{d}{dx}x \cdot y) = 2xy + x^2\dfrac{dy}{dx}$

$\dfrac{1}{1+(xy)^2} \times (x\dfrac{dy}{dx} + y) = 2xy + x^2\dfrac{dy}{dx}$

$\dfrac{x}{1+(xy)^2} \dfrac{dy}{dx} + \dfrac{y}{1+(xy)^2} = 2xy + x^2\dfrac{dy}{dx}$

$(\dfrac{x}{1+(xy)^2} - x^2) \dfrac{dy}{dx} = 2xy - \dfrac{y}{1+(xy)^2}$

$\dfrac{dy}{dx} = \dfrac{2xy - \dfrac{y}{1-(xy)^2}}{\dfrac{x}{1+(xy)^2} - x^2}$

$= \dfrac{(2xy)(1+(xy)^2) - y}{x - x^2(1+(xy)^2)}$

$= \dfrac{2xy + 2(x^3y^3) - y}{x - x^2 - x^4y^2}$



#### Answer

$y' = \dfrac{2xy + 2(x^3y^3) - y}{x - x^2 - x^4y^2}$



### Exercise 33

#### Statement

If $g(x) = x \sin^{-1}(\dfrac{x}{4}) + \sqrt{16 - x^2}$, find $g'(2)$



#### Solution

$g'(x) = \dfrac{x}{dx}(x \sin^{-1} (\dfrac{x}{4})) + \dfrac{x}{dx} \sqrt{16-x^2}$

$ = x \dfrac{x}{dx} \sin^{-1}(\dfrac{x}{4}) + \dfrac{x}{dx}x \cdot \sin^{-1}(\dfrac{x}{4}) + \dfrac{1}{2\sqrt{16-x^2}} \cdot (16-x^2)\dfrac{d}{dx}$

$= x \dfrac{1}{\sqrt{1-(\dfrac{x}{4})^2}} \dfrac{d}{dx}(\dfrac{x}{4}) + \sin^{-1}(\dfrac{x}{4}) + \dfrac{-2x}{2\sqrt{16-x^2}}$

$= \dfrac{x}{\sqrt{1-(\dfrac{x}{4})^2}}\cdot \dfrac{1}{4} + \sin^{-1}(\dfrac{x}{4}) + \dfrac{-x}{\sqrt{16-x^2}}$

$= \dfrac{x}{4\sqrt{1 - \dfrac{x^2}{16}}} + \sin^{-1}(\dfrac{x}{4}) + \dfrac{-x}{\sqrt{16-x^2}}$

$= \dfrac{x}{\sqrt{16-x^2}} + \sin^{-1}(\dfrac{x}{4}) + \dfrac{-x}{\sqrt{16-x^2}}$

$= \sin^{-1}(\dfrac{x}{4})$



$g'(2) = \sin^{-1}(\dfrac{1}{2}) = \dfrac{\pi}{6}$



#### Answer

$g'(2) = \dfrac{\pi}{6}$



### Exercise 34

#### Statement

Find an equation of the tangent line to the curve $y = 3 \arccos(\dfrac{x}{2})$ at the point $(1, \pi)$



#### Solution

$y' = \dfrac{d}{dx}(3 \arccos(\dfrac{x}{2}))$

$ = \dfrac{d}{dx}3 \cdot \arccos(\dfrac{x}{2}) + 3\dfrac{d}{dx}\arccos(\dfrac{x}{2})$

$= - 3 \dfrac{1}{\sqrt{1 - (\dfrac{x}{2})^2}} \cdot \dfrac{d}{dx}\dfrac{x}{2}$

$= \dfrac{-3}{\sqrt{1-\dfrac{x^2}{4}}} \cdot \dfrac{1}{2}$

$= \dfrac{-3}{\sqrt{4-x^2}}$



$y - y_0 = [y'(1)] (x - x_0)$

$y - \pi = \dfrac{-3}{\sqrt{4-1}}(x-1)$

$y - \pi = \dfrac{-3}{\sqrt{3}}(x-1)$

$\sqrt{3}y-\sqrt{3}\pi = -3x+3$

$\sqrt{3}y = -3x+3+\sqrt{3}\pi$

$y = \dfrac{-3x+3+\sqrt{3}\pi}{\sqrt{3}} = -\sqrt{3}x+\sqrt{3}+\pi$



#### Answer

$y = -\sqrt{3}x+\sqrt{3}+\pi$



### Exercise 42

#### Statement

(a) Sketch the graph of the function $f(x) = \sin(\sin^{-1}x)$

(b) Sketch the graph of the function $g(x) = \sin^{-1}(\sin x), x \in \mathbb{R}$

(c) Show that $g'(x) = \dfrac{\cos{x}}{|\cos(x)|}$

(d) Sketch the graph of $h(x) = \cos^{-1}(\sin x), x \in \mathbb{R}$, and find its derivative.



#### Solution

(a) 

![image-20200928010159328](https://i.imgur.com/Hep1wYe.png)

(b)

![image-20200928010356348](https://i.imgur.com/GExxtiF.png)

(c)

$g(x) = \sin^{-1}(\sin x)$

$g'(x) = \dfrac{1}{\sqrt{1-\sin^2x}} \cos(x)$

$g'(x) = \dfrac{1}{|\cos x|} \cos(x) = \dfrac{\cos(x)}{|\cos(x)|}$



(d)

![image-20200928010635692](https://i.imgur.com/Hlq0SD0.png)

$h(x) = \cos^{-1}(\sin x)$

$h'(x) = \dfrac{-1}{\sqrt{1 - \sin^2x}}\cos(x) = -\dfrac{-\cos(x)}{|\cos(x)|}$



#### Answer

(a) 圖在Solution中

(b) 圖在Solution中

(c) 證明在Solution中

(d) 圖在Solution中，$h'(x) = -\dfrac{-\cos(x)}{|\cos(x)|}$



## Sec 3.7

### Exercise 15

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x3^x}{3^x-1}$



#### Solution

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x3^x}{3^x-1} = \displaystyle \lim_{x\rightarrow 0} \dfrac{x}{1-3^{-x}} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1}{-1(-1\times 3^{-x} \ln 3)} = \dfrac{1}{\ln3}$



#### Answer

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x3^x}{3^x-1} = \dfrac{1}{\ln 3}$



### Exercise 17

#### Statment

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 1} \dfrac{1-x+\ln x}{1+\cos \pi x}$



#### Solution

$\displaystyle \lim_{x\rightarrow 1} \dfrac{1-1+\ln 1}{1+\cos\pi} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule

$\displaystyle \dfrac{\dfrac{d}{dx}{1-x+\ln x}}{\dfrac{d}{dx}(1+\cos\pi x)} = \dfrac{0-1+\dfrac{1}{x}}{0-\pi\sin\pi x} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule again

$\dfrac{\dfrac{d}{dx}-1+\dfrac{1}{x}}{\dfrac{d}{dx}-\pi\sin\pi x} = \dfrac{\dfrac{1}{x^2}}{-\pi^2\cos\pi x} = \dfrac{1}{-\pi^2}$



Therefore, $\displaystyle \lim_{x\rightarrow 1} \dfrac{1-x+\ln x}{1 + \cos \pi x} = -\dfrac{1}{\pi^2}$



#### Answer

$\displaystyle \lim_{x\rightarrow 1} \dfrac{1-x+\ln x}{1 + \cos \pi x} = -\dfrac{1}{\pi^2}$



### Exercise 18

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 0}\dfrac{1}{\tan^{-1}(4x)}$



#### Solution

$\displaystyle \lim_{x\rightarrow 0}\dfrac{1}{\tan^{-1}(4x)} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1}{4\times \dfrac{1}{1+(4x)^2}} = \displaystyle \lim_{x\rightarrow 0} \dfrac{1+16x^2}{4} = \dfrac{1}{4}$



#### Answer

$\displaystyle \lim_{x\rightarrow 0}\dfrac{1}{\tan^{-1}(4x)} = \dfrac{1}{4}$



### Exercise 22

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow a^+} \dfrac{\cos x \ln(x-a)}{\ln(e^x-e^a)}$



#### Solution

$\displaystyle \lim_{x\rightarrow a^+} \dfrac{\cos x \ln(x-a)}{\ln(e^x-e^a)} = \cos x \displaystyle \color{red}{\lim_{x\rightarrow a^+} \dfrac{\ln(x-a)}{\ln(e^x-e^a)}}$

$\displaystyle{\lim_{x\rightarrow a^+} \dfrac{\ln(x-a)}{\ln(e^x-e^a)} = \dfrac{0}{0}}$, s.t. we can use L'Hospital's Rule.

$\cos x \displaystyle {\lim_{x\rightarrow a^+} \dfrac{\ln(x-a)}{\ln(e^x-e^a)}} = \cos a \displaystyle \lim_{x\rightarrow a^+} \dfrac{\dfrac{1}{x-a}}{\dfrac{e^x}{e^x-e^a}} = \cos a \color{red}{\lim_{x\rightarrow a^+} \dfrac{e^x-e^a}{x-a}}\color{black}{ \times \lim_{x\rightarrow a^+} \dfrac{1}{e^x}}$

$\displaystyle \color{black}{\lim_{x\rightarrow a^+} \dfrac{e^x-e^a}{x-a}} = \dfrac{0}{0}$, s.t. we can use L'Hospital's Rule.

$\cos a \times \displaystyle\lim_{x\rightarrow a^+}\dfrac{e^x}{1} \times  \lim_{x\rightarrow a^+}\dfrac{1}{e^x} = \cos a \times \dfrac{e^a}{1}\times \dfrac{1}{e^a} = \cos a$



Therefore, $\displaystyle \lim_{x\rightarrow a^+} \dfrac{\cos x \ln(x-a)}{\ln(e^x-e^a)} = \cos a$

#### Answer

$\displaystyle \lim_{x\rightarrow a^+} \dfrac{\cos x \ln(x-a)}{\ln(e^x-e^a)} = \cos a$

### Exercise 25

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow \infty} x^3e^{-x^2}$



#### Solution

$\displaystyle \lim_{x\rightarrow \infty} x^3 e^{-x^2} = \infty \cdot 0$

s.t. we can rearrange the formula.

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^3}{\dfrac{1}{e^{-x^2}}} = \lim_{x\rightarrow \infty} \dfrac{x^3}{e^{x^2}} = \dfrac{\infty}{\infty}$

s.t we can use L'Hospital's Rule

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{3x^2}{2x e^{x^2}} = \lim_{x\rightarrow \infty} \dfrac{3x}{2e^{x^2}} = \dfrac{3}{2} \color{red}{\lim_{x\rightarrow \infty} \dfrac{x}{e^{x^2}}}$



$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x}{e^{x^2}} = \dfrac{\infty}{\infty}$

s.t we can use L'Hospital's Rule

$\dfrac{3}{2} \displaystyle \lim_{x\rightarrow \infty} \dfrac{1}{2xe^{x^2}} = \dfrac{3}{2}\cdot\dfrac{1}{\infty} = 0$



Therefore, $\displaystyle \lim_{x\rightarrow \infty} x^3e^{-x^2} = 0$



#### Answer

$\displaystyle \lim_{x\rightarrow \infty} x^3e^{-x^2} = 0$



### Exercise 27

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 1^+} \ln x \tan(\dfrac{\pi x}{2})$



#### Solution

$\displaystyle \lim_{x\rightarrow 1^+} \ln x \tan(\dfrac{\pi x}{2}) = 0\times \infty$

s.t. we can rearrange formula.

$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{\ln x}{\dfrac{1}{\tan(\dfrac{\pi x}{2})}} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule

$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{\ln x}{\dfrac{1}{\tan(\dfrac{\pi x}{2})}} = \lim_{x\rightarrow 1^+} \dfrac{\ln x}{\cot(\dfrac{\pi x}{2})} = -\dfrac{\dfrac{1}{x}}{\dfrac{\pi}{2}\csc^2(\dfrac{\pi x}{2})} = -\dfrac{2}{\pi}$



#### Answer

$\displaystyle \lim_{x\rightarrow 1^+} \ln x \tan(\dfrac{\pi x}{2}) = \dfrac{-2}{\pi}$



### Exercise 29

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 0^+}(\dfrac{1}{x}-\dfrac{1}{e^x-1})$



#### Solution

$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{e^x-x-1}{x(e^x-1)} = \lim_{x\rightarrow 0^+}\dfrac{e^x-x-1}{xe^x-x} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule

$\displaystyle \lim_{x\rightarrow 0^+}\dfrac{e^x-1}{e^x+xe^x-1} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule again

$\displaystyle \lim_{x\rightarrow 0^+}\dfrac{e^x}{e^x+e^x+xe^x} = \dfrac{1}{2}$



#### Answer

$\displaystyle \lim_{x\rightarrow 0^+}(\dfrac{1}{x}-\dfrac{1}{e^x-1}) = \dfrac{1}{2}$



### Exercise 32

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 1^+} [\ln(x^7-1)-\ln(x^5-1)]$



#### Solution

$\displaystyle \lim_{x\rightarrow 1^+} [\ln(x^7-1) - \ln(x^5-1)]$

$ = \displaystyle \lim_{x\rightarrow 1^+} \ln(\dfrac{x^7-1}{x^5-1})$

$y = \ln(\dfrac{x^7-1}{x^5-1}) \iff e^y = \dfrac{x^7-1}{x^5-1}$



$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{x^7-1}{x^5-1} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule

$\displaystyle \lim_{x \rightarrow 1^+} \dfrac{\dfrac{d}{dx} x^7-1}{\dfrac{d}{dx} x^5-1} = \lim_{x\rightarrow 1^+}\dfrac{7x^6}{5x^4} = \lim_{x\rightarrow 1^+}\dfrac{7}{5}x^2 = \dfrac{7}{5}$

$e^y = \dfrac{7}{5} \iff y = \ln(\dfrac{7}{5})$

$\therefore \displaystyle \lim_{x\rightarrow 1^+} [\ln(x^7-1) - \ln(x^5-1)] = \ln(\dfrac{7}{5})$



#### Answer

$\displaystyle \lim_{x\rightarrow 1^+} [\ln(x^7-1) - \ln(x^5-1)] = \ln(\dfrac{7}{5})$



### Exercise 34

#### Statement

Find the limit. Use l’Hospital’s Rule where appropriate. If there is a more elementary method, consider using it. If l’Hospital’s
Rule doesn’t apply, explain why.

$\displaystyle \lim_{x\rightarrow 0^+} (\tan 2x)^x$



#### Solution

$y = (\tan(2x))^x,\ \ln(y) = \ln(\tan(2x)^x)$

$= x\ln(\tan(2x))$



$\displaystyle \lim_{x\rightarrow 0} x\ln(\tan(2x))$

$\because \displaystyle \lim_{x\rightarrow 0} x\ln(\tan(2x)) = 0\cdot -\infty$

$\therefore \displaystyle \lim_{x\rightarrow 0} \dfrac{\ln(\tan(2x))}{\dfrac{1}{x}} = \dfrac{0}{0}$

s.t. we can use L'Hosptial's Rule

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\dfrac{d}{dx} \ln(\tan(2x))}{\dfrac{d}{dx} \dfrac{1}{x}} = \lim_{x\rightarrow 0} \dfrac{\dfrac{1}{\tan2x} \dfrac{d}{dx} \tan 2x }{\dfrac{-1}{x^2}} = \lim_{x\rightarrow 0} \dfrac{\dfrac{2\sec^22x}{\tan2x}}{\dfrac{-1}{x^2}} = \lim_{x\rightarrow 0} \dfrac{2\sec^2 2x\cdot x^2}{\tan 2x}$

$= \displaystyle \lim_{x\rightarrow 0} -2\sec^2 2x\cdot x^2 \cdot \dfrac{\cos 2x}{\sin 2x} = \lim_{x\rightarrow 0} \dfrac{-2\sec2x\cdot x^2}{\sin 2x} = \lim_{x\rightarrow 0} \dfrac{-2x^2}{\sin2x}\cdot \lim_{x\rightarrow 0}\sec2x$

$\displaystyle = \lim_{x\rightarrow 0} \dfrac{-2x^2}{\sin 2x} = \dfrac{0}{0}$

s.t. we can use L'Hospital's Rule again.

$\displaystyle \lim_{x\rightarrow 0} \dfrac{-2x^2}{\sin 2x} = \lim_{x\rightarrow 0} \dfrac{-4x}{2\cos2x} = 0$



Therefore $\ln(y) = 0, y = 1$

#### Answer

$\displaystyle \lim_{x\rightarrow 0^+} (\tan 2x)^x  = 1$



