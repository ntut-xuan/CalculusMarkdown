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



## Exercise 19

### Statement

$\int \dfrac{1}{x^2\sqrt{4-x^2}} dx$



### Solution

令$x = 2\sin u$，$u = \sin^{-1}(\dfrac{x}{2})$，則$dx = 2\cos u du$

因此$\int \dfrac{1}{x^2\sqrt{4-x^2}} dx = \int \dfrac{2\cos u}{4\sin^2u \sqrt{4-4\sin^2u}} du = \int \dfrac{2\cos u}{8\sin^2u\cos u}du = \dfrac{1}{4}\int\dfrac{1}{\sin^2u} du$

計算$\int \dfrac{1}{\sin^2 u} du = \int \dfrac{\sec^2 u}{\tan^2 u}du$，

令$t = \tan u$，則 $dt = \sec^2u\ du,\ du = \dfrac{1}{\sec^2 u}dt$

$\int \dfrac{\sec^2 u}{\tan^2 u} du = \int \dfrac{1}{t^2} dt = -t^{-1}+C = -\cot u + C$

又$u = \sin^{-1}(\dfrac{x}{2})$，則$-\cot(\sin^{-1}(\dfrac{x}{2})) du = -\dfrac{\sqrt{1-(\dfrac{x}{2})^2}}{\dfrac{x}{2}} = -\dfrac{\sqrt{4-x^2}}{x}$

因此$\int \dfrac{1}{x^2\sqrt{4-x^2}} dx = \dfrac{1}{4}\int \dfrac{1}{\sin^2 u} du = \dfrac{-\sqrt{4-x^2}}{4x} + C$



### Answer

$\int \dfrac{1}{x^2\sqrt{4-x^2}} dx = \dfrac{-\sqrt{4-x^2}}{4x} + C$

