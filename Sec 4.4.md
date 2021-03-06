# 洪揮霖微積分Practice Ch4.4

###### tags: `微積分題目紀錄`



## Exercise 16

### Statement

全班共有60人，欲舉辦班遊，若30人參加，則每人繳500元，每增加一人，每人可少繳10元。

試問多少人參加班遊可收到最多的費用。



### Solution

列出方程式。

$f(x) = (30+x)(500-10x) = -10x^2+200x+15000$

利用一階導數求函數極值。

$f'(x) = -20x + 200$

考慮極值通常發生在臨界點上，因此

考慮$f'(x) = 0$，則$x = 10$

考慮$f'(x) = D.N.E.$，則$x \in \varnothing$

上凹下凹區間通常由臨界點分割，因此考慮$(-\infty, 10), (10, \infty)$

考慮$(-\infty, 10)$，以$x=9$考慮$f'(9)$，則$f'(9) > 0$，故區間遞增

考慮$(10, \infty)$，以$x = 11$考慮$f'(11)$，則$f'(11) < 0$，故區間遞減

考慮$x = 10$，左邊區間與右邊區間遞增遞減不同，故極值發生在$x = 10$

因此$f(10) = 16000$，故能收到的最大費用為$40$人參加。



### Answer

$40$人參加時可收到最多的費用。



## Exercise 17

### Statement

假設球體的半徑為6公分，求內接於球體的圓柱體之最大體積為多少？



### Solution

設圓柱半徑為$R$，圓柱高度為$H$，球體半徑為$r$

則我們可以根據畢氏定理，求出$(\dfrac{H}{2})^2 + R^2 = 36$，得到$R^2 = 36 - (\dfrac{H}{2})^2$。

已知圓柱體積為$V = R^2H\pi$

因此我們可以套入圓柱體積為$f(H) = (36 - \dfrac{H^2}{4})H\pi = \pi(36H - \dfrac{H^3}{4})$，$0 < H < 12$

則$f'(H) = \pi(36 - \dfrac{3}{4}H^2)$

考慮$f'(H) = 0$，則$H \in \{4\sqrt{3}\}$

考慮$f'(H) = D.N.E.$，則$H \in \{\varnothing\}$

故考慮區間$(0, 4\sqrt{3}), (4\sqrt{3}, 12)$

考慮區間$(0, 4\sqrt{3})$，以$4$考慮$f'(4)$，則$f'(4) > 0$

考慮區間$(4\sqrt{3}, 12)$，以$5$考慮$f'(10)$，則$f'(10) < 0$

考慮$H = 4\sqrt{3}$，左右兩邊遞增遞減區間不同，故極值發生在$H = 4\sqrt{3}$

$f(H) = 96\sqrt{3}\pi$，因此最大體積為$96\sqrt{3}\pi$



### Answer

$96\sqrt{3}\pi$



## Exercise 18

### Statement

求一直線方程式，使得該直線通過點$P(1, 2)$且在第一象限與$x$軸、$y$軸形成的三角形面積最小。



### Solution

造出直線，$y - 2 = m(x-1)$，則$y = mx - m + 2$，$x = \dfrac{y+m-2}{m}$

考慮$y$的截距，則令$x = 0$，因此$y_截 = -m+2$

考慮$x$的截距，則令$y = 0$，因此$x_截 = \dfrac{m-2}{m}$

因此可以造出方程式，$f(m) = \dfrac{1}{2}(-m+2) \dfrac{m-2}{m} = -\dfrac{m^2-4m+4}{2m}$，$m < 0$

利用一階導數求極值，$f'(m) = \dfrac{-1}{2} + \dfrac{2}{m^2}$

考慮極值可能發生在臨界點上，故考慮

$f'(m) = 0$，則$m = \{-2\}$

$f'(m) = D.N.E.$，則$m \in \varnothing$

遞增遞減區間通常由臨界點分割，因此考慮$(-\infty, -2),(-2, 0)$

考慮$(-\infty, -2)$，以$-4$考慮$f'(-4)$，則$f'(-4) < 0$

考慮$(-2, 0)$，以$-1$考慮$f'(-1)$，則$f'(-1) > 0$

考慮$m = -2$，左右區間遞增遞減不同， 故極值發生在$m= -2$上

因此在$m = -2$有最小面積三角形

故直線方程式為$2x+y-4=0$



### Answer

$2x+y-4=0$

