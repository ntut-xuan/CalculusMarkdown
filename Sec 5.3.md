# 洪輝霖微積分Practice Ch 5.3

###### tags: `微積分題目紀錄`



## Exercise 16

### Statement

$\displaystyle \int^3_0 e^{2s}(e^{2s}+1)^6 ds$



### Solution

令$u = e^{2s}+1$，則$du = 2e^{2s} ds$，因此$ds= \dfrac{du}{2e^{2s}}$

$\displaystyle \int^3_0 e^{2s}(e^{2s}+1)^6 ds = \int^{e^6+1}_2 \dfrac{e^{2s}u^6}{2e^{2s}} du = \dfrac{1}{2}\int^{e^6+1}_2u^6 du = \dfrac{u^{7}}{14}|^{e^6+1}_2 = \dfrac{(e^6+1)^7-2^7}{14}$



### Answer

$\displaystyle \int^3_0 e^{2s}(e^{2s}+1)^6 ds = \dfrac{(e^6+1)^7-2^7}{14}$



## Exercise 17

### Statement

$\displaystyle \int^{\frac{\pi}{8}}_0 \tan^2(2x) dx$



### Solution

令$u = 2x$，則$du = 2dx$，$dx = \dfrac{du}{2}$

$\displaystyle \int^{\frac{\pi}{8}}_0 \tan^2(2x) dx = \dfrac{1}{2}\int^{\frac{\pi}{4}}_0 \tan^2(u) du = \dfrac{1}{2}\int^{\frac{\pi}{4}}_0 \sec^2(u)-1 du$