---
title: Square Identities
layout: page
---
These identities say that the product of $2$ numbers, each of which is a sum of $2^n$ squares, is itself a sum of $2^n$ squares.

But, this is not limited to only 'numbers', and this has many applications :)

Here are formulas of square identities:

<h3 style="color: rgb(255, 0, 0);">Brahmagupta–Fibonacci identity / Diophantus identity</h3>

\begin{equation}
    (x_{1}^{2}+x_{2}^{2})(y_{1}^{2}+y_{2}^{2})=z_{1}^{2}+z_{2}^{2}
\end{equation}

Where,
<div>
\begin{equation}
\begin{aligned}
    z_{1}&=(x_{1}y_{1}-x_{2}y_{2})\\
    z_{2}&=(x_{1}y_{2}+x_{2}y_{1})
\end{aligned}
\quad\text{or}\quad
\begin{aligned}
    z_{1}&=(x_{1}y_{1}+x_{2}y_{2})\\
    z_{2}&=(x_{1}y_{2}-x_{2}y_{1})
\end{aligned}
\end{equation}
</div>

<h3 style="color: rgb(3, 159, 190);">Euler's four–square identity</h3>
\begin{equation}
    (x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2})(y_{1}^{2}+y_{2}^{2}+y_{3}^{2}+y_{4}^{2})=z_{1}^{2}+z_{2}^{2}+z_{3}^{2}+z_{4}^{2}
\end{equation}
Where,
<div>
\begin{aligned}
    z_{1}&=({\color[RGB]{255, 0, 0}x_{1}y_{1}-x_{2}y_{2}}-x_{3}y_{3}-x_{4}y_{4})\\
    z_{2}&=({\color[RGB]{255, 0, 0}x_{1}y_{2}+x_{2}y_{1}}+x_{3}y_{4}-x_{4}y_{3})\\
    z_{3}&=(x_{1}y_{3}-x_{2}y_{4}+x_{3}y_{1}+x_{4}y_{2})\\
    z_{4}&=(x_{1}y_{4}+x_{2}y_{3}-x_{3}y_{2}+x_{4}y_{1})
\end{aligned}
</div>
   
<h3 style="color: rgb(207, 21, 120);">Degen's eight–square identity</h3>
<div>
\begin{equation}
    (x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}+x_{5}^{2}+x_{6}^{2}+x_{7}^{2}+x_{8}^{2})(y_{1}^{2}+y_{2}^{2}+y_{3}^{2}+y_{4}^{2}+y_{5}^{2}+y_{6}^{2}+y_{7}^{2}+y_{8}^{2})=z_{1}^{2}+z_{2}^{2}+z_{3}^{2}+z_{4}^{2}+z_{5}^{2}+z_{6}^{2}+z_{7}^{2}+z_{8}^{2}
\end{equation}    
</div>
Where,

<div>
\begin{aligned}
    z_{1}&=({\color[RGB]{3, 159, 190}{\color[RGB]{255, 0, 0}x_{1}y_{1}-x_{2}y_{2}}-x_{3}y_{3}-x_{4}y_{4}}-x_{5}y_{5}-x_{6}y_{6}-x_{7}y_{7}-x_{8}y_{8})\\
    z_{2}&=({\color[RGB]{3, 159, 190}{\color[RGB]{255, 0, 0}x_{1}y_{2}+x_{2}y_{1}}+x_{3}y_{4}-x_{4}y_{3}}+x_{5}y_{6}-x_{6}y_{5}-x_{7}y_{8}+x_{8}y_{7})\\
    z_{3}&=({\color[RGB]{3, 159, 190}x_{1}y_{3}-x_{2}y_{4}+x_{3}y_{1}+x_{4}y_{2}}+x_{5}y_{7}+x_{6}y_{8}-x_{7}y_{5}-x_{8}y_{6})\\
    z_{4}&=({\color[RGB]{3, 159, 190}x_{1}y_{4}+x_{2}y_{3}-x_{3}y_{2}+x_{4}y_{1}}+x_{5}y_{8}-x_{6}y_{7}+x_{7}y_{6}-x_{8}y_{5})\\
    z_{5}&=(x_{1}y_{5}-x_{2}y_{6}-x_{3}y_{7}-x_{4}y_{8}+x_{5}y_{1}+x_{6}y_{2}+x_{7}y_{3}+x_{8}y_{4})\\
    z_{6}&=(x_{1}y_{6}+x_{2}y_{5}-x_{3}y_{8}+x_{4}y_{7}-x_{5}y_{2}+x_{6}y_{1}-x_{7}y_{4}+x_{8}y_{3})\\
    z_{7}&=(x_{1}y_{7}+x_{2}y_{8}+x_{3}y_{5}-x_{4}y_{6}-x_{5}y_{3}+x_{6}y_{4}+x_{7}y_{1}-x_{8}y_{2})\\
    z_{8}&=(x_{1}y_{8}-x_{2}y_{7}+x_{3}y_{6}+x_{4}y_{5}-x_{5}y_{4}-x_{6}y_{3}+x_{7}y_{2}+x_{8}y_{1})
\end{aligned}    
</div>

### Pfister's sixteen–square identity
<div>
\begin{equation}
    (x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+\cdots +x_{16}^{2})\,(y_{1}^{2}+y_{2}^{2}+y_{3}^{2}+\cdots +y_{16}^{2})=z_{1}^{2}+z_{2}^{2}+z_{3}^{2}+\cdots +z_{16}^{2}
\end{equation}    
</div>
Where,
<div>
\begin{aligned}
    z_{1}&={\color[RGB]{207, 21, 120}{\color[RGB]{3, 159, 190}{\color[RGB]{255, 0, 0}x_{1}y_{1}-x_{2}y_{2}}-x_{3}y_{3}-x_{4}y_{4}}-x_{5}y_{5}-x_{6}y_{6}-x_{7}y_{7}-x_{8}y_{8}}+u_{1}y_{9}-u_{2}y_{10}-u_{3}y_{11}-u_{4}y_{12}-u_{5}y_{13}-u_{6}y_{14}-u_{7}y_{15}-u_{8}y_{16}\\
    z_{2}&={\color[RGB]{207, 21, 120}{\color[RGB]{3, 159, 190}{\color[RGB]{255, 0, 0}x_{2}y_{1}+x_{1}y_{2}}+x_{4}y_{3}-x_{3}y_{4}}+x_{6}y_{5}-x_{5}y_{6}-x_{8}y_{7}+x_{7}y_{8}}+u_{2}y_{9}+u_{1}y_{10}+u_{4}y_{11}-u_{3}y_{12}+u_{6}y_{13}-u_{5}y_{14}-u_{8}y_{15}+u_{7}y_{16}\\
    z_{3}&={\color[RGB]{207, 21, 120}{\color[RGB]{3, 159, 190}x_{3}y_{1}-x_{4}y_{2}+x_{1}y_{3}+x_{2}y_{4}}+x_{7}y_{5}+x_{8}y_{6}-x_{5}y_{7}-x_{6}y_{8}}+u_{3}y_{9}-u_{4}y_{10}+u_{1}y_{11}+u_{2}y_{12}+u_{7}y_{13}+u_{8}y_{14}-u_{5}y_{15}-u_{6}y_{16}\\
    z_{4}&={\color[RGB]{207, 21, 120}{\color[RGB]{3, 159, 190}x_{4}y_{1}+x_{3}y_{2}-x_{2}y_{3}+x_{1}y_{4}}+x_{8}y_{5}-x_{7}y_{6}+x_{6}y_{7}-x_{5}y_{8}}+u_{4}y_{9}+u_{3}y_{10}-u_{2}y_{11}+u_{1}y_{12}+u_{8}y_{13}-u_{7}y_{14}+u_{6}y_{15}-u_{5}y_{16}\\
    z_{5}&={\color[RGB]{207, 21, 120}x_{5}y_{1}-x_{6}y_{2}-x_{7}y_{3}-x_{8}y_{4}+x_{1}y_{5}+x_{2}y_{6}+x_{3}y_{7}+x_{4}y_{8}}+u_{5}y_{9}-u_{6}y_{10}-u_{7}y_{11}-u_{8}y_{12}+u_{1}y_{13}+u_{2}y_{14}+u_{3}y_{15}+u_{4}y_{16}\\
    z_{6}&={\color[RGB]{207, 21, 120}x_{6}y_{1}+x_{5}y_{2}-x_{8}y_{3}+x_{7}y_{4}-x_{2}y_{5}+x_{1}y_{6}-x_{4}y_{7}+x_{3}y_{8}}+u_{6}y_{9}+u_{5}y_{10}-u_{8}y_{11}+u_{7}y_{12}-u_{2}y_{13}+u_{1}y_{14}-u_{4}y_{15}+u_{3}y_{16}\\
    z_{7}&={\color[RGB]{207, 21, 120}x_{7}y_{1}+x_{8}y_{2}+x_{5}y_{3}-x_{6}y_{4}-x_{3}y_{5}+x_{4}y_{6}+x_{1}y_{7}-x_{2}y_{8}}+u_{7}y_{9}+u_{8}y_{10}+u_{5}y_{11}-u_{6}y_{12}-u_{3}y_{13}+u_{4}y_{14}+u_{1}y_{15}-u_{2}y_{16}\\
    z_{8}&={\color[RGB]{207, 21, 120}x_{8}y_{1}-x_{7}y_{2}+x_{6}y_{3}+x_{5}y_{4}-x_{4}y_{5}-x_{3}y_{6}+x_{2}y_{7}+x_{1}y_{8}}+u_{8}y_{9}-u_{7}y_{10}+u_{6}y_{11}+u_{5}y_{12}-u_{4}y_{13}-u_{3}y_{14}+u_{2}y_{15}+u_{1}y_{16}\\
    z_{9}&=x_{9}y_{1}-x_{10}y_{2}-x_{11}y_{3}-x_{12}y_{4}-x_{13}y_{5}-x_{14}y_{6}-x_{15}y_{7}-x_{16}y_{8}+x_{1}y_{9}-x_{2}y_{10}-x_{3}y_{11}-x_{4}y_{12}-x_{5}y_{13}-x_{6}y_{14}-x_{7}y_{15}-x_{8}y_{16}\\
    z_{10}&=x_{10}y_{1}+x_{9}y_{2}+x_{12}y_{3}-x_{11}y_{4}+x_{14}y_{5}-x_{13}y_{6}-x_{16}y_{7}+x_{15}y_{8}+x_{2}y_{9}+x_{1}y_{10}+x_{4}y_{11}-x_{3}y_{12}+x_{6}y_{13}-x_{5}y_{14}-x_{8}y_{15}+x_{7}y_{16}\\
    z_{11}&=x_{11}y_{1}-x_{12}y_{2}+x_{9}y_{3}+x_{10}y_{4}+x_{15}y_{5}+x_{16}y_{6}-x_{13}y_{7}-x_{14}y_{8}+x_{3}y_{9}-x_{4}y_{10}+x_{1}y_{11}+x_{2}y_{12}+x_{7}y_{13}+x_{8}y_{14}-x_{5}y_{15}-x_{6}y_{16}\\
    z_{12}&=x_{12}y_{1}+x_{11}y_{2}-x_{10}y_{3}+x_{9}y_{4}+x_{16}y_{5}-x_{15}y_{6}+x_{14}y_{7}-x_{13}y_{8}+x_{4}y_{9}+x_{3}y_{10}-x_{2}y_{11}+x_{1}y_{12}+x_{8}y_{13}-x_{7}y_{14}+x_{6}y_{15}-x_{5}y_{16}\\
    z_{13}&=x_{13}y_{1}-x_{14}y_{2}-x_{15}y_{3}-x_{16}y_{4}+x_{9}y_{5}+x_{10}y_{6}+x_{11}y_{7}+x_{12}y_{8}+x_{5}y_{9}-x_{6}y_{10}-x_{7}y_{11}-x_{8}y_{12}+x_{1}y_{13}+x_{2}y_{14}+x_{3}y_{15}+x_{4}y_{16}\\
    z_{14}&=x_{14}y_{1}+x_{13}y_{2}-x_{16}y_{3}+x_{15}y_{4}-x_{10}y_{5}+x_{9}y_{6}-x_{12}y_{7}+x_{11}y_{8}+x_{6}y_{9}+x_{5}y_{10}-x_{8}y_{11}+x_{7}y_{12}-x_{2}y_{13}+x_{1}y_{14}-x_{4}y_{15}+x_{3}y_{16}\\
    z_{15}&=x_{15}y_{1}+x_{16}y_{2}+x_{13}y_{3}-x_{14}y_{4}-x_{11}y_{5}+x_{12}y_{6}+x_{9}y_{7}-x_{10}y_{8}+x_{7}y_{9}+x_{8}y_{10}+x_{5}y_{11}-x_{6}y_{12}-x_{3}y_{13}+x_{4}y_{14}+x_{1}y_{15}-x_{2}y_{16}\\
    z_{16}&=x_{16}y_{1}-x_{15}y_{2}+x_{14}y_{3}+x_{13}y_{4}-x_{12}y_{5}-x_{11}y_{6}+x_{10}y_{7}+x_{9}y_{8}+x_{8}y_{9}-x_{7}y_{10}+x_{6}y_{11}+x_{5}y_{12}-x_{4}y_{13}-x_{3}y_{14}+x_{2}y_{15}+x_{1}y_{16}
\end{aligned}    
</div>

The PDF for same can be found [here](https://paramrathour.github.io/Random-Stuff/Square%20Identities/Square%20Identities.pdf)

### References
+ [Sums of n squares](https://sites.google.com/site/tpiezas/005b)
+ [Brahmagupta–Fibonacci identity](https://en.wikipedia.org/wiki/Brahmagupta%E2%80%93Fibonacci_identity)
+ [Euler's four–square identity](https://en.wikipedia.org/wiki/Euler%27s_four-square_identity)
+ [Degen's eight–square identity](https://en.wikipedia.org/wiki/Degen%27s_eight-square_identity)
+ [Pfister's sixteen–square identity](https://en.wikipedia.org/wiki/Pfister%27s_sixteen-square_identity)