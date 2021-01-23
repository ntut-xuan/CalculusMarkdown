# 洪輝霖微積分Practice Ch 6.2

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

$\int \cos^2 3x\ dx$



### Solution

令$u=3x$，則$du = 3dx$，$dx = \dfrac{1}{3}du$

$\int \cos^2u \cdot \dfrac{1}{3} du = \dfrac{1}{3}\int \cos^2 u\ du$

因為$\cos^2 x = \dfrac{\cos 2x + 1}{2}$

所以$\dfrac{1}{3} \int \cos^2 u\ du = \dfrac{1}{3}\int \dfrac{\cos 2u + 1}{2} du = \dfrac{1}{6}\int (\cos 2u + 1) du = \dfrac{\sin 2u}{12} + \dfrac{u}{2} = \dfrac{\sin 6x}{12} + \dfrac{x}{2} + C$



### Answer

$\int \cos^2 3x\ dx = \dfrac{\sin 6x}{12} + \dfrac{x}{2} + C$



## Exercise 2

### Statement

$\int \sin^4x \cos^3 x\ dx$



### Solution

$\int \sin^4x \cos^3x\ dx = \int \sin^4x \cos^2x \cos x\ dx$

令$u = \sin x$，則$du = \cos x\ dx, dx = \dfrac{du}{\cos x}$

因此$\int \sin^4x \cos^2 x \cos x\ dx = \int u^4(1-u^2)du = \int u^4-u^6 du = \dfrac{u^5}{5}-\dfrac{u^7}{7} = \dfrac{\sin^5 x}{5}- \dfrac{\sin^7 x}{7} + C$



### Answer

$\int \sin^4x \cos^3 x\ dx = \dfrac{\sin^5 x}{5} - \dfrac{\sin^7 x}{7} + C$



## Exercise 3

### Statement

$\displaystyle \int^{\frac{\pi}{2}}_0 \sin^2 x\ dx$



### Solution

$\sin^2 x = \dfrac{1-\cos 2x}{2}$

因此$\displaystyle \int^{\frac{\pi}{2}}_0 \sin^2 x\ dx = \int^{\frac{\pi}{2}}_0 \dfrac{1-\cos 2x}{2} dx$

$\displaystyle = \int^{\frac{\pi}{2}}_0 \dfrac{1}{2} dx - \int^{\frac{\pi}{2}}_0 \dfrac{\cos 2x}{2} dx$

$= \displaystyle \dfrac{x}{2} |^\frac{\pi}{2}_0 - \dfrac{\sin 4x}{4}|^\frac{\pi}{2}_0 = \frac{\pi}{4}$



### Answer

$\displaystyle \int^{\frac{\pi}{2}}_0 \sin^2 x\ dx = \dfrac{\pi}{4}$



## Exercise 4

### Statement

$\displaystyle \int^{\frac{\pi}{2}}_0 \cos^4 x\ dx$



### Solution

$\displaystyle \int^{\frac{\pi}{2}}_0 \cos^4 x\ dx = \int^{\frac{\pi}{2}}_0 (\cos^2 x)^2\ dx = \int^{\frac{\pi}{2}}_0 (\dfrac{\cos 2x+1}{2})^2\ dx = \int^{\frac{\pi}{2}}_0 \dfrac{\cos^2 2x-2\cos 2x + 1}{4}\ dx$

利用微積分基本定理，將積分化成多個積分形式

$\displaystyle \int^{\frac{\pi}{2}}_0 \dfrac{\cos^2 2x-2\cos 2x + 1}{4}\ dx = \dfrac{1}{4}\int^{\frac{\pi}{2}}_0 \cos^2 2x\ dx- \dfrac{1}{2}\int^{\frac{\pi}{2}}_0 \cos2x\ dx + \dfrac{1}{4}\int^{\frac{\pi}{2}}_01dx$

$= \dfrac{1}{8}(\dfrac{\sin4x}{4}+x)|^{\frac{\pi}{2}}_0 - \dfrac{1}{2}(\dfrac{\sin 2x}{2})|^{\frac{\pi}{2}}_0 + \dfrac{1}{4}(x)|^\frac{\pi}{2}_0 = \dfrac{3\pi}{16}$



### Answer

$\displaystyle \int^{\frac{\pi}{2}}_0 \cos^4 x\ dx = \dfrac{3\pi}{16}$



## Exercise 5

### Statement

$\displaystyle \int^{\pi}_0 \sin^3x\cos^2x\ dx$



### Solution

$\displaystyle \int^{\pi}_0 \sin^3x\cos^2x\ dx = \displaystyle \int^{\pi}_0 \sin^2x\cos^2x\sin x\ dx$

令$u = \cos x$，則$du = -\sin x dx$，因此$dx = -\dfrac{du}{\sin x}$

$\displaystyle \int^{\pi}_0 \sin^2x\cos^2x\sin x\ dx = -\int^{-1}_{1} (1-u^2)u^2 du = -\int^{-1}_{1} (u^2-u^4) du$

$\displaystyle -(\dfrac{u^3}{3}|^{-1}_1 - \dfrac{u^5}{5}|^{-1}_{1}) = -(-\dfrac{2}{3}+\dfrac{2}{5}) = \dfrac{4}{15}$



### Answer

$\displaystyle \int^{\pi}_0 \sin^3x\cos^2x\ dx = \dfrac{4}{15}$



## Exercise 6

### Statement

$\displaystyle \int \dfrac{\cos^3x}{\sqrt{\sin x}} dx$



### Solution

$\displaystyle \int \dfrac{\cos^3x}{\sqrt{\sin x}} dx = \int \dfrac{\cos^2x}{\sqrt{\sin x}} \cos xdx = \int \dfrac{1-\sin^2 x}{\sqrt{\sin x}} \cos x dx$

令$u = \sin x$，則$du = \cos x dx$，因此$dx = \dfrac{du}{\cos x}$

因此$\displaystyle \int \dfrac{1-\sin^2 x}{\sqrt{\sin x}} \cos x dx$

$= \displaystyle  \int \dfrac{1-u^2}{\sqrt{u}} \cos x \dfrac{du}{\cos x} = \int \dfrac{1-u^2}{\sqrt{u}}du =\int \dfrac{1}{\sqrt{u}}du - \dfrac{u^2}{\sqrt{u}} du = \int u^\frac{-1}{2}du - \int u^\frac{3}{2}du = 2\sqrt{u}-\dfrac{2}{5}\sqrt{u^5}$

還原$u$，得到$\displaystyle \int \dfrac{1-\sin^2 x}{\sqrt{\sin x}} \cos x dx = 2\sqrt{\sin x}-\dfrac{2}{5}\sqrt{\sin^5x}$

因此$\displaystyle \int \dfrac{\cos^3x}{\sqrt{\sin x}} dx = 2\sqrt{\sin x}-\dfrac{2}{5}\sqrt{\sin^5x} + C$



### Answer

$\displaystyle \int \dfrac{\cos^3x}{\sqrt{\sin x}} dx = 2\sqrt{\sin x}-\dfrac{2}{5}\sqrt{\sin^5x} + C$



## Exercise 7

### Statement

$\displaystyle \int \dfrac{\sin^3 x}{\cos^2 x}dx$



### Solution

$\displaystyle \int \dfrac{\sin^3 x}{\cos^2 x}dx = \displaystyle \int \dfrac{\sin^2 x}{\cos^2 x}\sin xdx$

令$u = \cos x$，則$du = -\sin x dx$，因此$dx = -\dfrac{du}{\sin x}$

$\displaystyle \int \dfrac{\sin^2 x}{\cos^2 x}\sin xdx = \int \dfrac{1-\cos^2 x}{\cos^2 x}\sin xdx = \int \dfrac{1-u^2}{u^2}\sin x\dfrac{-du}{\sin x} = -\int \dfrac{1-u^2}{u^2}du$

$= -(\displaystyle \int \dfrac{1}{u^2} du - \int 1 du) = -(-u^{-1}-u)= \dfrac{1}{u}+u$

還原$u$，得到$\displaystyle \int \dfrac{\sin^2 x}{\cos^2 x}\sin xdx = \dfrac{1}{\cos x}+\cos x$

因此$\displaystyle \int \dfrac{\sin^3 x}{\cos^2 x}dx = \dfrac{1}{\cos x} + \cos x + C = \sec x + \cos  x + C$



### Answer

$\displaystyle \int \dfrac{\sin^3 x}{\cos^2 x}dx = \sec x + \cos  x + C$



## Exercise 8

### Statement

$\displaystyle \int \sin^2 x \cot^3 x dx$



### Solution

$\displaystyle \int \sin^2 x \cot^3 x dx = \int \sin^2 x \dfrac{\cos^3 x}{\sin^3 x} dx = \int \dfrac{\cos^3 x}{\sin x} dx = \int \dfrac{\cos^2 x}{\sin x}\cos x dx = \int \dfrac{1-\sin^2 x}{\sin x} \cos xdx$

令$u = \sin x$，則$du = \cos x dx$，因此$dx = \dfrac{du}{\cos x}$

$\displaystyle \int \dfrac{1-\sin^2 x}{\sin x} \cos xdx = \int \dfrac{1-u^2}{u}\cos x\dfrac{du}{\cos x} = \int \dfrac{1-u^2}{u}du = \int \dfrac{1}{u}du - \int u du = \ln(|u|)-\dfrac{u^2}{2}$

還原$u$，因此$\displaystyle \int \sin^2 x \cot^3 x dx = \ln(|\sin x|) - \dfrac{\sin^2 x}{2} + C$



### Answer

$\displaystyle \int \sin^2 x \cot^3 x dx = \ln(|\sin x|) - \dfrac{\sin^2 x}{2} + C$



## Exercise 9

### Statement

$\displaystyle \int \sec^2 x \tan^4 x dx$



### Solution

令$u = \tan x$，則$du = \sec^2 x dx$，因此$dx = \dfrac{du}{\sec^2 x}$

$\displaystyle \int \sec^2 x\tan^4 x dx = \int \sec^2 x u^4\dfrac{du}{\sec^2 x} = \int u^4du = \dfrac{u^5}{5}$

還原$u$，得到$\displaystyle \int \sec^2 x \tan^4 x dx = \dfrac{\tan^5 x}{5} + C$



### Answer

$\displaystyle \int \sec^2 x \tan^4 x dx = \dfrac{\tan^5 x}{5} + C$



### Answer

$\displaystyle \int \sec x \tan^3 x dx = -\dfrac{1}{3\cos^3 x}+\dfrac{1}{\cos x} + C$



## Exercise 10

### Statement

$\displaystyle \int \tan^2 x dx$



### Solution

$\displaystyle \int \tan^2 x dx = \int (\sec^2 x - 1)dx = \int \sec^2x dx - \int 1dx = \tan x-x$

因此$\displaystyle \int \tan^2 x dx = \tan x - x + C$



### Answer

$\displaystyle \int \tan^2 x dx = \tan x - x + C$



## Exercise 11

### Statement

$\displaystyle \int \cot^2 x dx$



### Solution

$\displaystyle \int \cot^2 x dx = \int \dfrac{\cos^2 x}{\sin^2 x} dx = \int \dfrac{1-\sin^2 x}{\sin^2 x} dx = \int \dfrac{1}{\sin^2 x}dx - \int1 dx = -\cot x - x$

因此$\displaystyle \int \cot^2 x dx = -\cot x - x + C$



### Answer

$\displaystyle \int \cot^2 x dx = -\cot x - x + C$



## Exercise 12

### Statement

$\displaystyle \int \sec x \tan^3 x dx$



### Solution

$\displaystyle \int \sec x \tan^3 x dx = \int \dfrac{1}{\cos x}\dfrac{\sin^3 x}{\cos^3 x} dx = \int \dfrac{\sin^3 x}{\cos^4 x} dx = \int \dfrac{\sin^2 x}{\cos^4 x}\sin xdx = \int \dfrac{1-\cos^2 x}{\cos^4 x}\sin x dx$

令$u = \cos x$，則$du = -\sin x dx$，因此$dx = \dfrac{du}{-\sin x}$

$\displaystyle \int \dfrac{1-\cos^2 x}{\cos^4 x}\sin x dx = -\int \dfrac{1-u^2}{u^4}du = -(\int \dfrac{1}{u^4}du - \int \dfrac{1}{u^2}du) = \dfrac{1}{3u^3}-\dfrac{1}{u} = \dfrac{1}{3\cos^3 x}-\dfrac{1}{\cos x}$

因此$\displaystyle \int \sec x \tan^3 x dx = \dfrac{1}{3\cos^3 x} - \dfrac{1}{\cos x} + C$



### Answer

$\displaystyle \int \sec x \tan^3 x dx = \dfrac{1}{3\cos^3 x} - \dfrac{1}{\cos x} + C$



## Exercise 13

### Statement

$\displaystyle \int \sec^4x dx$



### Solution

$\displaystyle \int \sec^4x dx = \int \sec^2x \sec^2 x dx = \int (1+\tan^2x)(\sec^2x)dx$

令$u = \tan x$，則$du = \sec^2 x dx$，因此$dx = \dfrac{du}{\sec^2 x}$

$\displaystyle \int (1+\tan^2x)(\sec^2x)dx = \int(1+u^2)\sec^2x\dfrac{du}{\sec^2 x} = \int (1+u^2)du = u+\dfrac{u^3}{3}$

因此$\displaystyle \int \sec^4x dx = \tan x + \dfrac{\tan^3 x}{3} + C$



### Answer

$\displaystyle \int \sec^4x dx = \tan x + \dfrac{\tan^3 x}{3} + C$



## Exercise 14

### Statement

$\displaystyle \int \dfrac{\tan^3 x}{\cos^2 x}dx$



### Solution

$\displaystyle \int \dfrac{\tan^3 x}{\cos^2 x}dx = \int \tan^3 x \sec^2 xdx$

令$u = \tan x$，則$du = \sec^2x dx$，因此$dx = \dfrac{du}{\sec^2 x}$

$\displaystyle \int \tan^3x\sec^2 xdx = \int u^3\sec^2 x\dfrac{du}{\sec^2 x} = \int u^3du = \dfrac{u^4}{4}$

還原$u$，得到$\displaystyle \int \dfrac{\tan^3 x}{\cos^2 x}dx = \dfrac{\tan^4 x}{4} + C$



### Answer

$\displaystyle \int \dfrac{\tan^3 x}{\cos^2 x}dx = \dfrac{\tan^4 x}{4} + C$



## Exercise 15

### Statement

$\displaystyle \int \dfrac{1}{\sin^3 x\tan^3 x} dx$



### Solution

$\displaystyle \int \dfrac{1}{\sin^3 x\tan^3 x} dx = \int \dfrac{1}{\sin^3 x\dfrac{\sin^3 x}{\cos^3 x}} dx = \int \dfrac{\cos^3 x}{\sin^6 x} dx = \int \dfrac{\cos^2 x}{\sin^6 x}\cos x dx = \int \dfrac{1-\sin^2 x}{\sin^6 x} \cos x dx$

令$u = \sin x$，則$du = \cos x dx$，因此$dx = \dfrac{du}{\cos x}$

$\displaystyle \int \dfrac{1-\sin^2 x}{\sin^6 x} \cos x dx = \int \dfrac{1-u^2}{u^6}\cos x\dfrac{du}{\cos x} = \int \dfrac{1-u^2}{u^6}du$

$\displaystyle \int \dfrac{1-u^2}{u^6}du = \int \dfrac{1}{u^6}du-\int \dfrac{1}{u^4}du = -\dfrac{1}{5u^5}+\dfrac{1}{3u^3}$

還原$u$，得到$\displaystyle \int \dfrac{1}{\sin^3 x\tan^3 x} dx = -\dfrac{1}{5\sin^5x}+\dfrac{1}{3\sin^3x}+C$



### Answer

$\displaystyle \int \dfrac{1}{\sin^3 x\tan^3 x} dx = -\dfrac{1}{5\sin^5x}+\dfrac{1}{3\sin^3 x}+C$



## Exercise 16

### Statement

$\displaystyle \int \sin 3x\cos 2x dx$



### Solution

$\displaystyle \int \sin 3x\cos 2x dx = \int(\dfrac{1}{2}\sin x +\dfrac{1}{2}\sin5x)dx = \dfrac{1}{2}\int\sin xdx+\dfrac{1}{2}\int \sin 5xdx = -\dfrac{1}{2}\cos x - \dfrac{1}{10}\cos 5x$

因此$\displaystyle \int \sin 3x\cos 2x dx = -\dfrac{1}{2}\cos x - \dfrac{1}{10}\cos 5x + C$



### Answer

$\displaystyle \int \sin 3x\cos 2x dx = -\dfrac{1}{2}\cos x - \dfrac{1}{10}\cos 5x + C$



## Exercise 17

### Statement

$\displaystyle \int^\frac{\pi}{6}_0 \cos x \cos 3x dx$



### Solution

先計算$\displaystyle \int \cos x \cos 3x dx$

$\displaystyle \int \cos x \cos 3x dx = \int \dfrac{1}{2}(\cos -2x + \cos 4x)dx = \dfrac{1}{2}\int \cos -2x dx + \dfrac{1}{2}\int \cos 4x dx = -\dfrac{1}{4}\sin -2x + \dfrac{1}{8}\sin 4x$

因此$\displaystyle \int \cos x \cos 3x dx = -\dfrac{1}{4}\sin(-2x)+\dfrac{1}{8}\sin 4x$

因此$\displaystyle \int^\frac{\pi}{6}_0 \cos x \cos 3x dx = (-\dfrac{1}{4}\sin(-2x)+\dfrac{1}{8}\sin 4x)|^\frac{\pi}{6}_0 = \dfrac{3\sqrt{3}}{16}$



### Answer

$\displaystyle \int^\frac{\pi}{6}_0 \cos x \cos 3x dx = \dfrac{3\sqrt{3}}{16}$



## Exercise 18

### Statement

$\displaystyle \int \sin 5x \sin 2x dx$



### Solution

$\displaystyle \int \sin 5x \sin 2x dx = \int \dfrac{1}{2}(\cos3x-\cos7x)dx = \dfrac{1}{2}\int \cos 3x - \int \cos 7x dx = \dfrac{1}{6}\sin 3x - \dfrac{1}{14}\sin 7x$

因此$\displaystyle \int \sin 5x \sin 2x dx = \dfrac{1}{6}\sin 3x - \dfrac{1}{14}\sin 7x + C$



### Answer

$\displaystyle \int \sin 5x \sin 2x dx = \dfrac{1}{6}\sin 3x - \dfrac{1}{14}\sin 7x + C$



## Exercise 19

### Statement

$\displaystyle \int \dfrac{1}{x^2\sqrt{4-x^2}} dx$



### Solution

令$x = 2\sin u$，則$dx  = 2\cos u du$，且$u = \arcsin(\dfrac{x}{2})$

$\displaystyle \int \dfrac{1}{x^2\sqrt{4-x^2}} dx = \int \dfrac{1}{4\sin^2 u \sqrt{4-4\sin^2u}} 2\cos u du = \int \dfrac{1}{4\sin^2u2\cos u}2\cos udu = \int\dfrac{1}{4\sin^2u}du$

$\displaystyle \int\dfrac{1}{4\sin^2u}du = \int 4\csc^2 udu = 4\int\csc^2udu = -4\cot u = -4\cot(\arcsin(\dfrac{x}{2})) = -\dfrac{\sqrt{4-x^2}}{4x}$

因此$\displaystyle \int \dfrac{1}{x^2\sqrt{4-x^2}} dx = -\dfrac{\sqrt{4-x^2}}{4x} + C$



### Answer

$\displaystyle \int \dfrac{1}{x^2\sqrt{4-x^2}} dx = -\dfrac{\sqrt{4-x^2}}{4x} + C$



## Exercise 20

### Statement

$\displaystyle \int^\frac{1}{2}_0 x^3\sqrt{9-4x^2}dx$



### Solution

令$t = 9-4x^2$，則$dt = -8xdx$，因此$dx = \dfrac{dt}{-8x}$，上界$8$，下界$9$

因此$\displaystyle \int^\frac{1}{2}_0 x^3\sqrt{9-4x^2}dx = \int^8_9x^3\sqrt{t}\dfrac{dt}{-8x} = \dfrac{1}{32}\int^8_9(t\sqrt{t}-9\sqrt{t})dt$

$\displaystyle = \dfrac{1}{32}(\dfrac{2t^\frac{5}{2}}{5}-6t^\frac{3}{2})|^9_8 = ( \dfrac{256\sqrt{2}}{5}-96\sqrt{2} - (\dfrac{486}{5}-162))\times \dfrac{1}{32} = \dfrac{324-224\sqrt{2}}{160} = \dfrac{81-56\sqrt{2}}{40}$



### Answer

$\dfrac{81-56\sqrt{2}}{40}$



## Exercise 21


### Statement

$\displaystyle \int \dfrac{x^3}{\sqrt{(4-x^2)^3}}dx$



### Solution

令$u = 4-x^2$，則$du = -2xdx$，因此$dx = -\dfrac{du}{2x}$

$\displaystyle \int \dfrac{x^3}{\sqrt{(4-x^2)^3}}dx = \int \dfrac{x^3}{\sqrt{u^3}}\dfrac{-du}{2x} = -\dfrac{1}{2}\int \dfrac{x^2}{\sqrt{u^3}}du = \dfrac{1}{2}\int \dfrac{u-4}{\sqrt{u^3}}du = \dfrac{1}{2}\int \dfrac{u}{\sqrt{u^3}}du - \dfrac{1}{2}\int \dfrac{4}{\sqrt{u^3}}du$

$= \displaystyle \dfrac{1}{2}\int u^\frac{-1}{2}du - 2\int u^\frac{-3}{2}du  = \sqrt{u}+\dfrac{4}{\sqrt{u}} = 2\sqrt{4-x^2}+\dfrac{4}{\sqrt{4-x^2}}$

因此$\displaystyle \int \dfrac{x^3}{\sqrt{(4-x^2)^3}}dx = \sqrt{4-x^2} + \dfrac{4}{\sqrt{4-x^2}} + C$



### Answer

$\displaystyle \int \dfrac{x^3}{\sqrt{(4-x^2)^3}}dx = \sqrt{4-x^2} + \dfrac{4}{\sqrt{4-x^2}} + C$