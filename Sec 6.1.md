# 洪輝霖微積分Practice Ch 6.1

###### tags: `微積分題目紀錄`



## Exercise 1

### Statement

$\displaystyle \int \dfrac{2x+1}{\sqrt{1-x^2}} dx$



### Solution

$\displaystyle \int \dfrac{2x+1}{\sqrt{1-x^2}} dx = \int\dfrac{2x}{\sqrt{1-x^2}}dx + \int\dfrac{1}{\sqrt{1-x^2}}dx$

計算$\displaystyle \int\dfrac{2x}{\sqrt{1-x^2}} dx$，利用代換積分法

令$u=1-x^2$，則$du = -2xdx$，$dx = \dfrac{du}{-2x}$

$\displaystyle \int\dfrac{2x}{\sqrt{1-x^2}} dx = \int\dfrac{2x}{\sqrt{u}} \dfrac{du}{-2x} = -\int u^\frac{-1}{2} du = -2\sqrt{u} = -2\sqrt{1-x^2}$

計算$\int\dfrac{1}{\sqrt{1-x^2}}dx$，可得$\int\dfrac{1}{\sqrt{1-x^2}}dx = \arcsin x$

故$\displaystyle \int \dfrac{2x+1}{\sqrt{1-x^2}} dx = -2\sqrt{1-x^2} + \arcsin x + C$



### Answer

$\displaystyle \int \dfrac{2x+1}{\sqrt{1-x^2}} dx = -2\sqrt{1-x^2} + \arcsin x + C$



## Exercise 2

### Statement

$\displaystyle \int \dfrac{3-2x}{x^2+4} dx$



### Solution

$\displaystyle \int \dfrac{3-2x}{x^2+4} dx = \int\dfrac{3}{x^2+4} dx + \int\dfrac{-2x}{x^2+4} dx$

計算$\displaystyle \int \dfrac{3}{x^2+4} dx$，$\displaystyle \int \dfrac{3}{x^2+4} dx = 3\int \dfrac{1}{x^2+4} dx$

利用代換積分法，令$x = 2u$，則$dx = 2du$，$u = \dfrac{x}{2}$

$\displaystyle 3\int \dfrac{1}{x^2+4} dx = 6\int \dfrac{1}{4u^2 + 4} du = \dfrac{3}{2}\int \dfrac{1}{u^2+1} du$

已知$\displaystyle \int \dfrac{1}{x^2+1} dx = \tan^{-1}x$

因此$\displaystyle \dfrac{3}{2} \int \dfrac{1}{u^2+1} du = \dfrac{3}{2} \tan^{-1}(u) = \dfrac{3}{2}\tan^{-1}(\dfrac{x}{2})$

計算$\displaystyle \int\dfrac{-2x}{x^2+4} dx$，利用代換積分法，令$u = x^2+4$，所以$du = 2x dx$，$dx = \dfrac{du}{2x}$

$\displaystyle \int\dfrac{-2x}{x^2+4} dx = \int \dfrac{-2x}{u} \dfrac{du}{2x} = -\int\dfrac{1}{u}du = -\ln(|u|) = -\ln(|x^2+4|)$

所以$\displaystyle \int \dfrac{3-2x}{x^2+4} dx = \dfrac{3}{2}\tan^{-1}(\dfrac{x}{2}) - \ln(|x^2+4|) + C$



### Answer

$\displaystyle \int \dfrac{3-2x}{x^2+4} dx = \dfrac{3}{2}\tan^{-1}(\dfrac{x}{2}) - \ln(|x^2+4|) + C$



## Exercise 3

### Statement

$\displaystyle \int \dfrac{6x-3}{\sqrt{9-x^2}} dx$



### Solution

$\displaystyle \int \dfrac{6x-3}{\sqrt{9-x^2}} dx = \int \dfrac{6x}{\sqrt{9-x^2}} dx - \int\dfrac{3}{\sqrt{9-x^2}} dx$

計算$\displaystyle \int \dfrac{6x}{\sqrt{9-x^2}} dx$，$\displaystyle \int \dfrac{6x}{\sqrt{9-x^2}} dx = 6\int \dfrac{x}{\sqrt{9-x^2}} dx$

利用代換積分法，令$u = 9-x^2$，則$du = -2x dx$，$dx = -\dfrac{du}{2x}$

$\displaystyle 6\int \dfrac{x}{\sqrt{9-x^2}} dx = 6\int \dfrac{x}{\sqrt{u}}\dfrac{-du}{2x} = -3\int\dfrac{1}{\sqrt{u}} du = -6\sqrt{u} = -6\sqrt{9-x^2}$

計算$\displaystyle \int \dfrac{3}{\sqrt{9-x^2}} dx$，$\displaystyle \int \dfrac{3}{\sqrt{9-x^2}} dx = 3\int\dfrac{1}{\sqrt{9-x^2}} dx$

利用代換積分法，令$x = 3u$，則$dx = 3du$，$u = \dfrac{x}{3}$

$\displaystyle 3\int \dfrac{1}{\sqrt{9-x^2}} dx = 3\int \dfrac{3}{\sqrt{9-9u^2}} du = 3\int \dfrac{3}{3\sqrt{1-u^2}} du = 3\int \dfrac{1}{\sqrt{1-u^2}} du = 3\sin^{-1}(u) = 3\sin^{-1}(\dfrac{x}{3})$

因此$\displaystyle \int \dfrac{6x-3}{\sqrt{9-x^2}} dx = -6\sqrt{9-x^2} - 3\sin^{-1}(\dfrac{x}{3})$



### Answer

$\displaystyle \int \dfrac{6x-3}{\sqrt{9-x^2}} dx = -6\sqrt{9-x^2} - 3\sin^{-1}(\dfrac{x}{3})$



## Exercise 4

### Statement

$\displaystyle \int \dfrac{2x+1}{x^2+2x+2} dx$



### Solution

$\displaystyle \int \dfrac{2x+1}{x^2+2x+2} dx = \int \dfrac{2x+2-1}{x^2+2x+2} dx = \int \dfrac{2x+2}{x^2+2x+2} dx - \int \dfrac{1}{x^2+2x+2} dx$

計算$\displaystyle \int \dfrac{2x+2}{x^2+2x+2} dx$，利用代換積分法，令$u = x^2+2x+2$，則$du = (2x+2)dx$，$dx = \dfrac{du}{2x+2}$

$\displaystyle \int \dfrac{2x+2}{x^2+2x+2} dx = \int \dfrac{2x+2}{u} \dfrac{du}{2x+2} = \int\dfrac{1}{u}du = \ln(|u|) = \ln(|x^2+2x+2|)$

計算$\displaystyle \int \dfrac{1}{x^2+2x+2} dx$，$\displaystyle \int \dfrac{1}{x^2+2x+2} dx = \displaystyle \int \dfrac{1}{x^2+2x+1+1} dx = \displaystyle \int \dfrac{1}{(x+1)^2+1} dx$

令$u = x+1$，則$du = dx$

$\displaystyle \int \dfrac{1}{(x+1)^2+1} dx = \displaystyle \int \dfrac{1}{u^2+1} du = \tan^{-1}(u) = \tan^{-1}(x+1)$

因此$\displaystyle \int \dfrac{2x+1}{x^2+2x+2} dx = \ln(|x^2+2x+2|) - \tan^{-1}(x+1) + C$



### Answer

$\displaystyle \int \dfrac{2x+1}{x^2+2x+2} dx = \ln(|x^2+2x+2|) - \tan^{-1}(x+1) + C$



## Exercise 12

### Statement

$\displaystyle \int^1_0 \ln(1+\sqrt{x}) dx$



### Solution

Let $u = 1+\sqrt{x}$, $du = \dfrac{1}{2\sqrt{x}} dx$, $dx = 2\sqrt{x} du$, $UpperBound= 1+\sqrt{1} = 2$, $LowerBound = 1+0 = 1$

$\int^1_0 \ln(1+\sqrt{x}) dx = \int^1_0 \ln(x) 2\sqrt{x} du = \int^1_0 2(u-1)\ln(u) du = \int^1_0 2u\ln(u)du-\int^1_0 2\ln(u)du$



Calculate $\int^1_0 2u\ln(u) du$, Find $\int 2u\ln(u) du $

Let $t = \ln(u), dv = 2udu$, $dt = \dfrac{1}{u}du, v = u^2$

$\int t dv = tv - \int v dt = u^2\ln(u) - \int vdt = u^2 \ln(u) - \int u^2 \dfrac{1}{u}du = u^2\ln(u) - \int u du = u^2\ln(u) - \dfrac{1}{2}u^2$

$\int 2u\ln(u)du = u^2\ln(u) - \dfrac{1}{2}u^2$

$\int^1_0 2u\ln(u)du = u^2\ln(u)-\dfrac{1}{2}u^2|^2_1 = 4\ln(2)-2-(\ln(1)-\dfrac{1}{{2}}) = 4\ln(2)-\dfrac{3}{2}$



Calculate $\int^1_0 2\ln(u) du$, Find $\int 2\ln(u)du$

Let $t = 2\ln(u)$, $dv = du$, $dt = \dfrac{2}{u}du, v = u$

$\int tdv = tv - \int vdt = 2u\ln(u)-\int u \dfrac{2}{u}du = 2u\ln(u) - \int2du = 2u\ln(u) - 2u$

$\int 2\ln(u)du = 2u\ln(u)-2u$

$\int^1_0 2\ln(u)du = 2u\ln(u)-2u|^2_1 = (4\ln(2)-4)-(2\ln(1)-2) = (4\ln(2)-2)$



$\int^1_0 2u\ln(u)du-\int^1_0 2\ln(u)du = 4\ln(2) - \dfrac{3}{2} - (4\ln(2)-2) = \dfrac{1}{2}$



### Answer

$\displaystyle \int^1_0 \ln(1+\sqrt{x}) dx = \dfrac{1}{2}$



## Exercise 16

### Statement

$\int \ln(2x+3) dx$



### Solution

令$u = 2x+3$，則$du = 2dx, dx = \dfrac{du}{2}$

$\int \ln(u) \dfrac{du}{2} = \dfrac{1}{2}\int\ln(u)du$

計算$\int \ln(u) du$，令$t = \ln(u), dv = du$，則$dt = \dfrac{1}{u}du, v = u$

利用分部積分計算$\int \ln(u)du$，$\int t dv = tv - \int v dt$

$\int \ln(u)du = u\ln(u) - \int u \dfrac{1}{u} du = u\ln(u) - \int 1du = u\ln(u)- u$

則$\dfrac{1}{2}\int \ln(u)du = \dfrac{1}{2}u\ln(u) - \dfrac{1}{2}u = (2x+3)\ln(2x+3) - x - \dfrac{3}{2}$

因此$\int \ln(2x+3) dx = (2x+3)\ln(2x+3)-x+C$

由於$C$代表任意實數，因此省略$-\dfrac{3}{2}$



### Answer

$\displaystyle \int \ln(2x+3) dx = (2x+3)\ln(2x+3)-x+C$



## Exercise 28

### Statement

$\int x^5e^{x^2} dx$



### Solution

$\int x^5e^{x^2} = \int x^4\cdot xe^{x^2} dx$

令$u = x^4, dv = xe^{x^2}dx$，則$du = 4x^3 dx, v = \dfrac{e^{x^2}}{2}$

利用分部積分，$\int u dv = uv - \int v du$

$\int x^4 \cdot x^{e^{x^2}} = \dfrac{x^4e^{x^2}}{2} - \int \dfrac{4x^3e^{x^2}}{2} dx = \dfrac{x^4e^{x^2}}{2} - 2\int x^3e^{x^2} dx = \dfrac{x^4e^{x^2}}{2} - 2\int x^2\cdot xe^{x^2}dx$

計算$2\int x^2\cdot xe^{x^2} dx$，令$a = x^2, db = xe^{x^2} dx$，則$da = 2x dx, b = \dfrac{e^{x^2}}{2}$

利用分部積分，$\int adb = ab - \int b da$

$\int x^2\cdot x e^{x^2} dx = \dfrac{x^2e^{x^2}}{2} - \int\dfrac{2xe^{x^2}}{2}dx = \dfrac{x^2e^{x^2}}{2} - \int xe^{x^2}dx$

計算$\int xe^{x^2}dx$，令$c = e^{x^2}$，則$dc = 2xe^{x^2}dx, dx = \dfrac{dc}{2xe^{x^2}}$

$\int xe^{x^2}dx = \int xe^{x^{2}} \dfrac{dc}{2xe^{x^2}} = \int \dfrac{1}{2}dc = \dfrac{c}{2} = \dfrac{e^{x^2}}{2}$

因此$2\int x^2\cdot x e^{x^2} dx = 2(\dfrac{x^2e^{x^2}}{2} - \dfrac{e^{x^2}}{2}) = x^2e^{x^2}-e^{x^2}$

因此$\dfrac{x^4e^{x^2}}{2} - 2\int x^2\cdot xe^{x^2}dx = \dfrac{x^4e^{x^2}}{2}-x^2e^{x^2}-e^{x^2}$

因此$\int x^5e^{x^2} dx = \dfrac{x^4e^{x^2}}{2}-x^2e^{x^2}-e^{x^2} + C$



### Answer

$\displaystyle \int x^5e^{x^2} dx = \dfrac{x^4e^{x^2}}{2}-x^2e^{x^2}-e^{x^2} + C$