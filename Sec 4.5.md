# 洪輝霖微積分Practice Ch 4.5

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

$\displaystyle \lim_{x\rightarrow 2} \dfrac{x^3-8}{x^2-x-2}$



### Solution

$\dfrac{x^3-8}{x^2-x-2}$，當$x \rightarrow 2$時，得$\dfrac{8-8}{4-2-2} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 2} \dfrac{x^3-8}{x^2-x-2} \stackrel{L.H.}= \lim_{x\rightarrow 2} \dfrac{3x^2}{2x-1} = \lim_{x\rightarrow 2} \dfrac{12}{3} = 4$



### Answer

$\displaystyle \lim_{x\rightarrow 2} \dfrac{x^3-8}{x^2-x-2} = 4$



## Exercise 2

### Statement

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-4}$



### Solution

$\dfrac{\ln(2x-3)}{x^2-4}$，當$x \rightarrow 2$時，得$\dfrac{\ln(4-3)}{4-4} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-4} \stackrel{L.H.}= \lim_{x\rightarrow 2} \dfrac{\dfrac{2}{2x-3}}{2x} = \dfrac{2}{4} = \dfrac{1}{2}$



### Answer

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-4} = \dfrac{1}{2}$



## Exercise 3

### Statement

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^3+1}{x^2+2x+3}$



### Solution

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^3+1}{x^2+2x+3} = \dfrac{\infty}{\infty}$

因此我們使用羅畢達

$ \displaystyle \lim_{x\rightarrow \infty} \dfrac{x^3+1}{x^2+2x+3} \stackrel{L.H.} =  \lim_{x\rightarrow \infty} \dfrac{3x^2}{2x+2} = \dfrac{\infty}{\infty}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{3x^2}{2x+2} \stackrel{L.H.} =  \lim_{x\rightarrow \infty} \dfrac{6x}{2} = \infty$



### Answer

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^3+1}{x^2+2x+3} = \infty$



## Exercise 4

### Statement

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin^{-1} x}{\tan^{-1} x}$



### Solution

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin^{-1} x}{\tan^{-1} x} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin^{-1} x}{\tan^{-1} x } \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{\dfrac{1}{\sqrt{1-x^2}}}{\dfrac{1}{1+x^2}} = 1$



### Answer

$\displaystyle \lim_{x\rightarrow 0} \dfrac{\sin^{-1} x}{\tan^{-1} x} = 1$



## Exercise 5

### Statement

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x+\cos x}{x-\sin x}$



### Solution

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x+\cos x}{x - \sin x} = \lim_{x\rightarrow \infty} \dfrac{1+\dfrac{\cos x}{x}}{1+\dfrac{\sin x}{x}} = \dfrac{\displaystyle \lim_{x\rightarrow \infty} 1 + \lim_{x\rightarrow \infty} \dfrac{\cos x}{x}}{\displaystyle \lim_{x\rightarrow \infty} 1 + \lim_{x\rightarrow \infty} \dfrac{\sin x}{x}} = \dfrac{1+0}{1+0} = 1$



### Answer

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x+\cos x}{x-\sin x} = 1$





## Exercise 6

### Statement

$\displaystyle \lim_{x\rightarrow 0} (\dfrac{1}{\ln(x+1)} - \dfrac{1}{x})$



### Solution

$\displaystyle \lim_{x\rightarrow 0}(\dfrac{1}{\ln(x+1)} - \dfrac{1}{x}) = \lim_{x\rightarrow 0} \dfrac{x-\ln(x+1)}{x\ln(x+1)} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x-\ln(x+1)}{x\ln(x+1)} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{1-\dfrac{1}{x+1}}{\ln(x+1)+\dfrac{x}{x+1}} = \lim_{x\rightarrow 0} \dfrac{x}{(x+1)\ln(x+1)+x} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x}{(x+1)\ln(x+1)+x} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{1}{2+\ln(x+1)} = \dfrac{1}{2}$



### Answer

$\displaystyle \lim_{x\rightarrow 0} (\dfrac{1}{\ln(x+1)} - \dfrac{1}{x}) = \dfrac{1}{2}$



## Exercise 7

### Statement

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-x-2}$



### Solution

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-x-2} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-x-2} \stackrel{L.H.} = \lim_{x\rightarrow 2} \dfrac{\dfrac{2}{2x-3}}{2x-1} = \dfrac{2}{3}$



### Answer

$\displaystyle \lim_{x\rightarrow 2} \dfrac{\ln(2x-3)}{x^2-x-2} = \dfrac{2}{3}$



## Exercise 8

### Statement

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^2+2x-3}{e^x-1}$



### Solution

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^2+2x-3}{e^x-1} = \dfrac{\infty}{\infty}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^2+2x-3}{e^x-1} \stackrel{L.H.} = \lim_{x\rightarrow \infty} \dfrac{2x+2}{e^x} = \dfrac{\infty}{\infty}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{2x+2}{e^x} = \lim_{x\rightarrow \infty} \dfrac{2}{e^x} = 0$



### Answer

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{x^2+2x-3}{e^x-1} = 0$ 



## Exercise 9

### Statement

$\displaystyle \lim_{x\rightarrow 0} x\cot x$



### Solution

$\displaystyle \lim_{x\rightarrow 0} x \cot x = 0\cdot \infty$

轉換表達式，得到$\displaystyle \lim_{x\rightarrow 0} \dfrac{x}{\dfrac{1}{\cot x}} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x}{\dfrac{1}{\cot x}} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{1}{\sec^2x} = 1$



### Answer

$\displaystyle \lim_{x\rightarrow 0} x\cot x = 1$



## Exercise 10

### Statement

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1-\cos x}{\ln(1+x^2)}$



### Solution

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1-\cos x}{\ln(1+x^2)} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1-\cos x}{\ln(1+x^2)} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{\sin x}{\dfrac{2x}{1+x^2}} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0}\dfrac{\sin x}{\dfrac{2x}{1+x^2}} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{\cos x}{\dfrac{(1+x^2)(2)-(2x)(2x)}{(1+x^2)^2}} = \dfrac{1}{2}$



### Answer

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1-\cos x}{\ln(1+x^2)} = \dfrac{1}{2}$



## Exercise 11

### Statement

$\displaystyle \lim_{x\rightarrow \infty} x\ln(\dfrac{2x+1}{2x-1})$



### Solution

$\displaystyle \lim_{x\rightarrow \infty} x\ln(\dfrac{2x+1}{2x-1}) = \lim_{x\rightarrow \infty}x \lim_{x\rightarrow \infty} \ln(\dfrac{2x+1}{2x-1}) = \infty \cdot 0$

轉換表達式

$\displaystyle \lim_{x\rightarrow \infty} x \ln(\dfrac{2x+1}{2x-1})  = \lim_{x\rightarrow \infty} \dfrac{\ln(\dfrac{2x+1}{2x-1})}{\dfrac{1}{x}} \stackrel{L.H.} = \lim_{x\rightarrow \infty} \dfrac{-\dfrac{4}{4x^2-1}}{\dfrac{-1}{x^2}} = \lim_{x\rightarrow \infty} \dfrac{4x^2}{4x^2-1} = 1$



### Answer

$\displaystyle \lim_{x\rightarrow \infty} x\ln(\dfrac{2x+1}{2x-1}) = 1$



## Exercise 12

### Statement

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x-\sin x}{x^3}$



### Solution

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x-\sin x}{x^3} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x-\sin x}{x^3} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{1-\cos x}{3x^2} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{1-\cos x}{3x^2} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{1+\sin x}{6x} = \dfrac{0}{1} = D.N.E.$



### Answer

$\displaystyle \lim_{x\rightarrow 0} \dfrac{x-\sin x}{x^3} = D.N.E.$



## Exercise 13

### Statement

$\displaystyle \lim_{x\rightarrow 0} (\dfrac{1}{x\sqrt{x+1}} - \dfrac{1}{x})$



### Solution

$\displaystyle \lim_{x\rightarrow 0} (\dfrac{1}{x\sqrt{x+1}} - \dfrac{1}{x}) = \lim_{x\rightarrow 0} (\dfrac{x-x\sqrt{x+1}}{x^2\sqrt{x+1}}) = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0}(\dfrac{x-x\sqrt{x+1}}{x^2\sqrt{x+1}}) \stackrel{L.H.} = \lim_{x\rightarrow 0}(\dfrac{\dfrac{2\sqrt{x+1}-3x-2}{2\sqrt{x+1}}}{\dfrac{5x^2+4x}{2\sqrt{x+1}}}) = \lim_{x\rightarrow 0}\dfrac{2\sqrt{x+1}-3x-2}{5x^2+4x} = \dfrac{0}{0}$

因此我們使用羅畢達

$\displaystyle \lim_{x\rightarrow 0} \dfrac{2\sqrt{x+1}-3x-2}{5x^2+4x} \stackrel{L.H.} = \lim_{x\rightarrow 0} \dfrac{\dfrac{1}{\sqrt{x+1}}-3}{10x+4} = -\dfrac{1}{2}$



### Answer

$\displaystyle \lim_{x\rightarrow 0} (\dfrac{1}{x\sqrt{x+1}} - \dfrac{1}{x}) = -\dfrac{1}{2}$



## Exercise 21

### Statement

$\displaystyle \lim_{x\rightarrow \infty} x(2\tan^{-1}x - \pi)$



### Solution

$\displaystyle \lim_{x\rightarrow \infty} x(2\tan^{-1}x - \pi) = \infty \cdot 0$

故我們改寫式子

$\displaystyle \lim_{x\rightarrow \infty} x(2\tan^{-1}x - \pi) = \lim_{x\rightarrow \infty} \dfrac{2\tan^{-1}x - \pi}{\dfrac{1}{x}} = \dfrac{0}{0}$

故我們使用羅畢達

$\displaystyle \lim_{x\rightarrow \infty} \dfrac{2\tan^{-1}x - \pi}{\dfrac{1}{x}} \stackrel{L.H.} = \lim_{x\rightarrow \infty} \dfrac{\dfrac{2}{1+x^2}}{\dfrac{-1}{x^2}} = \lim_{x\rightarrow \infty} -\dfrac{2x^2}{1+x^2} = -2$

故$\displaystyle \lim_{x\rightarrow \infty} x(2\tan^{-1}x - \pi) = -2$



### Answer

$\displaystyle \lim_{x\rightarrow \infty} x(2\tan^{-1}x - \pi) = -2$



## Exercise 26

### Statement

$\displaystyle \lim_{x\rightarrow 0^+} (\csc x)^{\sin^2 x}$



### Solution

$\displaystyle \lim_{x\rightarrow 0^+} (\csc x)^{\sin^2 x} = \lim_{x\rightarrow 0^+} e^{\sin^2x\ln(\csc x)}$

令$y = e^{\sin^2x \ln(\csc x)}$，則$\ln(y) = \sin^2 x \ln(\csc x)$

將問題轉換成$\displaystyle \lim_{x\rightarrow 0^+} \sin^2 x \ln(\csc x)$，再還原去掉$\ln$

$\displaystyle \lim_{x\rightarrow 0^+} \sin^2 x \ln(\csc x) = 0\cdot \infty$

故我們改寫式子

$\displaystyle \lim_{x\rightarrow 0^+} \sin^2 x \ln(\csc x) = \lim_{x\rightarrow 0^+} \dfrac{\ln(\csc x)}{\csc^2 x} = \dfrac{\infty}{\infty}$

因此我們可以使用羅畢達

$\displaystyle \lim_{x\rightarrow 0^+} \dfrac{\ln(\csc x)}{\csc^2 x} \stackrel{L.H.} = \lim_{x\rightarrow 0^+} \sin^2 x = 0$

還原去掉$\ln$，$y = e^0 =  1$，故$\displaystyle \lim_{x\rightarrow 0^+} (\csc x)^{\sin^2 x} = 1$



### Answer

$\displaystyle \lim_{x\rightarrow 0^+} (\csc x)^{\sin^2 x} = 1$



## Exercise 27

### Statement

$\displaystyle \lim_{x\rightarrow 1} x^{\frac{1}{x-1}}$



### Soluton

$\displaystyle \lim_{x\rightarrow 1} x^{\frac{1}{x-1}} = \displaystyle \lim_{x\rightarrow 1} e^{\frac{1}{x-1}\ln(x)}$

$y = e^{\frac{1}{x-1}\ln(x)}, \ln(y) = \dfrac{1}{x-1}\ln(x)$

將問題轉成計算$\displaystyle \lim_{x\rightarrow 1} \dfrac{1}{x-1}\ln(x)$，再還原$\ln(y)$為$y$

$\displaystyle \lim_{x\rightarrow 1} \dfrac{1}{x-1}\ln(x) = \infty\cdot 0$

故改變形式

$\displaystyle \lim_{x\rightarrow 1} \dfrac{\ln(x)}{x-1} = \dfrac{0}{0}$

因此使用羅畢達

$\displaystyle \lim_{x\rightarrow 1} \dfrac{\ln(x)}{x-1} \stackrel{L.H.} = \lim_{x\rightarrow 1} \dfrac{1}{x} = 1$

還原$\ln(y)$為$y$，$\displaystyle \lim_{x\rightarrow 1} \dfrac{1}{x-1}\ln(x) = 1$，因此$\displaystyle \lim_{x\rightarrow 1} e^{\frac{1}{x-1}\ln(x)} = e^1 = e$

故$\displaystyle \lim_{x\rightarrow 1} x^{\frac{1}{x-1}} = e$



### Answer

$\displaystyle \lim_{x\rightarrow 1} x^{\frac{1}{x-1}} = e$

