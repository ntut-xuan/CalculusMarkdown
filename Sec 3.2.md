# 洪輝霖微積分Practice Ch 3.2

###### tags: `微積分題目紀錄`



## Exercise 10

### Statement

求下列各函數的導函數。

$y = e^{2x+3}$



### Solution

利用代換，令$u = 2x + 3$

$\dfrac{dy}{dx} = \dfrac{d}{du} e^u \dfrac{du}{dx} = e^u \dfrac{d}{dx} u$

還原$u$得到$\dfrac{dy}{dx} = e^{2x+3} \dfrac{d}{dx} (2x+3) = 2e^{2x+3}$

故$\dfrac{dy}{dx} = 2e^{2x+3}$



### Answer

$\dfrac{dy}{dx} = 2e^{2x+3}$



## Exercise 11

### Statement

求下列各函數的導函數。

$y = e^{1-2x}$



### Solution

令$u = 1-2x$，則$y = e^u$

因此考慮$\dfrac{dy}{dx} = \dfrac{d}{dx} e^u = \dfrac{d}{du} e^u \dfrac{du}{dx} = e^u \dfrac{d}{dx} u$

還原$u$，得到$\dfrac{dy}{dx} = e^{1-2x} \dfrac{d}{dx}(1-2x) = -2e^{1-2x}$



### Answer

$\dfrac{dy}{dx} = -2e^{1-2x}$



## Exercise 12

### Statement

求下列各函數的導函數。

$y = \dfrac{2}{e^{3x}}$



### Solution

$y = 2e^{-3x}$

利用代換，令$u = -3x$，則

$\dfrac{dy}{dx} = 2e^u \dfrac{du}{dx} = -6e^{-3x}$

故$\dfrac{dy}{dx} = -6e^{-3x}$



### Answer

$\dfrac{dy}{dx} = -6e^{-3x}$



## Exercise 13

### Statement

求下列各函數的導函數。

$y = e^{\sin x}$



### Solution

利用代換，令$u = \sin x$，則

$\dfrac{dy}{dx} = e^u \dfrac{du}{dx} =  e^{\sin x}\cos x$

故$\dfrac{dy}{dx} = e^{\sin x} \cos x$



### Answer

$\dfrac{dy}{dx} = e^{\sin x} \cos x$



## Exercise 14

### Statement

求下列各函數的導函數。

$y = e^{\cos 2x}$



### Solution

利用代換，令$u = \cos 2x$，則

$\dfrac{dy}{dx} = \dfrac{d}{dx} e^{u} = \dfrac{d}{du} e^u \dfrac{du}{dx} = e^u \dfrac{d}{dx}u$

還原$u$，得到$\dfrac{dy}{dx} = e^{\cos 2x} \dfrac{d}{dx} \cos 2x$

令$t = 2x$，則$\dfrac{dy}{dx} = e^{\cos 2x} \dfrac{d}{dx} \cos t = e^{\cos 2x} \dfrac{d}{dt}\cos t \dfrac{dt}{dx} = -e^{\cos 2x} \sin t \dfrac{d}{dx}t$

還原$t$，得到$\dfrac{dy}{dx} = -e^{\cos 2x} \sin(2x) \dfrac{d}{dx}(2x) = -2e^{\cos 2x}\sin 2x$



### Answer

$\dfrac{dy}{dx} = -2e^{\cos 2x} \sin 2x$



## Exercise 15

### Statement

求下列各函數的導函數。

$f(t) = te^{-2t}$



### Solution

考慮$f'(t) = \dfrac{d}{dt}(te^{-2t}) = e^{-2t} + t\dfrac{d}{dt}e^{-2t}$

令$u = -2t$，則$f'(t) = e^{-2t} + t\dfrac{d}{dt}e^{u} = e^{-2t} + t\dfrac{d}{du}e^{u}\dfrac{du}{dt} = e^{-2t} + te^u \dfrac{d}{dt}u$

還原$u$，得到$f'(t) = e^{-2t} + te^{-2t} \dfrac{d}{dt}(-2t) = e^{-2t}-2te^{-2t} = (1-2t)e^{-2t}$



### Answer

$f'(t) = (1-2t)e^{-2t}$



## Exercise 16

### Statement

求下列各函數的導函數。

$f(x) = x^3 e^{2x-1}$



### Solution

考慮$f'(x) = 3x^2e^{2x-1} + x^3\dfrac{d}{dx}e^{2x-1}$

令$u = 2x-1$，則$f'(x) = 3x^2e^{2x-1} + x^3 \dfrac{d}{dx} e^u = 3x^2e^{2x-1} + x^3\dfrac{d}{du}e^u\dfrac{du}{dx} = 3x^2e^{2x-1}+x^3e^u\dfrac{d}{dx}u$

還原$u$，得到$f'(x) = 3x^2e^{2x-1} + x^3e^{2x-1} \dfrac{d}{dx} (2x-1) = 3x^2e^{2x-1} + 2x^3e^{2x-1} = (3x^2+2x^3)e^{2x-1}$



## Exercise 17

### Statement

求下列各函數的導函數。

$f(x) = \dfrac{1+e^{2x}}{1-e^{2x}}$



### Solution

$f'(x) = \dfrac{(1-e^{2x})\dfrac{d}{dx}(1+e^{2x}) - (1+e^{2x})\dfrac{d}{dx}(1-e^{2x})}{(1-e^{2x})^2} = \dfrac{(1-e^{2x})(2e^{2x})-(1+e^{2x})(-2e^{2x})}{(1-e^{2x})^2}$

$= \dfrac{4e^{2x}}{(1-e^{2x})^2}$



### Answer

$f'(x) = \dfrac{4e^{2x}}{(1-e^{2x})^2}$



## Exercise 18

### Statement

求下列各函數的導函數。

$f(x) = \dfrac{3+e^{2x}}{x}$



### Solution

$f'(x) = \dfrac{x\dfrac{d}{dx}(3+e^{2x}) - (3+e^{2x})\dfrac{d}{dx}(x)}{x^2} = \dfrac{2xe^{2x}-(3+e^{2x})}{x^2} = \dfrac{(2x-1)e^{2x}-3}{x^2}$



### Answer

$f'(x) =\dfrac{(2x-1)e^{2x}-3}{x^2}$



## Exercise 19

### Statement

求下列各函數的導函數。

$y = \dfrac{\sin 3x}{x-e^{2x}}$



### Solution

$y' = \dfrac{(x-e^{2x})(3\cos 3x)-(\sin 3x)(1-2e^{2x})}{(x-e^{2x})^2}$



### Answer

$y' = \dfrac{(x-e^{2x})(3\cos 3x)-(\sin 3x)(1-2e^{2x})}{(x-e^{2x})^2}$



## Exercise 20

### Statement

求下列各函數的導函數。

$y = e^{2x}\cos 3x$



### Solution

$y' = e^{2x} \dfrac{d}{dx}\cos 3x + \dfrac{d}{dx}e^{2x}\cdot \cos 3x = -3e^{2x}\sin 3x + 2e^{2x}\cos 3x$



### Answer

$y' = 2e^{2x}\cos 3x - 3e^{2x}\sin 3x$



## Exercise 21

### Statement

求下列各函數的導函數。

$y = \sqrt{e^{2x}+1}$



### Solution

$y' = \dfrac{1}{2\sqrt{e^{2x}+1}} \dfrac{d}{dx}(e^{2x}+1) = \dfrac{2e^{2x}}{2\sqrt{e^{2x}+1}} = \dfrac{e^{2x}}{\sqrt{e^{2x}+1}}$