> 已知 $\forall x > 0, a(e^{ax} + 1) \ge 2\left(x + \frac{1}{x}\right)\ln x$，求 $a$ 取值范围。

$\because a(e^{ax} + 1) \ge 2\left(x + \frac{1}{x}\right)\ln x$

$\therefore ax(e^{ax} + 1) \ge 2x\left(x + \frac{1}{x}\right)\ln x$

$\therefore axe^{ax} + ax \ge x^2\ln x^2 + \ln x^2$

$\therefore axe^{ax} + ax \ge e^{\ln x^2}\ln x^2 + \ln x^2$

设 $f(x) = xe^x + x\ (x \in \mathrm{R})$，易知 $f(x)$ 单调递增

$\therefore f(ax) \ge f(\ln x^2)$

$\therefore ax \ge \ln x^2$

设 $g(x) = \frac{\ln x^2}{x}\ (x > 0)$

$\therefore$ 易得 $a \ge g(x)_{\max} = g(e) = \frac{2}{e}$



> 已知 $ae^x + \ln \frac{a}{x + 2} - 2 > 0\ (a > 0)$ 恒成立，求正实数 $a$ 取值范围。

$\because ae^x + \ln \frac{a}{x + 2} - 2 > 0$

$\therefore ae^x - 2 > \ln \frac{x + 2}{a} = \ln (x + 2) - \ln a$

$\therefore e^{x + \ln a} + x + \ln a > (x + 2) + \ln (x + 2) = e^{\ln (x + 2)} + \ln (x + 2)$

设 $f(x) = e^x + x\ (x > 0)$

$\therefore f(x + \ln a) > f(ln (x + 2)) \Rightarrow x + \ln a > ln (x + 2)$

设 $g(x) = x - \ln (x + 2) + \ln a\ (x > -2)$

$\therefore$ 易得 $g(x)_{\min} = g(-1) = -1 + \ln a > 0$

$\therefore a \in (e, +\infty)$



> 已知 $x^3 = e^{3 - x^3},\ln y = \frac{e^5}{y} + 2$，求 $x^3y$。

$\because \ln y = \frac{e^5}{y} + 2$

$\therefore \ln y - 2 = \frac{e^5}{y} = e^{5 - \ln y} = e^{3 - (\ln y - 2)}$

设 $f(x) = x - e^{3 - x}\ (x \in \mathrm{R})$

$\therefore x^3,\ln y - 2$ 为 $f(x)$ 的零点

$\because f(x)$ 显然单调递增

$\therefore f(x)$ 仅一个零点

$\therefore x^3 = \ln y - 2 = \left(\frac{e^5}{y} + 2\right) - 2 = \frac{e^5}{y}$

$\therefore x^3y = e^5$



> 已知 $x(e^{2x} - a) \ge 1 + x + \ln x$，求 $a$ 的取值范围

$\because x(e^{2x} - a) \ge 1 + x + \ln x$

$\therefore xe^{2x} \ge 1 + (a + 1)x + \ln x$

令 $t = xe^{2x}\ (t > 1)$

$\therefore t \ge 1 + (a + 1)x + \ln x$

$\because \ln t = \ln x + 2x$

$\therefore t - \ln t \ge (a - 1) x + 1$

$\because t - \ln t \ge 1$，当且仅当 $t = 1$ 时取等

当 $a \le 1$ 时，显然符合条件

当 $a > 1$ 时，令 $t = 1$

$\therefore t - \ln t = 1 < (a - 1)x + 1$

$\exist t_0, x_0$ 使 $t_0 - \ln t_0 < (a - 1)x_0 + 1$，不符合条件

综上，$a \in (-\infty, 1]$



> 已知函数 $f(x) = 3^x - 3^{-x}\ (x \in \mathrm{R})$，$f(1 - 2\log_3 t) + f(3\log_3 t - 1) \ge \log_{\frac{1}{3}} t$，求 $t$ 的取值范围。

$\because \log_{\frac{1}{3}} t = -\log_3 t = (2\log_3 t - 1) - (3\log_3 t - 1)$

$\therefore f(1 - 2\log_3 t) + f(3\log_3 t - 1) \ge (2\log_3 t - 1) - (3\log_3 t - 1)$

$\therefore f(1 - 2\log_3 t) - (2\log_3 t - 1) \ge -f(3\log_3 t - 1) - (3\log_3 t - 1)$

易知 $f(x)$ 为奇函数，且单调递增

$\therefore f(2\log_3 t - 1) + (2\log_3 t - 1) \le f(3\log_3 t - 1) + (3\log_3 t - 1)$

$\therefore 2\log_3 t - 1 \le 3\log_3 t - 1$

$\therefore \log_3 t \ge 0$

$\therefore t \in [1, +\infty)$



> 已知 $a,b \in (0, 2)$，且满足 $a^2 - b^2 - 4 = \frac{4}{2^b} - 2^a - 4b$，求 $a + b$。

$\because a^2 - b^2 - 4 = \frac{4}{2^b} - 2^a - 4b$

$\therefore a^2 + 2^a = \frac{4}{2^b} + b^2 - 4b + 4$

$\therefore a^2 + 2^a = 2^{2 - b} + (2 - b)^2$

设 $f(x) = x^2 + 2^x\ (0 < x < 2)$

$\therefore f(a) = f(2 - b)$

$\because f(x)$ 单调递增

$\therefore a = 2 - b \Rightarrow a + b = 2$