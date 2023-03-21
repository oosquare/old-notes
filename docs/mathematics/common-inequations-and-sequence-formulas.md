## 均值不等式链

$$
\frac{2}{\frac{1}{a} + \frac{1}{b}} < \sqrt{ab} < \frac{a - b}{\ln a - \ln b} < \frac{a + b}{2} < \sqrt{\frac{a^2 + b^2}{2}}\ (a, b \in \mathrm{R^*},a \ne b) \\
ab < \left(\frac{a + b}{2}\right)^2 < \frac{a^2 + b^2}{2}\ (a, b \in \mathrm{R},a \ne b) \\
$$

## 指数函数

$$
e^x = \sum_{k = 0}^{n} \frac{x^k}{k!} + \omicron(x^n) \\
e^x \ge x + 1\ (x \in \mathrm{R}) \\
e^x \ge \frac{1}{2}x^2 + x + 1\ (x \in \mathrm{R^*}) \\
$$

## 对数函数

$$
\ln(1 + x) = \sum_{k = 1}^{n} \frac{x^n}{k} + \omicron(x^n) \\
\ln(1 + x) \le x \\
\ln(1 + x) \ge x - \frac{x^2}{2} \\
\ln(1 + x) \le x - \frac{x^2}{2} + \frac{x^3}{3} \\
\ln\frac{1}{x} \ge 1 - x \\
$$

$$
\frac{1}{x + 1} \le \ln \frac{x + 1}{x} \le \frac{1}{x}
$$

证明：把 $\frac{x + 1}{x}$ 代入 $\ln\frac{1}{x} \ge
 1 - x$ 得到左边部分，把 $\frac{1}{x}$ 代入 $\ln(1 + x) \le x$ 得到右边。

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