# 洪揮霖微積分Practice Ch4.3

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = 2x^3-6x$



### Solution

考慮$f'(x) = 6x^2-6, f''(x) = 12x$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \{0\}$

考慮$f''(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$CriticalPoint \in \{0\}$

考慮臨界數將區間分割成上凹與下凹，因此我們考慮區間$(-\infty, 0), (0, \infty)$。

考慮$(-\infty, 0)$，以$-1$考慮$f''(-1)$，可知$f''(-1) < 0$，故在區間$(-\infty, 0)$為下凹。

考慮$(0, \infty)$，以$1$考慮$f''(1)$，可知$f''(1) > 0$，故在區間$(0, \infty)$為上凹。

考慮$x = 0$，左右區間上凹下凹不同，因此反曲點發生在$x = 0$上，也就是點$(0, 0)$。



### Answer

上凹區間：$(0, \infty)$

下凹區間：$(-\infty, 0)$

反曲點：$(0, 0)$



## Exercise 2

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = x^4-4x^3$



### Solution

考慮$f'(x) = 4x^3 - 12x^2, f''(x) = 12x^2 - 24x = 12x(x-2)$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \{0, 2\}$

考慮$f''(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$CriticalPoint \in \{0, 2\}$

上凹下凹曲間由臨界數所分割，故考慮$(-\infty, 0), (0, 2), (2, \infty)$

考慮$(-\infty, 0)$，以$-1$考慮$f''(-1)$，則$f''(-1) > 0$，因此$(-\infty, 0)$上凹。

考慮$(0, 2)$，以$1$考慮$f''(1)$，則$f''(1) < 0$，因此$(0, 2)$下凹。

考慮$(2, \infty)$，以$3$考慮$f''(3)$，則$f''(3) > 0$，因此$(2, \infty)$上凹。

考慮$x = 0$，左右區間上凹下凹不同，因此反曲點發生在$x = 0$上，也就是$(0, 0)$

考慮$x = 2$，左右區間上凹下凹不同，因此反曲點發生在$x = 2$上，也就是$(2, -16)$



### Answer

上凹區間：$(-\infty, 0), (2, \infty)$

下凹區間：$(0, 2)$

反曲點：$(0, 0), (2, -16)$



## Exercise 3

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = 6x^2-x^4$



### Solution

考慮$f'(x) = 12x - 4x^3$，$f''(x) = 12-12x^2 = 12(1-x^2)$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \{1, -1\}$

考慮$f''(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$CriticalPoint \in \{-1, 1\}$

上凹下凹區間通常由臨界數所分割，故考慮$(-\infty, -1), (-1, 1), (1, \infty)$

考慮$(-\infty, -1)$，以$-2$考慮$f''(-2)$，可知$f''(-2) < 0$，因此$(-\infty, -1)$下凹。

考慮$(-1, 1)$，以$0$考慮$f''(0)$，可知$f''(0) > 0$，因此$(-1, 1)$上凹。

考慮$(1, \infty)$，以$2$考慮$f''(2)$，可知$f''(2) < 0$，因此$(2, \infty)$下凹。

考慮$x = -1$，左右區間上凹下凹不同，因此反曲點發生在$x = -1$上，也就是$(-1, 5)$

考慮$x = 1$，左右區間上凹下凹不同，因此反曲點發生在$x = 1$上，也就是$(1, 5)$



### Answer

上凹區間：$(-1, 1)$

下凹區間：$(-\infty, -1), (2, \infty)$

反區點：$(1, 5), (-1, 5)$



## Exercise 4

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = 3x^2 + \dfrac{2}{x^2}$



### Solution

考慮$f'(x) = 6x + \dfrac{-4}{x^3}$，$f''(x) = 6 + \dfrac{12}{x^4} = \dfrac{6x^4+12}{x^4}$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \varnothing$

考慮$f''(x) = D.N.E.$，則$x \in \{0\}$

因此臨界數$CriticalPoint \in \{0\}$

上凹下凹區間通常由臨界數所分割，故考慮區間$(-\infty, 0), (0, \infty)$

考慮區間$(-\infty, 0)$，以$-1$考慮$f''(-1)$，則$f''(-1) > 0$，故區間$(-\infty, 0)$上凹。

考慮區間$(0, \infty)$，以$1$考慮$f''(1)$，則$f''(1) > 0$，故區間$(0, \infty)$上凹。

考慮$x = 0$，左右區間上凹下凹相同，故反曲點並沒有發生在$x = 0$上。



### Answer

上凹區間：$(-\infty, 0)$，$(0, \infty)$。

下凹區間：不存在。

反曲點：不存在。



## Exercise 5

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = \dfrac{1}{6}x^3-\dfrac{9}{40}x^\frac{8}{3} + \dfrac{7}{120}$



### Solution

考慮$f'(x) = \dfrac{1}{2}x^2 - \dfrac{3}{5} x^\frac{5}{3}$，$f''(x) = x - x^\frac{2}{3}$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \{0, 1\}$

考慮$f''(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$Critical Point \in \{0, 1\}$

上凹下凹區間通常由臨界數所分割，故考慮$(-\infty, 0), (0, 1), (1, \infty)$

考慮區間$(-\infty, 0)$，以$-1$考慮$f''(-1)$，則$f''(-1) < 0$，故區間$(-\infty, 0)$下凹。

考慮區間$(0, 1)$，以$\dfrac{1}{2}$考慮$f''(\dfrac{1}{2})$，則$f''(\dfrac{1}{2}) < 0$，故區間$(0, 1)$下凹。

考慮區間$(1, \infty)$，以$8$考慮$f''(8)$，則$f''(8)  > 0$，故區間$(1, \infty)$上凹。

考慮$x = 0$，左右上凹下凹相同，因此反曲點沒有發生在$x = 0$上。

考慮$x = 1$，左右上凹下凹不同，因此反曲點發生在$x = 1$上，也就是點$(1, 0)$。

也因為$x = 0$不是反曲點，下凹區間$(-\infty, 0)$與$(0, 1)$合併成$(-\infty, 1)$。



### Answer

上凹區間：$(1, \infty)$。

下凹區間：$(0, 1), (-\infty, 0)$。

反曲點：$(1, 0)$。



## Exercise 6

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = 3x^4-4x^3+1$



### Solution

$f'(x) = 12x^3 - 12x^2$，$f''(x) = 36x^2 - 24x = 12x(3x-2)$

考慮反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \{0, \dfrac{2}{3}\}$

考慮$f''(x) = D.N.E.$，則$x \in \varnothing$

因此臨界數$CriticalPoint \in \{0, \dfrac{2}{3}\}$

上凹下凹區間通常被臨界數所分割，因此考慮區間$(-\infty, 0), (0, \dfrac{2}{3}), (\dfrac{2}{3}, \infty)$

考慮$(-\infty, 0)$，則以$-1$考慮$f''(-1)$，得到$f''(-1) > 0$，故$(-\infty, 0)$上凹。

考慮$(0, \dfrac{2}{3})$，則以$\dfrac{1}{3}$考慮$f''(\dfrac{1}{3})$，得到$f''(\dfrac{1}{3}) < 0$，故$(0, \dfrac{2}{3})$下凹。

考慮$(\dfrac{2}{3}, \infty)$，則以$1$考慮$f''(1)$，得到$f''(1) > 0$，故$(\dfrac{2}{3}, \infty)$上凹。

考慮$x = 0$，左右兩邊上凹下凹不同，故反曲點發生在$x = 0$，也就是$(0, 1)$

考慮$x = \dfrac{2}{3}$，左右兩邊上凹下凹不同，故反曲點發生在$x = \dfrac{2}{3}$，也就是$(\dfrac{2}{3}, \dfrac{11}{27})$



### Answer

上凹區間：$(-\infty, 0),(\dfrac{2}{3}, \infty)$

下凹區間：$(0, \dfrac{2}{3})$

反曲點：$(0, 1),(\dfrac{2}{3}, \dfrac{11}{27})$



## Exercise 7

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = 2x - \sqrt[3]{x}$



### Solution

$f(x) = 2x - x^\frac{1}{3}$，$f'(x) = 2 - \dfrac{1}{3} x^\frac{-2}{3}$，$f''(x) = \dfrac{2}{9}x^\frac{-5}{3}$

考慮反曲點通常發生在臨界數

考慮$f''(x) = 0$，則$x \in \varnothing$

考慮$f''(x) = D.N.E.$，則$x \in \{0\}$

故臨界數$CriticalPoint \in \{0\}$

考慮臨界數會把區間分割成上凹與下凹，故考慮區間$(-\infty, 0), (0, \infty)$。

考慮$(-\infty, 0)$，以$-1$考慮$f''(-1)$，則$f''(-1) < 0$，故區間$(-\infty, 0)$下凹。

考慮$(0, \infty)$，以$1$考慮$f''(1)$，則$f''(1) > 0$，故區間$(0, \infty)$上凹。

考慮$x = 0$，左右兩邊上凹下凹不同，故反曲點會發生在$x = 0$，也就是$(0, 0)$



### Answer

上凹區間：$(0, \infty)$

下凹區間：$(-\infty, 0)$

反曲點：$(0, 0)$



## Exercise 8

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = x - \sqrt{1-x^2}$



### Solution

考慮函數的定義域，得$x \in [-1, 1]$時有定義。

$f'(x) = 1 + \dfrac{x}{\sqrt{1-x^2}}$，$f''(x) = \dfrac{1}{\sqrt{1-x^2}(1-x^2)}$

考慮反曲點通常都發生在臨界數

考慮$f''(x) = 0$，則$x \in \varnothing$

考慮$f''(x) = D.N.E.$，則$x \in \{1\}$

因此臨界數$Critical Point \in \{1\}$

通常臨界數會將區間分割成上凹與下凹，因此考慮$(-1, 1)$

區間只有一個，故沒有反曲點。

考慮$(-1, 1)$，以$0$考慮$f''(0)$，則$f''(0) > 0$，故$(-1, 1)$上凹。



### Answer

上凹區間：$(-1, 1)$

下凹區間：不存在

反曲點：不存在



## Exercise 9

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = \dfrac{x}{x+1}$



### Solution

考慮定義域，$x \neq -1$時均有定義。

考慮$f'(x) = \dfrac{1}{(x+1)^2}$，$f''(x) = \dfrac{-2}{(x+1)^3}$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \varnothing$

考慮$f''(x) = D.N.E.$，則$x \in -1$

因此臨界數$CriticalPoint \in \{-1\}$

臨界數通常將區間分割成上凹與下凹，因此考慮區間$(-\infty, -1), (-1, \infty)$

考慮$(-\infty, -1)$，以$-2$考慮$f''(-2)$，得$f''(-2) > 0$，故$(-\infty, -1)$上凹。

考慮$(-1, \infty)$，以$2$考慮$f''(2)$，得$f''(2) < 0$，故$(-1, \infty)$下凹。

考慮$x = -1$，左右兩邊上凹下凹不同，故反曲點發生在$x = -1$，但是點不存在因此這個反曲點不存在。



### Answer

上凹區間：$(-\infty, -1)$

下凹區間：$(-1, \infty)$

反曲點：不存在。



## Exercise 10

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = \dfrac{x^2-9}{1-x^2}$



### Solution

考慮$f(x)$的定義域，當$x \neq \{-1, 1\}$時函數有定義。

考慮$f'(x) = \dfrac{-16x}{(1-x^2)^2}$，$f''(x) = \dfrac{-16-48x^2}{(1-x^2)^3}$

反曲點可能發生在臨界數

考慮$f''(x) = 0$，則$x \in \varnothing$

考慮$f''(x) = D.N.E.$，則$x \in \{-1, 1\}$

則臨界數$CriticalPoint \in \{-1, 1\}$

區間通常被臨界數分割成上凹與下凹，所以考慮區間$(-\infty, -1), (-1, 1), (1, \infty)$

考慮$(-\infty, -1)$，以$-2$考慮$f''(-2)$，則$f''(-2) > 0$，因此$(-\infty, -1)$上凹。

考慮$(-1, 1)$，以$0$考慮$f''(0)$，則$f''(0) < 0$，因此$(-1, 1)$下凹。

考慮$(1, \infty)$，以$2$考慮$f''(2)$，則$f''(2) > 0$，因此$(1, \infty)$上凹。

考慮$x = -1$，左右兩邊上凹下凹不同，故反曲點發生在$x = -1$，但是點不存在所以反曲點不存在。

考慮$x = 1$，左右兩邊上凹下凹不同，故反曲點發生在$x = 1$，但是點不存在所以反曲點不存在。



### Answer

上凹區間：$(-\infty, -1), (1, \infty)$

下凹區間：$(-1, 1)$

反曲點：不存在



## Exercise 11

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = x - \sin x,\quad 0 \le x \le 4\pi$



### Solution

考慮$f'(x) = 1 - \cos(x)$，且$f''(x) = \sin x$

考慮反曲點通常發生在臨界數上

故我們考慮$f''(x) = 0,\quad 0\le x \le 4\pi$，則$x \in \{0, \pi, 2\pi, 3\pi, 4\pi\}$

考慮$f''(x) = D.N.E.,\quad 0 \le x \le 4$，則$x \in \varnothing$

故臨界數$CriticalNumber \in \{0, \pi, 2\pi, 3\pi, 4\pi\}$



考慮上凹下凹區間通常由臨界數所分割，故考慮$(0, \pi), (\pi, 2\pi), (2\pi, 3\pi), (3\pi, 4\pi)$

考慮$(0, \pi)$，以$\dfrac{\pi}{2}$來考慮$f''(\dfrac{\pi}{2})$，則$f''(\dfrac{\pi}{2}) > 0$，故區間$(0, \pi)$上凹。

考慮$(\pi, 2\pi)$，以$\dfrac{3\pi}{2}$來考慮$f''(\dfrac{3\pi}{2})$，則$f''(\dfrac{3\pi}{2}) < 0$，故區間$(\pi, 2\pi)$下凹。

考慮$(2\pi, 3\pi)$，以$\dfrac{5\pi}{2}$來考慮$f''(\dfrac{5\pi}{2})$，則$f''(\dfrac{5\pi}{2}) > 0$，故區間$(2\pi, 3\pi)$上凹。

考慮$(3\pi, 4\pi)$，以$\dfrac{7\pi}{2}$來考慮$f''(\dfrac{7\pi}{2})$，則$f''(\dfrac{7\pi}{2}) < 0$，故區間$(3\pi, 4\pi)$下凹。

考慮$x = \pi$，則左右上凹下凹區間不同，故反曲點發生在$x = \pi$上，也就是$(\pi, \pi)$。

考慮$x = 2\pi$，則左右上凹下凹區間不同，故反曲點發生在$x = 2\pi$上，也就是$(2\pi, 2\pi)$。

考慮$x = 3\pi$，則左右上凹下凹區間不同，故反曲點發生在$x = 3\pi$上，也就是$(3\pi, 3\pi)$。



### Answer

上凹區間：$(0, \pi), (2\pi, 3\pi)$

下凹區間：$(\pi, 2\pi), (3\pi, 4\pi)$

反曲點：$(\pi, \pi), (2\pi, 2\pi), (3\pi, 3\pi)$



## Exercise 12

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = \dfrac{1}{6}x^3+x-x\ln x+\dfrac{5}{6}$





### Solution

考慮函數的定義域為$(0, \infty)$，則我們只考慮區間$(0, \infty)$。

考慮$f'(x) = \dfrac{1}{2}x^2-\ln(x)$，$f''(x) = \dfrac{x^2-x}{x}$

考慮反曲點通常發生在臨界數上

故考慮$f''(x) = 0, x\in (0, \infty)$，則$x \in \{1\}$

考慮$f''(x) = D.N.E., x\in (0, \infty)$，則$x \in \varnothing$

故臨界數$CriticalNumber \in \{1\}$

考慮上凹下凹區間通常由臨界數所分割，故我們考慮$(0, 1), (1, \infty)$。

考慮$(0, 1)$，則以$x = 0.5$考慮$f''(0.5)$，得到$f''(0.5) < 0$，故$(0, 1)$區間下凹。

考慮$(1, \infty)$，則以$x = 2$考慮$f''(2)$，得到$f''(2) > 0$，故$(1, \infty)$區間上凹。

考慮$x = 1$，左右區間上凹下凹不同，故反曲點發生在$x = 1$，也就是$(1, 2)$



### Answer

上凹區間：$(1, \infty)$

下凹區間：$(0, 1)$

反曲點：$(1, 2)$



## Exercise 13

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = \dfrac{\sin x}{1 + \cos x}, -\pi < x < \pi$



### Solution

考慮$f'(x) = \dfrac{\sec(\dfrac{x}{2})^2}{2}$，$f''(x) = \dfrac{\sin(\dfrac{x}{2})}{2\cos (\dfrac{x}{2})^3}$

考慮反曲點通常發生在臨界數上

故考慮$f''(x) = 0, -\pi < x < \pi$，則$x \in \{0\}$

考慮$f''(x) = D.N.E., -\pi < x < \pi$，則$x \in \varnothing$

因此$CriticalNumber \in \{0\}$

考慮上凹下凹區間通常發生在臨界數上，故考慮區間$(-\pi, 0), (0, \pi)$

考慮$(-\pi, 0)$，以$\dfrac{-\pi}{2}$考慮$f''(-\dfrac{\pi}{2})$，則$f''(-\dfrac{\pi}{2}) < 0$，故區間$(-\pi, 0)$區間下凹。

考慮$(0, \pi)$，以$\dfrac{\pi}{2}$考慮$f''(\dfrac{\pi}{2})$，則$f''(\dfrac{\pi}{2}) > 0$，故區間$(0, \pi)$區間上凹。

考慮$x = 0$，左右兩邊上凹下凹不同，故反曲點發生在$x = 0$上，也就是$(0, 0)$。



### Answer

上凹區間：$(0, \pi)$

下凹區間：$(-\pi, 0)$

反曲點：$(0, 0)$



## Exercise 14

### Statement

求函數圖形上凹、下凹的區間及反曲點。

$f(x) = x - \dfrac{1}{6}x^2 - \dfrac{1}{3}\ln x + \dfrac{1}{6}$



### Solution

考慮定義域為$(0, \infty)$，故區間只考慮$(0, \infty)$。

考慮$f'(x) = 1 - \dfrac{1}{3}x - \dfrac{1}{3x}$，$f''(x) = -\dfrac{1}{3} + \dfrac{1}{3x^2}$

考慮臨界數通常發生在反曲點上

故考慮$f''(x) = 0, 0<x<\infty$，則$x \in \{1\}$

考慮$f''(x) = D.N.E., 0 < x < \infty$，則$x \in \{0\}$

因此臨界數$CriticalNumber \in \{1\}$

上凹下凹區間通常由臨界數所分割，故考慮$(0, 1), (1, \infty)$

考慮$(0, 1)$，以$0.5$考慮$f''(0.5)$，則$f''(0.5) > 0$，因此$(0, 1)$區間上凹。

考慮$(1, \infty)$，以$2$考慮$f''(2)$，則$f''(2) < 0$，因此$(1, \infty)$區間下凹。

考慮$x = 1$，左右兩邊區間上凹下凹不同，故反曲點發生在$x = 1$，也就是$(1, 1)$



### Answer

上凹區間：$(0, 1)$

下凹區間：$(1, \infty)$

反曲點：$(1, 1)$



## Exercise 15

### Statement

試畫出下列函數圖形：

$f(x) = \dfrac{1}{x+2}$



### Solution

考慮$f(x)$的定義域為$x \neq -2$，因此我們考慮區間$(-\infty, -2), (-2, \infty)$

考慮$f'(x) = -\dfrac{1}{(x+2)^2}$，$f''(x) = \dfrac{2}{(x+2)^3}$

考慮反曲點通常可能發生在臨界數上

故考慮$f''(x) = 0, x < -2\  \cup -2 < x$，$x\in \varnothing$

考慮$f''(x) = D.N.E.,  x < -2\  \cup -2 < x$，$x \in \varnothing $

故沒有臨界數，也就沒有反曲點。

考慮兩個區間$(-\infty, -2), (-2, \infty)$

考慮$(-\infty. -2)$，以$-3$考慮$f''(-3)$，則$f''(-3) < 0$，則$(-\infty, -2)$區間下凹

考慮$(-2, \infty)$，以$0$考慮$f''(0)$，則$f''(x) > 0$，則$(-2, \infty)$區間上凹

考慮函數的垂直漸進線。

$\displaystyle \lim_{x\rightarrow -2^-} f(x) = \lim_{x\rightarrow -2^-} \dfrac{1}{x+2} = -\infty$

$\displaystyle \lim_{x\rightarrow -2^+} f(x) = \lim_{x\rightarrow -2^+} \dfrac{1}{x+2} = \infty$

考慮函數的水平漸進線。

$\displaystyle \lim_{x\rightarrow -\infty} f(x) = \lim_{x\rightarrow -\infty} \dfrac{1}{x+2} = 0$

$\displaystyle \lim_{x\rightarrow \infty} f(x) = \lim_{x\rightarrow \infty} \dfrac{1}{x+2} = 0$

因此我們可以畫一條下凹的線，從$(-\infty, 0)$到$(-2, -\infty)$，再畫一條上凹的線，從$(-2, \infty)$到$(\infty, 0)$。

<img src="C:\Users\Xuan\AppData\Roaming\Typora\typora-user-images\image-20201207174157669.png" alt="image-20201207174157669" style="zoom:67%;" />



### Answer

See solution.



## Exercise 16

### Statement

試畫出下列函數圖形：

$f(x) = \dfrac{x-1}{x+1}$



### Solution

考慮函數的定義域$x \neq -1$，因此考慮兩個區間$(-\infty, -1), (-1, \infty)$。

考慮$f'(x) = \dfrac{2}{(x+1)^2}$，$f''(x) = \dfrac{-4}{(x+1)^3}$

考慮反曲點通常可能發生在臨界數上

故考慮$f''(x) = 0, x \in (-\infty, -1) \cup (-1, \infty)$，則$x \in \varnothing$

考慮$f''(x) = D.N.E., x \in (-\infty, -1) \cup (-1, \infty)$，則$x \in \varnothing$

故沒有反曲點發生

考慮兩個區間的上凹下凹情況

考慮$(-\infty, -1)$，以$-2$考慮$f''(-2)$，則$f''(-2) > 0$，故$(-\infty, -1)$區間上凹。

考慮$(-1, \infty)$，以$0$考慮$f''(0)$，則$f''(0) < 0$，故$(-1, \infty)$區間下凹。

考慮垂直漸進線。

$\displaystyle \lim_{x\rightarrow -1^-} f(x) = \lim_{x\rightarrow -1^-} \dfrac{x-1}{x+1} = \infty$ 

$\displaystyle \lim_{x\rightarrow -1^+} f(x) = \lim_{x\rightarrow -1^+} \dfrac{x-1}{x+1} = -\infty$

因此$x = -1$為函數的垂直漸進線。

考慮水平漸進線。

$\displaystyle \lim_{x\rightarrow \infty} f(x) = \lim_{x\rightarrow \infty} \dfrac{x-1}{x+1} = 1$

$\displaystyle \lim_{x\rightarrow -\infty} f(x) = \lim_{x\rightarrow -\infty} \dfrac{x-1}{x+1} = 1$

描圖，得到

<img src="C:\Users\Xuan\AppData\Roaming\Typora\typora-user-images\image-20201207180340974.png" alt="image-20201207180340974" style="zoom:67%;" />

### Answer

See solution.



## Exercise 23

### Statement

試畫出函數圖形。

$f(x) = xe^{-\frac{3}{2}x^2}$



### Solution

$f'(x) = e^{-\frac{3}{2}x^2} + x \cdot (-3x) \cdot e^{-\frac{3}{2}x^2} = (1-3x^2)e^{-\frac{3}{2}x^2}$

$f''(x) = (-6x)e^{-\frac{3}{2}x^2} + (1-3x^2) \cdot(-3x) \cdot e^{-\frac{3}{2}x^2} = (9x^3-9x)e^{-\frac{3}{2}x^2}$

考慮$f''(x)$的$CriticalNumber$

考慮$f''(x) = 0$，則$x \in \{-1, 0, 1\}$

考慮$f''(x) = D.N.E.$，則$x \in \varnothing$

因此$CriticalNumber \in \{-1, 0, 1\}$

考慮上凹下凹區間會由$CriticalNumber$所分割，因此我們考慮$(-\infty, -1),(-1, 0),(0, 1),(1, \infty)$

考慮$(-\infty, -1)$，以$-2$考慮$f''(-2)$，則$f''(-2) < 0$，故$(-\infty, -1)$區間下凹。

考慮$(-1, 0)$，以$\dfrac{-1}{2}$考慮$f''(\dfrac{-1}{2})$，則$f''(\dfrac{-1}{2}) > 0$，故$(-1, 0)$區間上凹。

考慮$(0, 1)$，以$\dfrac{1}{2}$考慮$f''(\dfrac{1}{2}$)，則$f''(\dfrac{1}{2}) < 0$，故$(0, 1)$區間下凹。

考慮$(1, \infty)$，以$2$考慮$f''(2)$，則$f''(2) > 0$，故$(1, \infty)$區間上凹。

考慮$\displaystyle \lim_{x\rightarrow \infty} f(x) = \lim_{x\rightarrow \infty} xe^{-\frac{3}{2}x^2} = \lim_{x\rightarrow \infty} \dfrac{x}{e^{\frac{3}{2}x^2}} = \dfrac{\infty}{\infty}$

故我們使用羅畢達，$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x}{e^{\frac{3}{2}x^2}} = \lim_{x\rightarrow \infty} \dfrac{1}{3e^{\frac{3}{2}x^2}} = 0$

考慮$\displaystyle \lim_{x\rightarrow -\infty} f(x) = \lim_{x\rightarrow -\infty} xe^{-\frac{3}{2}x^2} = \lim_{x\rightarrow \infty} \dfrac{x}{e^{\frac{3}{2}x^2}} = \dfrac{-\infty}{-\infty}$

故我們使用羅畢達，$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x}{e^{\frac{3}{2}x^2}} = \lim_{x\rightarrow \infty} \dfrac{1}{3e^{\frac{3}{2}x^2}} = 0$

故畫出圖形

<img src="https://i.imgur.com/EfRDprn.png" alt="image-20201214180019081" style="zoom:67%;" />