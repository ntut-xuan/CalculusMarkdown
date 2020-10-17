# 微積分Practice Ch3

###### tags: `微積分題目紀錄`

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

$= x \dfrac{x}{dx} \sin^{-1}(\dfrac{x}{4}) + \dfrac{x}{dx}x \cdot \sin^{-1}(\dfrac{x}{4}) + \dfrac{1}{2\sqrt{16-x^2}} \cdot (16-x^2)\dfrac{d}{dx}$

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



