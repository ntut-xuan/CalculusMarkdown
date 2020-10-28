# 洪揮霖微積分Practice Ch2.3

###### tags: `微積分題目紀錄`

## Sec 2.3

### Exercise 1

#### Statement

利用連鎖法則求函數的導函數。

$y = (2x-1)^5$



#### Solution

令$u = (2x-1)$，則$y = u^5$

$\dfrac{d}{dx} y = \dfrac{d}{dx} u^5$

$= \dfrac{d}{du} u^5 \dfrac{du}{dx}$

$= 5u^4 \dfrac{du}{dx}$

還原$u$得到$\dfrac{dy}{dx} = 5(2x-1)^4 \dfrac{d}{dx}(2x-1)$

$= 5(2x-1)^4\times (2) = 10(2x-1)^4$



因此$\dfrac{dy}{dx} = 10(2x-1)^4$



#### Answer

$\dfrac{dy}{dx} = y' = 10(2x-1)^4$



### Exercise 2

#### Statement

利用連鎖法則求函數的導函數。

$y = \sqrt{x^2-3}$



#### Solution

令$u = x^2-3$，則$y = \sqrt{u} = u^\frac{1}{2}$

$\dfrac{d}{dx} y = \dfrac{d}{dx} u^\frac{1}{2}$

$= \dfrac{d}{du} u^\frac{1}{2} \dfrac{du}{dx}$

$= \dfrac{1}{2}u^\frac{-1}{2} \dfrac{d}{dx} u = \dfrac{1}{2\sqrt{u}} \dfrac{d}{dx} u$

還原$u$

$\dfrac{dy}{dx} = \dfrac{1}{2\sqrt{x^2-3}} \dfrac{d}{dx}(x^2-3)$

$= \dfrac{1}{2\sqrt{x^2-3}} \cdot 2x$

$= \dfrac{2x}{2\sqrt{x^2-3}}$

$= \dfrac{x}{\sqrt{x^2-3}}$



因此$\dfrac{dy}{dx} = \dfrac{x}{\sqrt{x^2-3}}$。



#### Answer

$\dfrac{dy}{dx} = y' = \dfrac{x}{\sqrt{x^2-3}}$



### Exercise 3

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = (x^2+3)^6$



#### Solution

令$u = x^2+3$，則$f(x) = u^6$

所以$f'(x) = \dfrac{d}{dx} u^6 = \dfrac{d}{du} u^6 \dfrac{du}{dx}$

$= 6u^5 \dfrac{d}{dx} u$

還原$u$得到$f'(x) = 6(x^2+3)^5 \dfrac{d}{dx}(x^2+3) = 6(x^2+5)^5\times 2x = 12x(x^2+5)^5$



#### Answer

$f'(x) =12x(x^2+5)^5$



### Exercise 4

#### Statement

利用連鎖法則求函數的導函數。

$y = \sin 2x$



#### Solution

令$u = 2x$，則$\dfrac{d}{dx} y = \dfrac{d}{dx} \sin u$

$= \dfrac{d}{du} \sin u \dfrac{du}{dx} = \cos u \dfrac{d}{dx} u$

還原$u$得到$\dfrac{d}{dx}y = \cos2x \dfrac{d}{dx}(2x) = 2\cos 2x$



因此$\dfrac{dy}{dx} = y' = 2\cos 2x$



#### Answer

$\dfrac{dy}{dx} = y' = 2\cos 2x$



### Exercise 5

#### Statement

利用連鎖法則求函數的導函數。

$y = \sqrt{3x-2\cos x}$



#### Solution

令$u = 3x-2\cos x$，則$y = \sqrt{u}$

$\dfrac{d}{dx} y = \dfrac{d}{dx} \sqrt{u}$

$= \dfrac{d}{du} \sqrt{u} \dfrac{du}{dx}$

$= \dfrac{1}{2\sqrt{u}} \dfrac{d}{dx} u$

還原$u$，得到$\dfrac{dy}{dx} = \dfrac{1}{2\sqrt{3x-2\cos x}} \dfrac{d}{dx} (3x-2\cos x)$

$= \dfrac{1}{2\sqrt{3x-2\cos x}} (3+2\sin x)$

$= \dfrac{3+2\sin x}{2\sqrt{3x-2\cos x}} $



因此$\dfrac{dy}{dx} = y' = \dfrac{3+2\sin x}{2\sqrt{3x-2\cos x}} $



#### Answer

$\dfrac{dy}{dx} = y' = \dfrac{3+2\sin x}{2\sqrt{3x-2\cos x}} $



### Exercise 6

#### Statement

利用連鎖法則求函數的導函數。

$y = \tan \sqrt{x}$



#### Solution

令$u = \sqrt{x}$，則$y = \tan u$

因此$\dfrac{d}{dx} y = \dfrac{d}{dx} \tan u$

$= \dfrac{d}{du} \tan u \dfrac{du}{dx}$

$= \sec^2 u \dfrac{d}{dx} u$

還原$u$，得到$\dfrac{dy}{dx} = \sec^2(\sqrt{x}) \dfrac{1}{2\sqrt{x}}$

$= \dfrac{\sec^2\sqrt{x}}{2\sqrt{x}}$



因此$\dfrac{dy}{dx} = y' = \dfrac{\sec^2\sqrt{x}}{2\sqrt{x}}$



#### Answer

$\dfrac{dy}{dx} = y' = \dfrac{\sec^2\sqrt{x}}{2\sqrt{x}}$



### Exercise 7

#### Statement

利用連鎖法則求函數的導函數。

$y = \dfrac{1}{\sqrt[3]{x^3-2}}$



#### Solution

$y = \dfrac{1}{\sqrt[3]{x^3-2}} = (x^3-2)^\frac{-1}{3}$

令$u = x^3-2$，則$y = u^\frac{-1}{3}$



$\dfrac{d}{dx} y = \dfrac{d}{dx} u^\frac{-1}{3}$

$= \dfrac{d}{du} u^\frac{-1}{3} \dfrac{du}{dx}$

$= \dfrac{-1}{3} u^\frac{-4}{3} \dfrac{d}{dx} u$

$= \dfrac{-1}{3\sqrt[3]{u^4}} \dfrac{d}{dx} u$

還原$u$，得到$\dfrac{dy}{dx} = \dfrac{-1}{3\sqrt[3]{(x^3-2)^4}} \dfrac{d}{dx}(x^3-2)$

$= \dfrac{-1}{3\sqrt[3]{(x^3-2)^4}} \cdot 3x^2$

$= \dfrac{-3x^2}{3\sqrt[3]{(x^3-2)^4}} = \dfrac{-x^2}{\sqrt[3]{(x^3-2)^4}}$



#### Answer

$\dfrac{dy}{dx} = y' = \dfrac{-x^2}{\sqrt[3]{(x^3-2)^4}}$



### Exercise 8

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \dfrac{1}{(x^3-3)^2}$



#### Solution

令$u = x^3-3$，則$f(x) = \dfrac{1}{u^2} = u^{-2}$

因此$f'(x) = \dfrac{d}{dx} u^{-2}$

$= \dfrac{d}{du} u^{-2} \dfrac{du}{dx}$

$= -2u^{-3} \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = -2(x^3-3)^{-3} \dfrac{d}{dx}(x^3-3)$

$= -6x^2(x^3-3)^{-3}  = \dfrac{-6x^2}{(x^3-3)^3}$



#### Answer

$f'(x) =  \dfrac{-6x^2}{(x^3-3)^3}$



### Exercise 9

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \dfrac{1}{1-3x}$



#### Solution

$f(x) = \dfrac{1}{1-3x} = (1-3x)^{-1}$

令$u = (1-3x)$，則$f(x) = u^{-1}$



$f'(x) = \dfrac{d}{dx} u^{-1} = \dfrac{d}{du} u^{-1} \dfrac{du}{dx}$

$= -u^{-2} \dfrac{d}{dx} u$

還原$u$得到$f'(x) = -(1-3x)^{-2}\dfrac{d}{dx}(1-3x)$

$= -(1-3x)^{-2} (-3) = 3(1-3x)^{-2} = \dfrac{3}{(1-3x)^2}$



#### Answer

$f'(x) = \dfrac{3}{(1-3x)^2}$



### Exercise 10

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \dfrac{3}{(2x-1)^3}$



#### Solution

$f(x) = \dfrac{3}{(2x-1)^3} = 3(2x-1)^{-3}$

令$u = 2x-1$，則$f(x) = 3u^{-3}$

因此$f'(x) = \dfrac{d}{dx} 3u^{-3} = \dfrac{d}{du} 3u^{-3} \dfrac{du}{dx}$

$= -9u^{-4} \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = -9(2x-1)^{-4} \dfrac{d}{dx}(2x-1)$

$= -18(2x-1)^{-4} = \dfrac{-18}{(2x-1)^4}$



因此$f'(x) = \dfrac{-18}{(2x-1)^4}$



#### Answer

$f'(x) = \dfrac{-18}{(2x-1)^4}$



### Exercise 11

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \sqrt{2x^3-4x}$



#### Solution

令$u = 2x^3-4x$，則$f(x) = \sqrt{u}$

因此$f'(x) = \dfrac{d}{dx} \sqrt{u}$

$= \dfrac{d}{du} \sqrt{u} \dfrac{du}{dx}$

$= \dfrac{1}{2\sqrt{u}} \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = \dfrac{1}{2\sqrt{2x^3-4x}} \dfrac{d}{dx}(2x^3-4x)$

$= \dfrac{1}{2\sqrt{2x^3-4x}} (6x^2-4)$

$= \dfrac{6x^2-4}{2\sqrt{2x^3-4x}}$

$= \dfrac{3x^2-2}{\sqrt{2x^3-4x}}$



#### Answer

$f'(x) = \dfrac{3x^2-2}{\sqrt{2x^3-4x}}$



### Exercise 12

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \dfrac{1}{(x^3-2x^2+1)^5}$



#### Solution

$f(x) = (x^3-2x^2+1)^{-5}$

令$u = x^3-2x^2+1$，則$f(x) = u^{-5}$

那麼$f'(x) = \dfrac{d}{dx} u^{-5}$

$= \dfrac{d}{du} u^{-5} \dfrac{du}{dx}$

$= -5u^{-6} \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = -5(x^3-2x^2+1)^{-6} \dfrac{d}{dx}(x^3-2x^2+1)$

$= -5(x^3-2x^2+1)^{-6}\times (3x^2-4x)$

$= \dfrac{-5(3x^2-4x)}{(x^3-2x^2+1)^6}$



#### Answer

$f'(x) = \dfrac{-5(3x^2-4x)}{(x^3-2x^2+1)^6}$



### Exercise 13

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = (x + \dfrac{1}{2x})^3$



#### Solution

令$u = x + \dfrac{1}{2x} = x + \dfrac{1}{2}x^{-1}$，則$f(x) = u^3$

因此$f'(x) = \dfrac{d}{dx} u^3$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx}$

$= 3u^2 \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = 3(x+\dfrac{1}{2}x^{-1})^2 \dfrac{d}{dx}(x+\dfrac{1}{2}x^{-1})$

$= 3(x+\dfrac{1}{2}x^{-1})^2(1-\dfrac{1}{2}x^{-2})$

$= 3(x+\dfrac{1}{2x})^2(1-\dfrac{1}{2x^2})$



#### Answer

$f'(x) = 3(x+\dfrac{1}{2x})^2(1-\dfrac{1}{2x^2})$



### Exercise 14

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = (\dfrac{x-1}{x+1})^3$



#### Solution

令$u = \dfrac{x-1}{x+1}$，則$f(x) = u^3$

因此$f'(x) = \dfrac{d}{dx} u^3$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx}$

$= 3u^2 \dfrac{d}{dx} u$

還原$u$，得到$f'(x)= 3(\dfrac{x-1}{x+1})^2 \dfrac{d}{dx} (\dfrac{x-1}{x+1})$

$= 3(\dfrac{x-1}{x+1})^2 \dfrac{(x+1)(x-1)' - (x-1)(x+1)'}{(x+1)^2}$

$= 3(\dfrac{x-1}{x+1})^2 \dfrac{(x+1) - (x-1)}{(x+1)^2}$

$= 3(\dfrac{x-1}{x+1})^2 \dfrac{2}{(x+1)^2}$

$= 3\dfrac{(x-1)^2}{(x+1)^2} \dfrac{2}{(x+1)^2}$

$= \dfrac{6(x-1)^2}{(x+1)^4}$

#### Answer

$f'(x) = \dfrac{6(x-1)^2}{(x+1)^4}$



### Exercise 15

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \cos(3x+1)$



#### Solution

令$u = 3x+1$，則$f(x) = \cos u$

因此$f'(x) = \dfrac{d}{dx} \cos u$

$= \dfrac{d}{du} \cos u \dfrac{du}{dx}$

$= -\sin u \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = -\sin(3x+1) \dfrac{d}{dx}(3x+1)$

$= -\sin(3x+1)\times 3$

$= -3\sin(3x+1)$



#### Answer

$f'(x) = -3\sin(3x+1)$



### Exercise 16

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = (\dfrac{2x^2-1}{3x+4})^3$



#### Solution

令$u = \dfrac{2x^2-1}{3x+4}$，則$f(x) = u^3$

因此$f'(x) = \dfrac{d}{dx} u^3$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx}$

$= 3u^2 \dfrac{d}{dx}u$

還原$u$，得到$f'(x) = 3(\dfrac{2x^2-1}{3x+4})^2\dfrac{d}{dx}\dfrac{2x^2-1}{3x+4}$

$= 3(\dfrac{2x^2-1}{3x+4})^2\dfrac{(3x+4)(2x^2-1)'-(2x^2-1)(3x+4)'}{(3x+4)^2}$

$= 3(\dfrac{2x^2-1}{3x+4})^2\dfrac{(3x+4)4x-(2x^2-1)3}{(3x+4)^2}$

$= 3(\dfrac{2x^2-1}{3x+4})^2\dfrac{12x^2+16x-(6x^2-3)}{(3x+4)^2}$

$= 3(\dfrac{2x^2-1}{3x+4})^2\dfrac{6x^2+16x-3}{(3x+4)^2}$

$= \dfrac{3(2x^2-1)^2}{(3x+4)^2}\dfrac{6x^2+16x-3}{(3x+4)^2}$

$= \dfrac{3(2x^2-1)^2(6x^2+16x-3)}{(3x+4)^4}$



#### Answer

$f'(x) = \dfrac{3(2x^2-1)^2(6x^2+16x-3)}{(3x+4)^4}$



### Exercise 17

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \cot(3x+2)$



#### Solution

令$u = 3x+2$，則$f(x) = \cot(u)$

因此$f'(x) = \dfrac{d}{dx} \cot u$

$= \dfrac{d}{du} \cot u \dfrac{du}{dx}$

$= -\csc^2 u \dfrac{d}{dx} u$

還原$u$，得到

$f'(x) = -\csc^2(3x+2) \dfrac{d}{dx}(3x+2)$

$= -\csc^2(3x+2) \times 3$

$= -3\csc^2(3x+2)$



#### Answer

$f'(x) = -3\csc^2(3x+2)$



### Exercise 18

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \sin^32x$



#### Answer

令$u = \sin2x$，則$f(x) = u^3$

因此$f'(x) = \dfrac{d}{dx} u^3$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx}$

$= 3u^2 \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = 3(\sin 2x)^2 \dfrac{d}{dx} \sin2x$

令$t = 2x$，則

$f'(x) = 3(\sin 2x)^2 \dfrac{d}{dx}\sin t$

$= 3(\sin 2x)^2 \dfrac{d}{dt} \sin t \dfrac{dt}{dx}$

$= 3(\sin 2x)^2 \cos t \dfrac{d}{dx} t$

還原$t$，得到$f'(x) = 3(\sin 2x)^2 \cos 2x \dfrac{d}{dx} 2x$

$= 3(\sin 2x)^2 \cos 2x\times 2$

$= 6(\sin 2x)^2\cos 2x$

$= 6\cos 2x(\sin 2x)^2$



#### Answer

$f'(x) = 6\cos 2x(\sin 2x)^2$



### Exercise 19

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \sin \dfrac{1}{x}$



#### Solution

令$u = \dfrac{1}{x}$，則$f(x) = \sin u$

因此$f'(x) = \dfrac{d}{dx} \sin u$

$= \dfrac{d}{du} \sin u \dfrac{du}{dx}$

$= \cos u \dfrac{d}{dx} u$

還原$u$，得到，$\cos \dfrac{1}{x} \dfrac{d}{dx} \dfrac{1}{x}$

$= \cos \dfrac{1}{x}\times  \dfrac{x(1)'-1(x)'}{x^2}$

$= \cos \dfrac{1}{x}\times \dfrac{-1}{x^2}$



#### Answer

$f'(x) = \cos \dfrac{1}{x}\times \dfrac{-1}{x^2}$



### Exercise 20

#### Statement

利用連鎖法則求函數的導函數。

$f(x) = \sin^3x+\cos 2x$



#### Solution

令$u = \sin x, t = 2x$

則$f(x) = u^3 + \cos t$



因此$f'(x) = \dfrac{d}{dx} u^3 + \dfrac{d}{dx} \cos t$

$= \dfrac{d}{du} u^3 \dfrac{du}{dx} + \dfrac{d}{dt} \cos t \dfrac{dt}{dx}$

$= 3u^2\dfrac{d}{dx} u + (-\sin t) \dfrac{d}{dx} t$

還原$u, t$，得到$f'(x) = 3(\sin x)^2 \dfrac{d}{dx} \sin x - \sin 2x \dfrac{d}{dx}2x$

$= 3(\sin x)^2(\cos x) - \sin 2x\times (2)$

$= 3(\sin x)^2(\cos x) -2\sin 2x$



#### Answer

$f'(x) = 3(\sin x)^2(\cos x) -2\sin 2x$



### Exercise 21

#### Statement

$f(x) = \sqrt{1-\cos 2x}$



#### Solution

令$u = 1-\cos 2x$，則$f(x) = \sqrt{u}$

因此$f'(x) = \dfrac{d}{dx} \sqrt{u}$

$= \dfrac{d}{du} \sqrt{u} \dfrac{du}{dx}$

$= \dfrac{1}{2\sqrt{u}} \dfrac{d}{dx} u$

還原$u$，得到$f'(x) = \dfrac{1}{2\sqrt{1-\cos 2x}} \dfrac{d}{dx}(1-\cos 2x)$

 $= \dfrac{1}{2\sqrt{1-\cos 2x}}(\dfrac{d}{dx}1 - \dfrac{d}{dx} \cos 2x)$

$= \dfrac{1}{2\sqrt{1-\cos 2x}}(- \dfrac{d}{dx} \cos 2x)$

令$t = 2x$，則$f'(x) = \dfrac{1}{2\sqrt{1-\cos 2x}}(- \dfrac{d}{dx} \cos t)$

$= \dfrac{1}{2\sqrt{1-\cos 2x}}(-\dfrac{d}{dt} \cos t \dfrac{dt}{dx})$

$= \dfrac{1}{2\sqrt{1-\cos 2x}}(\sin t \dfrac{d}{dx} t)$

還原$t$，得到$f'(x) = \dfrac{1}{2\sqrt{1-\cos 2x}}(\sin 2x \dfrac{d}{dx} 2x)$

$= \dfrac{1}{2\sqrt{1-\cos 2x}}(\sin 2x \times 2)$

$=\dfrac{2\sin 2x}{2\sqrt{1-\cos 2x}}$

$=\dfrac{\sin 2x}{\sqrt{1-\cos 2x}}$



#### Answer

$f'(x) =\dfrac{\sin 2x}{\sqrt{1-\cos 2x}}$



### Exercise 22

#### Statement

$f(x) = \dfrac{1+\cos 3x}{1-\cos 3x}$



#### Solution

令$u = 3x$，則$f(x) = \dfrac{1+\cos u}{1-\cos u}$

所以$f'(x) = \dfrac{d}{dx} \dfrac{1+\cos u}{1-\cos u}$

$= \dfrac{(1-\cos u)\dfrac{d}{dx}(1+\cos u) - (1+\cos u)\dfrac{d}{dx}(1-\cos u)}{(1-\cos u)^2}$

$= \dfrac{(1-\cos u)(\dfrac{d}{dx}1+\dfrac{d}{dx}\cos u) - (1+\cos u)(\dfrac{d}{dx}1-\dfrac{d}{dx}\cos u)}{(1-\cos u)^2}$

$= \dfrac{(1-\cos u)(\dfrac{d}{dx}\cos u) - (1+\cos u)(-\dfrac{d}{dx}\cos u)}{(1-\cos u)^2}$

$= \dfrac{(1-\cos u)(\dfrac{d}{du}\cos u \dfrac{du}{dx}) - (1+\cos u)(-\dfrac{d}{du}\cos u \dfrac{du}{dx})}{(1-\cos u)^2}$

$= \dfrac{(1-\cos u)(-\sin u \dfrac{d}{dx} u) - (1+\cos u)(\sin u \dfrac{d}{dx}u)}{(1-\cos u)^2}$

還原$u$，得到$f'(x) = \dfrac{(1-\cos 3x)(-\sin 3x \dfrac{d}{dx} 3x) - (1+\cos 3x)(\sin 3x \dfrac{d}{dx}3x)}{(1-\cos 3x)^2}$

$= \dfrac{(1-\cos 3x)(-3\sin 3x) - (1+\cos 3x)(3\sin 3x)}{(1-\cos 3x)^2}$

$= \dfrac{(1-\cos 3x)(-3\sin 3x) + (1+\cos 3x)(-3\sin 3x)}{(1-\cos 3x)^2}$

$= \dfrac{2(-3\sin 3x)}{(1-\cos 3x)^2}$

$= \dfrac{-6\sin 3x}{(1-\cos 3x)^2}$



#### Answer

$f(x) = \dfrac{-6\sin 3x}{(1-\cos 3x)^2}$



### Exercise 23

#### Statement

$f(x) = \sin 3x + \tan\sqrt{2x+1}$



#### Solution

令$u = 3x, t = \sqrt{2x+1}$

因此$f(x) = \sin u + \tan t$

所以$f'(x) = \dfrac{d}{dx} \sin u + \dfrac{d}{dx} \tan t $

$= \dfrac{d}{du} \sin u \dfrac{du}{dx} + \dfrac{d}{dt} \tan t \dfrac{dt}{dx}$

$= \cos u \dfrac{d}{dx} u + \sec^2t \dfrac{d}{dx} t$

還原$u, t$，得到$f'(x) = \cos(3x) \dfrac{d}{dx}(3x) + \sec^2(\sqrt{2x+1}) \dfrac{d}{dx} (\sqrt{2x+1})$

$= 3\cos(3x) + \sec^2(\sqrt{2x+1})\dfrac{d}{dx}(\sqrt{2x+1})$

令$v = 2x+1$，則$f'(x) = 3\cos(3x) + \sec^2(\sqrt{2x+1})\dfrac{d}{dx}(\sqrt{v})$

$= 3\cos(3x) + \sec^2(\sqrt{2x+1})(\dfrac{d}{dv}(\sqrt{v}) \dfrac{dv}{dx})$

$= 3\cos(3x) + \sec^2(\sqrt{2x+1})(\dfrac{1}{2\sqrt{v}} \dfrac{d}{dx}v)$

還原$v$，得到$f'(x) = 3\cos(3x) + \sec^2(\sqrt{2x+1})(\dfrac{1}{2\sqrt{2x+1}} \dfrac{d}{dx}(2x+1))$

$= 3\cos(3x) + \sec^2(\sqrt{2x+1})(\dfrac{2}{2\sqrt{2x+1}})$

$= 3\cos(3x) + \dfrac{2\sec^2(\sqrt{2x+1})}{2\sqrt{2x+1}}$

$= 3\cos(3x) + \dfrac{\sec^2(\sqrt{2x+1})}{\sqrt{2x+1}}$



#### Answer

$f'(x) = 3\cos(3x) + \dfrac{\sec^2(\sqrt{2x+1})}{\sqrt{2x+1}}$



### Exercise 24

#### Statement

$f(x) = \sec(x^2+1)$



### Exercise 25

#### Statement

$f(x) = (2x+1)^5 \tan 2x$



### Exercise 26

#### Statement

$f(x) = \csc(x^2)$



### Exercise 27

#### Statement

$f(x) = (2-\cos^3x)^4$



### Exercise 28

#### Statement

$f(x) = \tan^2(x^3+1)$



### Exercise 29

#### Statement

$f(x) = \sqrt{1+4\sin^3 2x}$



### Exercise 30

#### Statement

$f(x) = \dfrac{x+\sin 2x}{1+\cos 2x}$



### Exercise 31

#### Statement

$f(x) = x^3\cos 2x$



### Exercise 32

#### Statement

$y = \sec^3(2x)$



### Exercise 33

#### Statement

$f(t) = \sin(\cos t)$



### Exercise 34

#### Statement

$y = \sqrt{x+\sqrt{x}}$



### Exercise 35

#### Statement

$y = x\sqrt{x^2 +  3}$



### Exercise 36

#### Statement

$y = \sin^3(2x)\cos (2x)$



### Exercise 37

#### Statement

$y = \dfrac{1+\sin 2x}{1-\sin 2x}$



### Exercise 38

#### Statement

$y = \tan(\sin(2x+1)))$



### Exercise 39

#### Statement

$y = \tan^3(x^2)$



### Exercise 40

#### Statement

$y = (1+\sec^3(2x))^5$



