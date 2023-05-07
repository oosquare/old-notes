## 均值不等式链

$$
\frac{2}{\frac{1}{a} + \frac{1}{b}} < \sqrt{ab} < \frac{a - b}{\ln a - \ln b} < \frac{a + b}{2} < \sqrt{\frac{a^2 + b^2}{2}}\ (a, b \in \mathrm{R^*},a \ne b) \\
ab < \left(\frac{a + b}{2}\right)^2 < \frac{a^2 + b^2}{2}\ (a, b \in \mathrm{R},a \ne b) \\
$$

## 柯西不等式

$$
(x_1^2 + x_2^2 + \cdots)(y_1^2 + y_2^2 + \cdots) \ge (x_1y_1 + x_2y_2 + \cdots)^2
$$

当且仅当 $\frac{x_1}{y_1} = \frac{x_2}{y_2} = \cdots$ 时取等。

## 指数函数

$$
e^x = \sum_{k = 0}^{n} \frac{x^k}{k!} + \omicron(x^n) \\
e^x \ge x + 1 \\
e^x \ge \frac{1}{2}x^2 + x + 1\ (x > 0) \\
e^x \le \frac{1}{1 - x}\ (x < 1) \\
$$

## 对数函数

$$
\ln(1 + x) = \sum_{k = 1}^{n} \frac{x^n}{k} + \omicron(x^n) \\
1 - \frac{1}{x} \le \ln x \le x - 1 \\
\ln(1 + x) \ge x - \frac{x^2}{2} \\
\ln(1 + x) \le x - \frac{x^2}{2} + \frac{x^3}{3} \\
$$

$\ln(1 + x) \ge x - \frac{x^2}{2}$ 在 $\left(0, \frac{1}{2}\right)$ 误差较小 $(< 0.03)$，在 $\left(\frac{1}{2}, 1\right)$ 误差略大 $(< 0.2)$，在 $(1, +\infty)$ **误差很大，估算慎用**。

$\ln(1 + x) \le x - \frac{x^2}{2} + \frac{x^3}{3}$ 误差同上。

$$
\frac{1}{x + 1} \le \ln \frac{x + 1}{x} \le \frac{1}{x}
$$

证明：把 $\frac{x + 1}{x}$ 代入 $\ln\frac{1}{x} \ge 1 - x$ 得到左边部分，把 $\frac{1}{x}$ 代入 $\ln(1 + x) \le x$ 得到右边。

$$
-\frac{1}{ex} \le \ln x \le \frac{x}{e}
$$

左右两边分别在 $x = \frac{1}{e}$ 和 $x = e$ 时取等。

$$
\ln x \le \frac{2(x - 1)}{x + 1}\ \left(0 < x \le 1\right) \\
\ln x \ge \frac{2(x - 1)}{x + 1}\ \left(x \ge 1\right) \\
$$

在 $x = 1$ 时取等。

在 $(\frac{1}{e}, 2)$ 上误差很小 $(< 0.02)$，在 $(2, \frac{5}{2})$ 上误差较小 $(< 0.1)$。

$$
2\ln x \ge x - \frac{1}{x}\ \left(0 < x \le 1\right) \\
2\ln x \ge x - \frac{1}{x}\ \left(x \ge 1\right) \\
$$

在 $x = 1$ 时取等。


## 数列裂项

$$
n < \sqrt{n(n + 1)} < \sqrt{(n + 1)^2} = n + 1 \\
\sqrt{n^2 + 2n} < \sqrt{(n^2 + 2n + 1)} = n + 1 \\
\frac{1}{n} < \frac{1}{\sqrt{n(n + 1)}} \\

\frac{1}{n^2} < \frac{1}{n^2 - 1} = \frac{1}{2}\left(\frac{1}{n - 1} - \frac{1}{n + 1}\right) \\
\frac{1}{n^2} = \frac{4}{4n^2} < \frac{4}{4n^2 - 1} = \frac{1}{2}\left(\frac{1}{2n - 1} - \frac{1}{2n + 1}\right) \\
\frac{1}{n^2} < \frac{1}{n(n - 1)} = \frac{1}{n - 1} - \frac{1}{n} \\
\frac{1}{n^2} > \frac{1}{n(n + 1)} = \frac{1}{n} - \frac{1}{n + 1} \\
$$

## 帕德近似

$f(x) = e^x$

| $[m, n]$ |        $0$        |          $1$          |              $2$              |
| :------: | :---------------: | :-------------------: | :---------------------------: |
|   $0$    |        $1$        |        $1 + x$        |   $1 + x + \frac{1}{2}x^2$    |
|   $1$    | $\frac{1}{1 - x}$ | $\frac{2 + x}{2 - x}$ | $\frac{6 + 4x + x^2}{6 - 2x}$ |

$f(x) = \ln (1 + x)$

| $[m, n]$ |        $1$         |            $2$            |
| :------: | :----------------: | :-----------------------: |
|   $0$    |        $x$         |    $x - \frac{x^2}{2}$    |
|   $1$    | $\frac{2x}{2 + x}$ | $\frac{6x + x^2}{6 + 4x}$ |
