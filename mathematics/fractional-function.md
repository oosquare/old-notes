已知分式型函数

$$
f(x) = \frac{ax^2 + bx + c}{dx^2 + ex + f}\ (dx^2 + ex + f \ne 0)
$$

则其导数有如下性质：

$$
\newcommand{\mydet}[4]{\begin{vmatrix} #1 & #2 \\ #3 & #4 \end{vmatrix}}
sgn\left(f'(x)\right) = sgn\left(\mydet{a}{b}{d}{e} x^2 + 2\mydet{a}{c}{d}{f} x + \mydet{b}{c}{e}{f}\right)
$$

$f(x)$ 的连续性由 $dx^2 + ex + f$ 决定，若 $dx^2 + ex + f = 0$ 有 $n$ 个根，则 $f(x)$ 就由 $n + 1$ 段组成。

段与段的分界处均趋近于 $+\infty$ 或 $-\infty$。