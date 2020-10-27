# 微積分Practice Ch2

###### tags: `微積分題目紀錄`

## Sec 2.1

### Exercise 1

#### Statement

判斷函數在下列各點是否可微分？

$f(x) = \left\{\begin{array}\ x+2, & x \le 0 \\ 2-3x, & x > 0\end{array}\right.$，$(0, 2)$



#### Solution

$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$

已知$f(0) = 2$，欲求$x=0$是否可微分，則考慮$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)-f(0)}{x}$，由於$0^+>0$，所以$f(x) = 2-3x$

因此$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{2-3x-2}{x} = \displaystyle \lim_{x\rightarrow 0^+} \dfrac{-3x}{x} = \lim_{x\rightarrow 0^+} -3 = -3$



考慮$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{f(x)-f(0)}{x}$，由於$0^-<0$，所以$f(x) = x+2$

因此$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{x+2-2}{x} = \displaystyle \lim_{x\rightarrow 0^-} \dfrac{x}{x} = \lim_{x\rightarrow 0^-} 1 = 1$



根據極限定義，得到$\displaystyle \lim_{x\rightarrow 0^+} f(x) \neq \lim_{x\rightarrow 0^-} f(x)$

因此$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x}$不存在，故在點$(0, 2)$不可微。



#### Answer

不可微。



### Exercise 2

#### Statement

判斷函數在下列各點是否可微分？

$f(x) = \sqrt[3]{x^2}$，$(0, 0)$



#### Solution

$f(x) = \sqrt[3]{x^2} = x^\frac{2}{3}$

$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$

已知$f(0) = 0$，欲求$x=0$是否可微分，則考慮$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x}$是否存在。

考慮$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)-f(0)}{x-0} = \lim_{x\rightarrow 0^+} \dfrac{x^\frac{2}{3}}{x} = \lim_{x\rightarrow 0^+} x^\frac{-1}{3} = \lim_{x\rightarrow 0^+} \dfrac{1}{\sqrt[3]{x}} = +\infty$

考慮$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{f(x)-f(0)}{x-0} = \lim_{x\rightarrow 0^-} \dfrac{x^\frac{2}{3}}{x} = \lim_{x\rightarrow 0^-} x^\frac{-1}{3} = \lim_{x\rightarrow 0^-} \dfrac{1}{\sqrt[3]{x}} = -\infty$



根據極限定義，得到$\displaystyle \lim_{x\rightarrow 0^+} f(x) \neq \lim_{x\rightarrow 0^-} f(x)$

因此$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x}$不存在，故在點$(0, 0)$不可微。



#### Answer

不可微。



### Exercise 3

#### Statement

判斷函數在下列各點是否可微分？

$f(x) = \left\{\begin{array}\ x+1, & x \le 0 \\ x^2+x+1, & x > 0\end{array}\right.$，$(0, 1)$



#### Solution

$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$

已知$f(0) = 1$，欲求$x=0$是否可微分，則考慮$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)-f(0)}{x}$，由於$0^+>0$，所以$f(x) = x+1$

因此$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{x+1-1}{x} = \displaystyle \lim_{x\rightarrow 0^+} \dfrac{x}{x} = \lim_{x\rightarrow 0^+} 1 = 1$



考慮$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{f(x)-f(0)}{x}$，由於$0^-<0$，所以$f(x) = x^2+x+1$

因此$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{x^2+x+1-1}{x} = \displaystyle \lim_{x\rightarrow 0^-} \dfrac{x^2+x}{x} = \lim_{x\rightarrow 0^-} x+1 = 1$



根據極限定義，得到$\displaystyle \lim_{x\rightarrow 0^+} f(x) = \lim_{x\rightarrow 0^-} f(x)$

因此$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x}$存在，故在點$(0, 1)$可微。



### Exercise 4

#### Statement

判斷函數在下列各點是否可微分？

$f(x) = |2x-4|$，$(2, 0)$



#### Solution

$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$

已知$f(2) = 0$，欲求$x=2$是否可微分，則考慮$\displaystyle \lim_{x\rightarrow 2} \dfrac{f(x)-f(2)}{x - 2}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{f(x)-f(2)}{x - 2}$，得到$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{|2x-4|}{x - 2}$

由於$2^+ > 2$，因此$2x-4 > 0$，所以$|2x-4| = 2x-4$

$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{2x-4}{x - 2} = \displaystyle \lim_{x\rightarrow 2^+} \dfrac{2(x-2)}{x - 2} = \displaystyle \lim_{x\rightarrow 2^+} 2 = 2$



考慮$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{f(x)-f(2)}{x - 2}$，得到$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{|2x-4|}{x - 2}$

由於$2^- < 2$，因此$2x-4 < 0$，所以$|2x-4| = -2x+4$

$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{-2x+4}{x - 2} = \displaystyle \lim_{x\rightarrow 2^-} \dfrac{-2(x-2)}{x - 2} = \displaystyle \lim_{x\rightarrow 2^-} -2 = -2$



根據極限定義，得到$\displaystyle \lim_{x\rightarrow 2^+} f(x) \neq \lim_{x\rightarrow 2^-} f(x)$

因此$\displaystyle \lim_{x\rightarrow 2} \dfrac{f(x)-f(2)}{x-2}$不存在，故在點$(2, 0)$不可微。



#### Answer

不可微。



### Exercise 5

#### Statement

若$f(x) = \left\{\begin{array}\ x\sin\dfrac{1}{x}, & x \not= 0 \\ 0, & x = 0\end{array}\right.$，求$(0, 0)$是否可微。



#### Solution

微分定義$f'(a)$可微時$\displaystyle f'(a) = \lim_{x\rightarrow a} \dfrac{f(x) - f(a)}{x-a}$存在。

因此我們考慮$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x-0} = \displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-0}{x-0} = \lim_{x\rightarrow 0} \dfrac{f(x)}{x}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)}{x}$，其中$x \neq 0$，所以$f(x) = x\sin\dfrac{1}{x}$

$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{x\sin\dfrac{1}{x}}{x} = \lim_{x\rightarrow 0^+} \sin\dfrac{1}{x} = D.N.E$



考慮$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{f(x)}{x}$，其中$x \neq 0$，所以$f(x) = x\sin\dfrac{1}{x}$

$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{x\sin\dfrac{1}{x}}{x} = \lim_{x\rightarrow 0^-} \sin\dfrac{1}{x} = D.N.E$



因此$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)}{x}$不存在，故不可微。



#### Answer

$f(x)$在點$(0, 0)$時不可微。



### Exercise 6

#### Statement

若$f(x) = \left\{\begin{array}\ x^2\sin\dfrac{1}{x}, & x \not= 0 \\ 0, & x = 0\end{array}\right.$，求$(0, 0)$是否可微。



#### Solution

微分定義$f'(a)$可微時$\displaystyle f'(a) = \lim_{x\rightarrow a} \dfrac{f(x) - f(a)}{x-a}$存在。

因此我們考慮$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-f(0)}{x-0} = \displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)-0}{x-0} = \lim_{x\rightarrow 0} \dfrac{f(x)}{x}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{f(x)}{x}$，其中$x \neq 0$，所以$f(x) = x^2\sin\dfrac{1}{x}$

$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{x^2\sin\dfrac{1}{x}}{x} = \lim_{x\rightarrow 0^+} x\sin\dfrac{1}{x}$

利用夾擠定理，我們可以知道$-1 \le \sin\dfrac{1}{x} \le 1$

因此$- |x| \le x\sin\dfrac{1}{x} \le |x|$

共同取$\displaystyle \lim_{x\rightarrow 0^+}$，得到$\displaystyle \lim_{x\rightarrow 0^+}- |x| \le \displaystyle \lim_{x\rightarrow 0^+} x\sin\dfrac{1}{x} \le \displaystyle \lim_{x\rightarrow 0^+} |x|$

因此$-0 \le \displaystyle \lim_{x\rightarrow 0^+} x\sin\dfrac{1}{x} \le 0$，因此$\displaystyle \lim_{x\rightarrow 0^+} x\sin\dfrac{1}{x} = 0$



考慮$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{f(x)}{x}$，其中$x \neq 0$，所以$f(x) = x^2 \sin\dfrac{1}{x}$

$\displaystyle \lim_{x\rightarrow 0^-} \dfrac{x^2\sin\dfrac{1}{x}}{x} = \lim_{x\rightarrow 0^-} x\sin\dfrac{1}{x}$

利用夾擠定理，我們可以知道$-1 \le \sin\dfrac{1}{x} \le 1$

因此$- |x| \le x\sin\dfrac{1}{x} \le |x|$

共同取$\displaystyle \lim_{x\rightarrow 0^-}$，得到$\displaystyle \lim_{x\rightarrow 0^-}- |x| \le \displaystyle \lim_{x\rightarrow 0^-} x\sin\dfrac{1}{x} \le \displaystyle \lim_{x\rightarrow 0^-} |x|$

因此$-0 \le \displaystyle \lim_{x\rightarrow 0^-} x\sin\dfrac{1}{x} \le 0$，因此$\displaystyle \lim_{x\rightarrow 0^-} x\sin\dfrac{1}{x} = 0$



因此$\displaystyle \lim_{x\rightarrow 0} \dfrac{f(x)}{x} = 0$，故可微。



#### Answer

$f(x)$可微。



### Exercise 7

#### Statement

若$f'(1) = 3$，求$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1-h)-f(1)}{h}$。



#### Solution

令$t=-h$，因此$\displaystyle \lim_{t\rightarrow 0} \dfrac{f(1+t)-f(1)}{-t} = \displaystyle \lim_{t\rightarrow 0} -\dfrac{f(1+t)-f(1)}{t} = -\displaystyle \lim_{t\rightarrow 0} \dfrac{f(1+t)-f(1)}{t} = -f'(1) = -3$



#### Answer

$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1-h)-f(1)}{h} = -3$



### Exercise 8

#### Statement

若$g'(2) = 1$，求$\displaystyle \lim_{h\rightarrow 0} \dfrac{g(2+3h)-g(2)}{h}$。



#### Solution

令$t=3h$，則$\displaystyle \lim_{t\rightarrow 0} \dfrac{g(2+t)-g(2)}{\dfrac{1}{3}t} = \displaystyle \lim_{t\rightarrow 0} 3\dfrac{g(2+t)-g(2)}{t} = \displaystyle 3 \lim_{t\rightarrow 0} \dfrac{g(2+t)-g(2)}{t} = 3g'(2) = 3$

#### Answer

$\displaystyle \lim_{h\rightarrow 0} \dfrac{g(2+3h)-g(2)}{h} = 3$



### Exercise 9

#### Statement

若$f'(1)=2$，求$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1-h)}{h}$



#### Solution



改寫成$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1) - (f(1-h)-f(1))}{h}$

利用極限四則運算定義，$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1)}{h} - \lim_{h\rightarrow 0} \dfrac{f(1-h)-f(1)}{h}$



考慮$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1)}{h}$，得到$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1)}{h} = f'(1) = 2$

考慮$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1-h)-f(1)}{h}$，代換成$\displaystyle \lim_{t\rightarrow -h}$，得到$\displaystyle \lim_{t\rightarrow -h} \dfrac{f(1+t)-f(1)}{-t} = -f'(1) = -2$



因此$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1-h)}{h} = \displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1)}{h} - \lim_{h\rightarrow 0} \dfrac{f(1-h)-f(1)}{h} = 2 - (-2) = 4$ 



### Exercise 10

#### Statement

已知$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(3+h)-f(3-h)}{h}=6$，求$f'(3)$



#### Solution

$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(3+h)-f(3-h)}{h}=6$

$=\displaystyle \lim_{h\rightarrow 0} \dfrac{f(3+h)-f(3)-(f(3-h)-f(3))}{h}=6$

$=\displaystyle \lim_{h\rightarrow 0} [\dfrac{f(3+h)-f(3)}{h}-\dfrac{(f(3-h)-f(3))}{h}]=6$

$=\displaystyle \lim_{h\rightarrow 0} (\dfrac{f(3+h)-f(3)}{h})-\lim_{h\rightarrow 0}(\dfrac{(f(3-h)-f(3))}{h})=6$

$\displaystyle = f'(3) - \lim_{h\rightarrow 0}(\dfrac{(f(3-h)-f(3))}{h}) = 6$

令$h = -t$，則

$\displaystyle = f'(3) - \lim_{t\rightarrow 0}(\dfrac{(f(3+t)-f(3))}{-t}) = 6$

$\displaystyle = f'(3) + \lim_{t\rightarrow 0}(\dfrac{(f(3+t)-f(3))}{t}) = 6$

$\displaystyle = f'(3) + \lim_{t\rightarrow 0}(\dfrac{(f(3+t)-f(3))}{t}) = 6$

$\displaystyle = f'(3) + f'(3) = 2f'(3) = 6$

$f'(3) = 3$



#### Answer

$f'(3) = 3$



### Exercise 11

#### Statement

若函數$f$的圖形在$x=2$的切線與$x$軸截距為$3$，與$y$軸截距為$2$，求$f(2)$和$f'(2)$



#### Solution

利用截距式來造出直線方程式。

$\dfrac{x}{3}+\dfrac{y}{2} = 1$

$2x+3y=6$，代入$x=2$得到$y=\dfrac{2}{3} = f(2)$

$f$在$x=2$微分所得到的$f'(2)$，等於$x=2$時的微分切線斜率，故為直線斜率。

所以$m = \dfrac{-2}{3} = f'(2)$



#### Answer

$f(2) = \dfrac{2}{3}$

$f'(2) = -\dfrac{2}{3}$



### Exercise 12

#### Statement

若$f(1) = 3$且$f$圖形在$x=1$的切點通過點$(0, -2)$，求$f'(1)$



#### Solution

$f(1) = 3$，可以知道$f$過點$(1, 3)$

因此我們可以造出過點$x=1$的切線方程式，過點$(1,3)$與$(0, -2)$



$y + 2 = \dfrac{-2-3}{0-1}x \Rightarrow y+2 = 5x$

故$-5x+y+2=0$

斜率$m = \dfrac{-(-5)}{1} = 5 = f'(1)$



因此$f'(1) =5$



#### Answer

$f'(1) =5$



### Exercise 13

#### Statement

假設$f(x) = \left\{\begin{array}\ x^2, & x \le 1 \\ mx+b, & x > 1\end{array}\right.$且$f$處處可微分，求$m$和$b$之值。



#### Solution

由於兩個複合函數都是多項式函數，故處處可微分。

因此我們只需要考量複合函數的接點是否可微即可。



$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$

已知$f(1) = 1$，欲求$x=1$是否可微分，則考慮$\displaystyle \lim_{x\rightarrow 1} \dfrac{f(x)-f(1)}{x - 1}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 1^-} \dfrac{f(x)-f(1)}{x - 1}$，由於$1^-<1$，所以$f(x)= x^2$

因此$\displaystyle \lim_{x\rightarrow 1^-} \dfrac{x^2-1}{x-1} = \displaystyle \lim_{x\rightarrow 1^-} \dfrac{(x-1)(x+1)}{x-1} = \lim_{x\rightarrow 1^-} x+1 = 2$



考慮$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{f(x)-f(1)}{x-1}$，由於$1^+>1$，所以$f(x) = mx+b$

因此$\displaystyle \lim_{x\rightarrow 1^+} \dfrac{mx+b-1}{x-1}$



考慮分母必須要能夠被分子整除，極限值才會存在。

考慮極限定義，因此$\displaystyle \lim_{x\rightarrow 1^-} \dfrac{f(x)-f(1)}{x} = \displaystyle \lim_{x\rightarrow 1^+} \dfrac{f(x)-f(1)}{x-1}$

又上下皆為一次函數，故上下同除後必為常數，因此我們要使$\dfrac{mx+b-1}{x-1} = 2$

因此$mx+b-1 = 2x-2$，可以得知$m = 2$且$b=-1$



#### Answer

$m = 2,\ b = -1$



### Exercise 14

#### Statement

假設$f(x) = \left\{\begin{array}\ \dfrac{1}{3-x}, & x < 2 \\ 3-x, & x \ge 2\end{array}\right.$，試問$f$在$x=2$是否可微分？



#### Solution



$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$

已知$f(2) = 1$，欲求$x=2$是否可微分，則考慮$\displaystyle \lim_{x\rightarrow 2} \dfrac{f(x)-f(2)}{x - 2}$是否存在。



考慮$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{f(x)-f(2)}{x-2}$，由於$2^-<2$，所以$f(x)= \dfrac{1}{3-x}$

因此$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{\dfrac{1}{3-x}-1}{x-2} = \lim_{x\rightarrow 2^-} \dfrac{\dfrac{1-(3-x)}{3-x}}{x-2} = \lim_{x\rightarrow 2^-} \dfrac{\dfrac{-2+x}{3-x}}{x-2} = \lim_{x\rightarrow 2^-} \dfrac{1}{3-x} = \dfrac{1}{3-2} = 1$



考慮$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{f(x)-f(2)}{x-2}$，由於$2^+>2$，所以$f(x)= 3-x$

因此$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{3-x-1}{x-2}  = \lim_{x\rightarrow 2^+} \dfrac{2-x}{x-2} = \lim_{x\rightarrow 2^+} -1 = -1$



根據極限定義，得到$\displaystyle \lim_{x\rightarrow 2^+} f(x) \neq \lim_{x\rightarrow 2^-} f(x)$

因此$\displaystyle \lim_{x\rightarrow 2} \dfrac{f(x)-f(2)}{x-2}$不存在，$f$在$x=2$不可微。



#### Answer

不可微。



### Exercise 15

#### Statement

假設$f(x) = \left\{\begin{array}\ x^3+1, & x < 2 \\ mx+b, & x \ge 2\end{array}\right.$，且$f$處處可微分，求$m, b$之值



#### Solution

在複合函數中，每個函數均為多項式，故處處可微。

只需要考慮複合函數的接點是否可微即可。



$f'(a) = \displaystyle \lim_{x\rightarrow a} \dfrac{f(x)-f(a)}{x-a}$，考慮$\displaystyle \lim_{x\rightarrow 2} \dfrac{f(x)-f(2)}{x-2}$是否存在。

$f(2) = 2m+b$

考慮$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{f(x)-f(2)}{x-2}$，$2^- < 2$，因此$f(x) = x^3+1$

所以得到$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{x^3+1 - (2m+b)}{x-2}$

又$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{x^3+1 - (2m+b)}{x-2}$必須要能夠被$x-2$整除

因此得到$\displaystyle \lim_{x\rightarrow 2^-} x^2+2x+4$，且$9-2m-b = 0 \Rightarrow 2m+b=9$

因此$\displaystyle \lim_{x\rightarrow 2^-} x^2+2x+4 = 2^2+2\times 2 + 4 = 12$



考慮$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{f(x)-f(2)}{x-2}$，$2^+ > 2$，因此$f(x) = mx+b$

所以$\displaystyle \lim_{x\rightarrow 2^+} \dfrac{mx+b-(2m+b)}{x-2} = \lim_{x\rightarrow 2^+} \dfrac{mx-2m}{x-2} = \lim_{x\rightarrow 2^+} m\dfrac{x-2}{x-2} = \lim_{x\rightarrow 2^+} m = m$



若$f$在$x=2$可微，則$\displaystyle \lim_{x\rightarrow 2} \dfrac{f(x)-f(2)}{x-2}$存在。

故$\displaystyle \lim_{x\rightarrow 2^-} \dfrac{f(x)-f(2)}{x-2} = \displaystyle \lim_{x\rightarrow 2^+} \dfrac{f(x)-f(2)}{x-2}$，因此$m = 12$

又$2m+b=9$，所以$24+b=9 \Rightarrow b = -15$



#### Answer

$m = 12, b = -15$



### Exercise 16

#### Statement

若$f$在$x=1$連續且$\displaystyle \lim_{x\rightarrow 1} \dfrac{[f(x)]^2-4}{x-1} = 6$，求$f'(1)$



#### Solution

$f'(1) = \displaystyle \lim_{x\rightarrow 1} \dfrac{f(x)-f(1)}{x-1}$

 $\displaystyle \lim_{x\rightarrow 1} \dfrac{[f(x)]^2-4}{x-1} = \dfrac{(f(x)-2)(f(x)+2)}{x-1}$

我們可以考慮成

當$f(1) = 2$時，$\displaystyle \lim_{x\rightarrow 1} \dfrac{[f(x)]^2-4}{x-1} =  \lim_{x\rightarrow 1} \dfrac{(f(x)-2)}{x-1} \cdot \lim_{x\rightarrow 1} (f(x)+2) = f'(1)\cdot \lim_{x\rightarrow 1}(f(x)+2) = 6$

當$f(1) = -2$時，$\displaystyle \lim_{x\rightarrow 1} \dfrac{[f(x)]^2-4}{x-1} =  \lim_{x\rightarrow 1} \dfrac{(f(x)+2)}{x-1} \cdot \lim_{x\rightarrow 1} (f(x)-2) = f'(1) \cdot \lim_{x \rightarrow 1} (f(x)-2) = 6$

又因$\displaystyle \lim_{x\rightarrow 1} \dfrac{[f(x)]^2-4}{x-1} = 6$ 極限存在，當$\displaystyle \lim_{x\rightarrow 1} (x-1) = 0$時，$\displaystyle \lim_{x\rightarrow 1} [f(x)]^2-4=[f(1)]^2-4=0$，得到$f(1) = \pm 2$

當$f(1) = 2$時，$f'(1) \cdot \displaystyle  \lim_{x\rightarrow 1} (f(x) + 2) = f'(1) \cdot (f(1)+2) = f'(1) \cdot 4 = 6$，得到$f'(1) = \dfrac{3}{2}$

當$f(1) = -2$時，$f'(1) \cdot \displaystyle  \lim_{x\rightarrow 1} (f(x) - 2) = f'(1) \cdot (f(1)-2) = f'(1) \cdot (-4) = 6$，得到$f'(1) = \dfrac{-3}{2}$

因此$f'(1) = \dfrac{3}{2}$或者$\dfrac{-3}{2}$



#### Answer

$\dfrac{-3}{2}$或$\dfrac{3}{2}$



### Exercise 17

#### Statement

若$f$在$x=2$連續且$\displaystyle \lim_{x\rightarrow 2} \dfrac{[f(x)]^3-8}{x^2-4} = 6$，求$f'(2)$



#### Solution

$\displaystyle \lim_{x\rightarrow 2} \dfrac{[f(x)]^3-8}{x^2-4} = \lim_{x\rightarrow 2} \dfrac{(f(x)-2)([f(x)]^2+2x+4)}{(x-2)(x+2)} = \lim_{x\rightarrow 2} \dfrac{f(x)-2}{x-2} \cdot \lim_{x\rightarrow 2} \dfrac{[f(x)]^2+2f(x)+4}{x+2}$

$= f'(2) \cdot \displaystyle \lim_{x\rightarrow 2} \dfrac{[f(x)]^2+2f(x)+4}{x+2} = 6$



由於$\displaystyle \lim_{x\rightarrow 2} \dfrac{[f(x)]^3-8}{x^2-4}=6$極限存在，因此當$\displaystyle \lim_{x\rightarrow 2} (x^2-4) = 0$，則$\displaystyle \lim_{x\rightarrow 2} [f(x)]^3-8=0$

因此$[f(2)]^3-8 = 0,\ f(2) = 2$



故$f'(2) \cdot \displaystyle \lim_{x\rightarrow 2} \dfrac{[f(x)]^2+2f(x)+4}{x+2} = f'(2) \cdot \dfrac{[f(2)]^2+2f(2)+4}{4} = f'(2) \cdot \dfrac{12}{4}= 6$

因此$f'(2) = 2$



#### Answer

$f'(2) = 2$



### Exercise 18

#### Statement

若$f$在$x = 1$連續且$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+2h)-f(1-3h)}{h} = 10$，求$f'(1)$



#### Solution

考慮$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+2h)-f(1-3h)}{h} = 10$

改寫成$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+2h)-f(1)-(f(1-3h)-f(1))}{h} = 10$

利用極限四則運算，分解成$\displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+2h)-f(1)}{h}-\lim_{h\rightarrow 0}\dfrac{f(1-3h)-f(1)}{h} = 10$

令$t=2h, v= -3h$，則

$\displaystyle \lim_{t\rightarrow 0} \dfrac{f(1+t)-f(1)}{\dfrac{1}{2}t}-\lim_{v\rightarrow 0}\dfrac{f(1+v)-f(1)}{\dfrac{-1}{3}v} = 10$

$\displaystyle \lim_{t\rightarrow 0} 2\dfrac{f(1+t)-f(1)}{t}-\lim_{v\rightarrow 0}-3\dfrac{f(1+v)-f(1)}{v} = 10$

$\displaystyle 2\lim_{t\rightarrow 0} \dfrac{f(1+t)-f(1)}{t}+3\lim_{v\rightarrow 0}\dfrac{f(1+v)-f(1)}{v} = 10$

利用$f'(x) = \displaystyle \lim_{h\rightarrow 0} \dfrac{f(1+h)-f(1)}{h}$，所以

$2f'(1) + 3f'(1) = 10$，$f'(1) = 2$



#### Answer

$f'(1) = 2$



## Sec 2.2

### Exercise 1

#### Statement

求函數的導函數。

$f(x) = 3x^2-2x+5$



#### Solution

$f'(x) = \dfrac{d}{dx} 3x^2 - \dfrac{d}{dx} 2x + \dfrac{d}{dx} 5$

$= 6x - 2$



#### Answer

$f'(x) = 6x-2$




### Exercise 2

#### Statement

求函數的導函數。

$g(x) = x^{\pi}+\pi x$



#### Solution

$g'(x) = \dfrac{d}{dx}x^{\pi} + \dfrac{d}{dx} \pi x$

$= \pi x^{\pi-1} + \pi$



#### Answer

$g'(x) = \pi x^{\pi-1} + \pi$



### Exercise 3

#### Statement

求函數的導函數。

$g(x) = \dfrac{2x^3-x^2+3}{x}$



#### Solution

$g(x) = \dfrac{2x^3-x^2+3}{x} = 2x^2-x+3x^{-1}$

$g'(x) = \dfrac{d}{dx} 2x^2 - \dfrac{d}{dx} x + \dfrac{d}{dx} 3x^{-1}$

$= 4x - 1 -3x^{-2}$

$= 4x-1-\dfrac{3}{x^2}$



#### Answer

$g'(x) = 4x-1-\dfrac{3}{x^2}$



### Exercise 4

#### Statement

求函數的導函數。

$g(x) = \dfrac{1}{10}x^{10}-4x^\frac{3}{2}+3$




#### Solution

$g'(x) = \dfrac{d}{dx}\dfrac{1}{10}x^{10} - \dfrac{d}{dx}4x^\frac{3}{2} + \dfrac{d}{dx}3$

$ = x^9 - 6x^\frac{1}{2}$

$= x^9-6\sqrt{x}$



#### Answer

$g'(x) = x^9-6\sqrt{x}$



### Exercise 5

#### Statement

求函數的導函數。

$g(x) = 3x-\cos x+\tan x$



#### Solution

$g'(x) = \dfrac{d}{dx} 3x - \dfrac{d}{dx}\cos x + \dfrac{d}{dx} \tan x$

$= 3 - (-\sin x) + \sec^2 x$

$= 3+\sin x + \sec^2x$



#### Answer

$g'(x) = 3 + \sin x + \sec^2 x$



### Exercise 6

#### Statement

求函數的導函數。

$g(x) = 2 - \dfrac{1}{x^2} - \dfrac{2}{x^5}$



#### Solution

$g(x) = 2 - \dfrac{1}{x^2} - \dfrac{2}{x^5} = 2 - x^{-2} - 2x^{-5}$

$g'(x) = \dfrac{d}{dx} 2 - \dfrac{d}{dx} x^{-2} - \dfrac{d}{dx} 2x^{-5}$

$= 0 - (-2x^{-3}) - (-10x^{-6}) = 2x^{-3} + 10x^{-6}$



#### Answer

$2x^{-3} + 10x^{-6}$