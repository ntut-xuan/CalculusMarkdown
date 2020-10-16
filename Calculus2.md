# 微積分Practice Ch2

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


