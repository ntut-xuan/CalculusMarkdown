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



## Exercise 22

### Statement

$\displaystyle \int \dfrac{1}{\sqrt{x^2-4}}dx$



### Solution

令$x = 2\sec u$，則$dx = 2\tan u \sec u du$，$u = \sec^{-1}(\dfrac{x}{2})$

$\displaystyle \int \dfrac{1}{\sqrt{x^2-4}}dx = \int \dfrac{2\tan u \sec u}{\sqrt{4\sec^2 u - 4}}du = \int \dfrac{2\tan u\sec u}{2\tan u}du = \int \sec u du$

計算$\displaystyle \int \sec u du$，$\displaystyle \int \sec u du = \int \dfrac{(\sec u)(\sec u + \tan u)}{(\sec u + \tan u)}du = \int \dfrac{\sec^2 u + \sec u \tan u}{\sec u + \tan u} du$

令$t = \sec u + \tan u$，則$dt = (\tan u \sec u + \sec^2 u)du$，因此$du = \dfrac{dt}{\tan u \sec u + \sec^2 u}$

因此$\displaystyle \int \dfrac{\sec^2 u + \sec u \tan u}{\sec u + \tan u} du = \int \dfrac{\sec^2 u + \tan u \sec u}{t} \dfrac{dt}{\tan u \sec u + \sec^2 u} = \int \dfrac{1}{t}dt = \ln(|t|) = \ln(|\sec u + \tan u|)$

故$\displaystyle \int \sec u du = \ln(|\sec u + \tan u|) = \ln(|\dfrac{x}{2} + \dfrac{\sqrt{x^2-4}}{2}|) = \ln(|x+\sqrt{x^2-4}|) - \ln(2)$

因此$\displaystyle \int \dfrac{1}{\sqrt{x^2-4}}dx = \ln(|x+\sqrt{x^2-4}|) + C$



### Answer

$\displaystyle \int \dfrac{1}{\sqrt{x^2-4}}dx = \ln(|x+\sqrt{x^2-4}|) + C$



## Exercise 23

### Statement

$\displaystyle \int \dfrac{1}{x^3\sqrt{x^2-1}}dx$



### Solution

令$x = \sec u$，則$dx = \sec u \tan u du$，$u = \sec^{-1}x$

因此$\displaystyle \int \dfrac{1}{x^3\sqrt{x^2-1}}dx = \int \dfrac{\sec u \tan u}{\sec^3 u \sqrt{\sec^2 u - 1}} du = \int \dfrac{\sec u \tan u}{\sec^3 u\tan u} = \int \cos^2 udu = \dfrac{\sin 2u}{4}+\dfrac{u}{2} = \dfrac{\sqrt{x^2-1}}{2x^2} + \dfrac{1}{2}\sec^{-1}x + C$



### Answer

$\displaystyle \int \dfrac{1}{x^3\sqrt{x^2-1}}dx = \dfrac{\sqrt{x^2-1}}{2x^2} + \dfrac{1}{2}\sec^{-1}x + C$



## Exercise 24

### Statement

$\displaystyle \int \dfrac{\sqrt{x^2-4}}{x^3}dx$



### Solution

令$x = 2\sec u$，則$dx = 2\sec u \tan u du$，$u = \sec^{-1}(\dfrac{x}{2})$

$\displaystyle \int \dfrac{\sqrt{x^2-4}}{x^3}dx = \int \dfrac{\sqrt{4\sec^2 u-4}}{8\sec^3 u}2\sec u\tan udu = \int \dfrac{4\sec u\tan^2 u}{8\sec^3 u}du = \dfrac{1}{2}\int \dfrac{\tan^2 u}{\sec^2 u}du = \dfrac{1}{2}\int \sin^2 u du$

$\displaystyle \dfrac{1}{2}\int \sin^2 u du = \dfrac{1}{2}\int (1-\cos^2 u)du = \dfrac{1}{2}\int1du - \dfrac{1}{2}\int \cos^2udu = \dfrac{u}{4}-\dfrac{\sin 2u}{8} = \dfrac{1}{4}\sec^{-1}(\dfrac{x}{2}) - \dfrac{\sqrt{x^2-4}}{2x^2}$

故$\displaystyle \int \dfrac{\sqrt{x^2-4}}{x^3}dx = \dfrac{1}{4}\sec^{-1}(\dfrac{x}{2}) - \dfrac{\sqrt{x^2-4}}{2x^2} + C$



### Answer

$\displaystyle \int \dfrac{\sqrt{x^2-4}}{x^3}dx = \dfrac{1}{4}\sec^{-1}(\dfrac{x}{2}) - \dfrac{\sqrt{x^2-4}}{2x^2} + C$



## Exercise 25

### Statement

$\displaystyle \int \dfrac{x^2}{\sqrt{2x-x^2}}dx$



### Solution

$\displaystyle \int \dfrac{x^2}{\sqrt{2x-x^2}}dx = \int \dfrac{x^2}{\sqrt{2x-x^2-1+1}}dx = \int \dfrac{x^2}{\sqrt{-(x-1)^2+1}}dx$

令$u = x-1$，則$du = dx$

因此$\displaystyle \int \dfrac{x^2}{\sqrt{-(x-1)^2+1}}dx = \int \dfrac{(u+1)^2}{\sqrt{1-u^2}}du = \int \dfrac{u^2+2u+1}{\sqrt{1-u^2}}du = \int \dfrac{u^2}{\sqrt{1-u^2}}du+\int \dfrac{2u}{\sqrt{1-u^2}}du+\int \dfrac{1}{\sqrt{1-u^2}}du$

計算$\displaystyle \int \dfrac{u^2}{\sqrt{1-u^2}}du$，令$u = \sin t$，則$du = \cos t dt$，$t = \arcsin(u)$

$\displaystyle \int \dfrac{u^2}{\sqrt{1-u^2}}du = \int \dfrac{\sin^2 t}{\cos t}\cot t dt = \int \sin^2 t dt = \dfrac{t}{2}-\dfrac{\sin2t}{4} = \dfrac{1}{2}\arcsin(u)-\dfrac{u\sqrt{1-u^2}}{2}$

計算$\displaystyle \int \dfrac{2u}{\sqrt{1-u^2}}du$，令$k = 1-u^2$，則$dk = -2udu$，$du=\dfrac{dk}{-2u}$

因此$\displaystyle \int \dfrac{2u}{\sqrt{1-u^2}}du = \int \dfrac{2u}{\sqrt{k}}\dfrac{dk}{-2u}  = -\int \dfrac{1}{\sqrt{k}}dk = -2\sqrt{k} = -2\sqrt{1-u^2}$

計算$\displaystyle \int \dfrac{1}{\sqrt{1-u^2}}du$，$\displaystyle \int \dfrac{1}{\sqrt{1-u^2}}du = \arcsin(u)$

故$\displaystyle \int \dfrac{u^2}{\sqrt{1-u^2}}du+\int \dfrac{2u}{\sqrt{1-u^2}}du+\int \dfrac{1}{\sqrt{1-u^2}}du = \dfrac{3}{2}\arcsin(u)-\dfrac{(u+4)\sqrt{1-u^2}}{2}$

還原$u$，得到$\displaystyle \int \dfrac{x^2}{\sqrt{2x-x^2}}dx = \dfrac{3}{2}\arcsin(x-1)-\dfrac{(x-3)\sqrt{1-u^2}}{2} + C$



### Answer

$\displaystyle \int \dfrac{x^2}{\sqrt{2x-x^2}}dx = \dfrac{3}{2}\arcsin(x-1)-\dfrac{(x-3)\sqrt{1-u^2}}{2} + C$



## Exercise 26

### Statement

$\displaystyle \int \dfrac{1}{x^2\sqrt{x^2+4}}dx$



### Solution

令$x = 2\tan u$，則$dx = 2\sec^2 u du$，$u = \arctan(\dfrac{x}{2})$

因此$\displaystyle \int \dfrac{1}{x^2\sqrt{x^2+4}}dx = \int \dfrac{2\sec^2 u}{4\tan^2u\sqrt{4\tan^2 u + 4}}du = \int \dfrac{2\sec^2 u}{8\tan^2u\sec u} = \dfrac{1}{4}\int \dfrac{\sec u}{\tan^2 u }du = \dfrac{1}{4}\int \dfrac{\cos u}{\sin^2 u}du$

$\displaystyle \dfrac{1}{4}\int \dfrac{\cos u}{\sin^2 u}du$，利用代換積分法，令$t = \sin u$，則$dt = \cos u du$，因此$du = \dfrac{dt}{\cos u}$

$\displaystyle \dfrac{1}{4}\int \dfrac{\cos u}{\sin^2 u}du = \dfrac{1}{4}\int \dfrac{\cos u}{t^2}\dfrac{dt}{\cos u} = \dfrac{1}{4}\int \dfrac{1}{t^2}dt = -\dfrac{1}{4t} = -\dfrac{1}{4\sin(u)}$

還原$u$，因此$\displaystyle \int \dfrac{1}{x^2\sqrt{x^2+4}}dx = -\dfrac{1}{4\sin(u)} = -\dfrac{1}{4\sin(\arctan(\dfrac{x}{2}))} = -\dfrac{\sqrt{x^2+4}}{4x} + C$



### Answer

$\displaystyle \int \dfrac{1}{x^2\sqrt{x^2+4}}dx = -\dfrac{\sqrt{x^2+4}}{4x}+C$



## Exercise 27

### Statement

$\displaystyle \int x\sqrt{1-x^4}dx$



### Solution

$\displaystyle \int x\sqrt{1-x^4}dx = \int x\sqrt{(1-x^2)(1+x^2)}dx$

令$u = x^2$，則$du = 2xdx$，因此$dx = \dfrac{du}{2x}$

因此$\displaystyle \int x\sqrt{(1-x^2)(1+x^2)}dx = \int x\sqrt{(1-u)(1+u)}\dfrac{du}{2x} = \dfrac{1}{2}\int\sqrt{1-u^2}du$

令$u = \sin t$，因此$du = \cos t dt$，$t = \arcsin(u)$

$\displaystyle \dfrac{1}{2}\int \sqrt{1-\sin^2t}\cos tdt = \dfrac{1}{2}\int \cos^2tdt = \dfrac{t}{4} + \dfrac{\sin2t}{8}$

還原$t$，因此$\displaystyle \dfrac{1}{2}\int\sqrt{1-u^2}du = \dfrac{\arcsin(u)}{4}+\dfrac{u\sqrt{1-u^2}}{4}$

因此$\displaystyle \int x\sqrt{1-x^4}dx = \dfrac{\arcsin(x^2)+x^2\sqrt{1-x^4}}{4}$



### Answer

$\displaystyle \int x\sqrt{1-x^4}dx = \dfrac{\arcsin(x^2)+x^2\sqrt{1-x^4}}{4}$



## Exercise 28

### Statement

$\displaystyle \int \dfrac{x}{\sqrt{3-2x-x^2}} dx$



### Solution

$\displaystyle \int \dfrac{x}{\sqrt{3-2x-x^2}} dx = \int \dfrac{x}{\sqrt{-x^2-2x-1+1+3}}dx = \int \dfrac{x}{\sqrt{-(x+1)^2+4}}$

令$u = x+1$，則$du = dx$

因此$\displaystyle \int \dfrac{x}{\sqrt{3-2x-x^2}} dx = \int \dfrac{u-1}{\sqrt{4-u^2}}du = \int \dfrac{u}{\sqrt{4-u^2}}du - \int \dfrac{1}{\sqrt{4-u^2}}du$

計算$\displaystyle \int \dfrac{u}{\sqrt{4-u^2}}du$，令$t = 4-u^2$，則$dt = -2udu$，因此$du = \dfrac{dt}{-2u}$

因此$\displaystyle \int \dfrac{u}{\sqrt{4-u^2}}du = \int \dfrac{u}{\sqrt{t}}\dfrac{dt}{-2u} = -\dfrac{1}{2}\int \dfrac{1}{\sqrt{t}}dt = -\sqrt{t}$

還原$t$，因此$\displaystyle \int \dfrac{u}{\sqrt{4-u^2}}du = -\sqrt{4-u^2}$

計算$\displaystyle \int \dfrac{1}{\sqrt{4-u^2}}du$，令$u = 2\sin k$，則$du = 2\cos kdk$，$k = \arcsin(\dfrac{u}{2})$

因此$\displaystyle \int \dfrac{1}{\sqrt{4-u^2}}du = \int \dfrac{2\cos k}{\sqrt{4-4\sin^2k}}dk = \int 1dk = k$

還原$k$，因此$\displaystyle \int \dfrac{1}{\sqrt{4-u^2}}du = \arcsin(\dfrac{u}{2})$

因此$\displaystyle \int \dfrac{u}{\sqrt{4-u^2}}du - \int \dfrac{1}{\sqrt{4-u^2}}du = -\sqrt{4-u^2}-\arcsin(\dfrac{u}{2})$

還原$u$，因此$\displaystyle \int \dfrac{x}{\sqrt{3-2x-x^2}} dx = -\sqrt{4-(x+1)^2}- \arcsin(\dfrac{x+1}{2}) = -\sqrt{3-x^2-2x}-\arcsin(\dfrac{x+1}{2}) + C$



### Answer

$\displaystyle \int \dfrac{x}{\sqrt{3-2x-x^2}} dx = -\sqrt{3-x^2-2x}-\arcsin(\dfrac{x+1}{2}) + C$



## Exercise 29

### Statement

$\displaystyle \int \dfrac{dx}{(x^2+2x+5)^2}$



### Solution

$\displaystyle \int \dfrac{dx}{(x^2+2x+5)^2} = \int \dfrac{1}{(x^2+2x+5)^2}dx = \int \dfrac{1}{(x^2+2x+1+4)^2}dx = \int \dfrac{1}{((x+1)^2+4)^2}dx$

令$u = x+1$，則$du = dx$

$\displaystyle \int \dfrac{1}{((x+1)^2+4)^2}dx = \int \dfrac{1}{(u^2+4)^2}du$

令$u = 2\tan t$，則$du = 2\sec^2 tdt$，$t = \arctan(\dfrac{u}{2})$

$\displaystyle \int \dfrac{1}{(u^2+4)^2}du = \int \dfrac{2\sec^2t}{(4\tan^2t+4)^2}dt = \int \dfrac{2\sec^2t}{16\sec^4t}dt = \int \dfrac{\cos^2 t}{8}dt = \dfrac{t}{16}+\dfrac{\sin2t}{32}$

還原$t$，因此$\displaystyle \int \dfrac{1}{(u^2+4)^2}du = \dfrac{1}{16}\arctan(\dfrac{u}{2}) + \dfrac{u}{8(u^2+4)}$

還原$u$，因此$\displaystyle \int \dfrac{dx}{(x^2+2x+5)^2} = \dfrac{1}{16}\arctan(\dfrac{x+1}{2}) + \dfrac{x+1}{8(x^2+2x+5)} + C$



### Answer

$\displaystyle \int \dfrac{dx}{(x^2+2x+5)^2} = \dfrac{1}{16}\arctan(\dfrac{x+1}{2}) + \dfrac{x+1}{8(x^2+2x+5)} + C$



## Exercise 30

### Statement

$\displaystyle \int^\frac{2}{3}_0 \dfrac{x^3}{\sqrt{(1+9x^2)^3}}dx$



### Solution

令$u = 1+9x^2$，則$du = 18xdx$，$dx = \dfrac{du}{18x}$

$\displaystyle \int^\frac{2}{3}_0 \dfrac{x^3}{\sqrt{(1+9x^2)^3}}dx = \int^5_1 \dfrac{u-1}{162\sqrt{u^3}}du = \dfrac{1}{162}\int^5_1\dfrac{u-1}{\sqrt{u^3}}du$

$\displaystyle \dfrac{1}{162}\int^5_1\dfrac{u-1}{\sqrt{u^3}}du = \dfrac{1}{162}\int^5_1\dfrac{u}{\sqrt{u^3}}du - \dfrac{1}{162}\int^5_1\dfrac{1}{\sqrt{u^3}} = \dfrac{\sqrt{u}}{81}|^5_1 + \dfrac{1}{81\sqrt{u}}|^5_1 = \dfrac{\sqrt{5}}{81}-\dfrac{1}{81}+\dfrac{1}{81\sqrt{5}}-\dfrac{1}{81} = \dfrac{2\sqrt{5}}{135}-\dfrac{2}{81}$



### Answer

$\displaystyle \int^\frac{2}{3}_0 \dfrac{x^3}{\sqrt{(1+9x^2)^3}}dx = \dfrac{2\sqrt{5}}{135}-\dfrac{2}{81}$



## Exercise 31

### Statement

$\displaystyle \int \dfrac{e^{2x}}{\sqrt{1-e^{4x}}}dx$



### Solution

$\displaystyle \int \dfrac{e^{2x}}{\sqrt{1-e^{4x}}}dx = \int \dfrac{e^{2x}}{\sqrt{1-(e^{2x})^2}}dx$

令$u = e^{2x}$，則$du = 2e^{2x}dx$，因此$dx = \dfrac{du}{2e^{2x}}$

$\displaystyle \int \dfrac{e^{2x}}{\sqrt{1-u^2}}\dfrac{du}{2e^{2x}} = \dfrac{1}{2}\int\dfrac{1}{\sqrt{1-u^2}}du = \dfrac{1}{2}\arcsin(u)$

還原$u$，得到$\displaystyle \int \dfrac{e^{2x}}{\sqrt{1-e^{4x}}}dx = \dfrac{\arcsin(e^{2x})}{2} + C$



### Answer

$\displaystyle \int \dfrac{e^{2x}}{\sqrt{1-e^{4x}}}dx = \dfrac{\arcsin(e^{2x})}{2} + C$



## Exercise 32

### Statement

$\displaystyle \int \dfrac{1}{e^{2x}\sqrt{1-e^{4x}}}dx$



### Solution

令$u = e^{2x}$，則$du = 2e^{2x}dx$，因此$dx = \dfrac{du}{2e^{2x}}$

因此$\displaystyle \int \dfrac{1}{e^{2x}\sqrt{1-e^{4x}}}dx = \int \dfrac{1}{u\sqrt{1-u^2}}\dfrac{du}{2u} = \dfrac{1}{2}\int \dfrac{1}{u^2\sqrt{1-u^2}}du$

令$u = \sin t$，則$du = \cos tdt$，$t = \arcsin(u)$

因此$\displaystyle \dfrac{1}{2}\int \dfrac{1}{u^2\sqrt{1-u^2}}du = \dfrac{1}{2}\int\dfrac{\cos t}{\sin^2 t\sqrt{1-\sin^2t}}dt = \dfrac{1}{2}\int \dfrac{1}{\sin^2t}dt = \dfrac{-\cot t}{2}$

還原$t$，得到$\displaystyle \dfrac{1}{2}\int \dfrac{1}{u^2\sqrt{1-u^2}}du = \dfrac{-\cot t}{2} = \dfrac{-\cot(\arcsin(u))}{2} = \dfrac{-\sqrt{1-u^2}}{2u}$

還原$u$，得到$\displaystyle \int \dfrac{1}{e^{2x}\sqrt{1-e^{4x}}}dx = \dfrac{-\sqrt{1-e^{4x}}}{2e^{2x}} + C$



### Answer	

$\displaystyle \int \dfrac{1}{e^{2x}\sqrt{1-e^{4x}}}dx = \dfrac{-\sqrt{1-e^{4x}}}{2e^{2x}} + C$



## Exercise 33

### Statement

$\displaystyle \int \dfrac{1}{\sqrt{1+e^{2x}}}dx$



### Solution

令$u = e^x$，則$du = e^x dx$，因此$dx = \dfrac{du}{e^x}$

因此$\displaystyle \int \dfrac{1}{\sqrt{1+e^{2x}}}dx = \int \dfrac{1}{\sqrt{1+u^2}}\dfrac{du}{u} = \int \dfrac{1}{u\sqrt{1+u^2}}du$

令$u = \tan t$，則$du = \sec^2 tdt$，$t = \arctan(u)$

因此$\displaystyle \int \dfrac{1}{u\sqrt{1+u^2}}du = \int \dfrac{\sec^2 t}{\tan t\sqrt{1+\tan t}}dt = \int \dfrac{\sec t}{\tan t} dt = \int \dfrac{1}{\sin t}dt$ 

計算$\displaystyle \int \dfrac{1}{\sin t}dt$，$\displaystyle \int \dfrac{1}{\sin t}dt = \int \dfrac{1}{2\sin(\dfrac{t}{2})\cos(\dfrac{t}{2})}dt$

分子分母同乘$\sec^2 (\dfrac{t}{2})$，則$\displaystyle \int \dfrac{1}{2\sin(\dfrac{t}{2})\cos(\dfrac{t}{2})}dt = \int \dfrac{\sec^2(\dfrac{t}{2})}{2\tan(\dfrac{t}{2})}dt = \dfrac{1}{2}\int \dfrac{\sec^2(\dfrac{t}{2})}{\tan(\dfrac{t}{2})}dt$

令$k = \tan(\dfrac{t}{2})$，則$dk = \dfrac{1}{2}\sec^2(\dfrac{t}{2})dt$，因此$dt = \dfrac{2}{\sec^2(\dfrac{t}{2})}dk$

$\displaystyle \dfrac{1}{2}\int \dfrac{\sec^2(\dfrac{t}{2})}{\tan(\dfrac{t}{2})}dt = \dfrac{1}{2}\int \dfrac{\sec^2(\dfrac{t}{2})}{k}\dfrac{2}{\sec^2(\dfrac{t}{2})}dk = \int\dfrac{1}{k}dk = \ln(|k|)$

還原$k$，得到$\displaystyle \int \dfrac{1}{\sin t}dt = \ln(|\tan(\dfrac{t}{2})|)$

還原$t$，得到$\displaystyle \int \dfrac{1}{u\sqrt{1+u^2}}du = \ln(|\tan(\dfrac{t}{2})|) = \ln(|\dfrac{1-\dfrac{1}{\sqrt{u^2+1}}}{\dfrac{u}{\sqrt{u^2+1}}}|) = \ln(|\dfrac{\sqrt{u^2+1}-1}{u}|)$

還原$u$，得到$\displaystyle \int \dfrac{1}{\sqrt{1+e^{2x}}}dx = \ln(|\dfrac{\sqrt{e^{2x}+1}-1}{e^{2x}}|)$

因此$\displaystyle \int \dfrac{1}{\sqrt{1+e^{2x}}}dx = \ln(|\dfrac{\sqrt{e^{2x}+1}-1}{e^{2x}}|) + C$



### Answer

$\displaystyle \int \dfrac{1}{\sqrt{1+e^{2x}}}dx = \ln(|\dfrac{\sqrt{e^{2x}+1}-1}{e^{2x}}|) + C$



## Exercise 34

### Statement

$\displaystyle \int \dfrac{\sqrt{x}}{\sqrt{1-x}}dx$



### Solution

令$x = u^2$，則$dx = 2udu$，$u = \sqrt{x}$

因此$\displaystyle \int \dfrac{\sqrt{x}}{\sqrt{1-x}}dx = \int \dfrac{2u^2}{\sqrt{1-u^2}}du$

令$u = \sin t$，則$du = \cos t dt$，$t = \arcsin(u)$

因此$\displaystyle \int \dfrac{2u^2}{\sqrt{1-u^2}}du = \int \dfrac{2\sin^2 t}{\sqrt{1-\sin^2 t}}\cos tdt = \int 2\sin ^2tdt = t-\cos(2t)$

還原$t$，得到$\displaystyle \int \dfrac{2u^2}{\sqrt{1-u^2}}du = \arcsin(u)-u\sqrt{1-u^2}$

還原$u$，得到$\displaystyle \int \dfrac{\sqrt{x}}{\sqrt{1-x}}dx = \arcsin(\sqrt{x})-\sqrt{x}\sqrt{1-x}$

因此$\displaystyle \int \dfrac{\sqrt{x}}{\sqrt{1-x}}dx = \arcsin(\sqrt{x})-\sqrt{x}\sqrt{1-x} + C$



### Answer

$\displaystyle \int \dfrac{\sqrt{x}}{\sqrt{1-x}}dx = \arcsin(\sqrt{x})-\sqrt{x}\sqrt{1-x} + C$



## Exercise 35

### Statement

$\displaystyle \int \dfrac{1}{\sqrt{x}(1+x)}dx$



### Solution

令$u = \sqrt{x}$，則$du = \dfrac{1}{2\sqrt{x}}dx$，因此$dx = 2\sqrt{x}du$

因此$\displaystyle \int \dfrac{1}{\sqrt{x}(1+x)}dx = 2\int \dfrac{1}{1+u^2}du$

令$u = \tan t$，則$du = \sec^2 t dt$，$t = \arctan(u)$

因此$\displaystyle 2\int \dfrac{\sec^2t}{1+\tan^2 t} dt = 2\int 1t = 2t$

還原$t$，得到$\displaystyle 2\int \dfrac{1}{1+u^2}du = 2\arctan(u)$

還原$u$，得到$\displaystyle \int \dfrac{1}{\sqrt{x}(1+x)}dx = 2\arctan(\sqrt{x})$

因此$\displaystyle \int \dfrac{1}{\sqrt{x}(1+x)}dx = 2\arctan(\sqrt{x}) + C$



### Answer

$\displaystyle \int \dfrac{1}{\sqrt{x}(1+x)}dx = 2\arctan(\sqrt{x}) + C$



## Exercise 36

### Statement

$\displaystyle \int^1_0 \sqrt{4x-x^2}dx$



### Solution

$\displaystyle \int^1_0 \sqrt{4x-x^2}dx = \int^1_0 \sqrt{x}{\sqrt{4-x}}dx$

令$u =\sqrt{x}$，則$du = \dfrac{dx}{2\sqrt{x}}$，因此$dx = 2\sqrt{x}du$，$x = 1\Rightarrow u = 1$，$x = 0\Rightarrow u = 0$

$\displaystyle \int^1_0 \sqrt{x}{\sqrt{4-x}}dx =\int^1_0 2u^2\sqrt{4-u^2}du$

令$u = 2\sin t$，則$du = 2\cos t dt$，$t = \arcsin(\dfrac{u}{2})$，$u = 1 \Rightarrow t = \dfrac{\pi}{6}$，$u = 0 \Rightarrow t = 0$

$\displaystyle \int^1_0 2u^2\sqrt{4-u^2}du = \int^\frac{\pi}{6}_0 8\sin^2 t \sqrt{4-4\sin^2t}2\cos tdt = \int^\frac{\pi}{6}_0 32\sin^2t\cos^2tdt = 32\int^\frac{\pi}{6}_0 \dfrac{\sin^2(2t)}{4}dt$

$\displaystyle 32\int^\frac{\pi}{6}_0 \dfrac{\sin^2(2t)}{4}dt = 32 \int^\frac{\pi}{6}_0 \dfrac{(\dfrac{1-\cos 4t}{2})}{4}dt = 32 \int^\frac{\pi}{6}_0 \dfrac{1}{8}dt - 32 \int^\frac{\pi}{6}_0 \dfrac{\cos 4t}{8}dt = 4t|^\frac{\pi}{6}_0 + \sin 4t|^\frac{\pi}{6}_0 = \dfrac{2\pi}{3}-\dfrac{\sqrt{3}}{2}$



### Answer

$\displaystyle \int^1_0 \sqrt{4x-x^2}dx = \dfrac{2\pi}{3}-\dfrac{\sqrt{3}}{2}$



## Exercise 37

### Statement

$\displaystyle \int \dfrac{1}{1+e^{2x}}dx$



### Solution

令$u = e^x$，則$du = e^xdx$，因此$dx = \dfrac{du}{e^x}$

因此$\displaystyle \int \dfrac{1}{1+e^{2x}}dx = \int \dfrac{1}{u(1+u^2)}du$

令$u = \tan t$，則$du = \sec^2 dt$，$t = \arctan(u)$

因此$\displaystyle \int \dfrac{1}{u(1+u^2)}du = \int \dfrac{\sec^2 t}{\tan t(1+\tan^2t)}dt = \int \dfrac{1}{\tan t}dt = \int \dfrac{\cos t}{\sin t}dt$

令$k = \sin t$，則$dk = \cos t dt$，因此$dt = \dfrac{dk}{\cos t}$

因此$\displaystyle \int \dfrac{\cos t}{\sin t}dt = \int \dfrac{\cos t}{k}\dfrac{dk}{\cos t} = \ln(|k|)$

還原$k$，得到$\displaystyle \int \dfrac{\cos t}{\sin t}dt = \ln(|\sin t|)$

還原$t$，得到$\displaystyle \int \dfrac{1}{u(1+u^2)}du = \ln(|\sin(\arctan(u))|) = \ln(|\dfrac{u}{\sqrt{1+u^2}}|)$

還原$u$，得到$\displaystyle \int \dfrac{1}{1+e^{2x}}dx = \ln(|\dfrac{e^x}{\sqrt{1+e^{2x}}}|)$

因此$\displaystyle \int \dfrac{1}{1+e^{2x}}dx = \ln(|\dfrac{e^x}{\sqrt{1+e^{2x}}}|) + C$



### Answer

$\displaystyle \int \dfrac{1}{1+e^{2x}}dx = \ln(|\dfrac{e^x}{\sqrt{1+e^{2x}}}|) + C$



## Problem 38

### Statement

$\displaystyle \int \dfrac{1}{1-2x^2+x^4}dx$



### Solution

$\displaystyle \int \dfrac{1}{1-2x^2+x^4}dx = \int \dfrac{1}{x^4-2x^2+1}dx = \int \dfrac{1}{(x^2-1)^2}dx$

令$x = \sec u$，則$dx = \tan u \sec u du$，$u = \sec^{-1}(x)$

$\displaystyle \int \dfrac{1}{(x^2-1)^2}dx = \int \dfrac{\tan u\sec u}{(\sec^2u-1)^2}du$

$\displaystyle  = \int \dfrac{\sec u}{\tan^3 u}du = \int \dfrac{\cos^2 u}{\sin ^3u}du = \int \dfrac{1-\sin^2u}{\sin^3u}du = \int \dfrac{1}{\sin^3u}du - \int \dfrac{1}{\sin u}du = \int \csc^3(u)du - \int \csc(u)du$



計算$\displaystyle \int \csc^3(u)du$

$\displaystyle \int \csc^3(u)du = \int \csc^2(u)\csc(u)du$

令$t = \csc u$，$dv = \csc^2(u)du$

因此$dt = -\csc u \cot udu$，$v = -\cot u$

因此$\displaystyle \int \csc^3(u)du = -\csc u \cot u - \int \csc u \cot^2du \\ \displaystyle = -\csc u \cot u - \int \csc u (\csc^2u-1)du \\\displaystyle = -\csc u \cot u - \int \csc^3u + \int \csc u du$

已知$\displaystyle \int \csc u = -\ln(|\csc(u)+\cot(u)|)$

因此$\displaystyle \int \csc^3(u)du = -\csc u \cot u - \int \csc^3u - \ln(|\csc(u)+\cot(u)|) \\\Rightarrow \displaystyle 2\int \csc^3(u)du = -\csc u \cot u - \ln(|\csc(u)+\cot(u)|)\\\Rightarrow \displaystyle \int \csc^3(u)du = \dfrac{-\csc u \cot u - \ln(|\csc(u)+\cot(u)|)}{2}$



所以$\displaystyle \int \csc^3(u)du - \int \csc(u)du = \dfrac{-\csc u \cot u - \ln(|\csc(u)+\cot(u)|)}{2} - (-\ln(|\csc(u)+\cot(u)|)) \\\displaystyle = \dfrac{-\csc u \cot u + \ln(|\csc(u)+\cot(u)|)}{2}$ 

還原$u$，得到$\displaystyle \int \dfrac{1}{1-2x^2+x^4}dx = \dfrac{-\csc u \cot u + \ln(|\csc(u)+\cot(u)|)}{2}$

$= -\dfrac{x}{2x^2-2} + \dfrac{1}{2} \ln(|\dfrac{x+1}{\sqrt{x^2-1}}|) + C$



### Answer

$-\dfrac{x}{2x^2-2} + \dfrac{1}{2} \ln(|\dfrac{x+1}{\sqrt{x^2-1}}|) + C$



