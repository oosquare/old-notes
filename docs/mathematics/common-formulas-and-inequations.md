## 不等式

### 均值不等式链

$$
\frac{2}{\frac{1}{a} + \frac{1}{b}} < \sqrt{ab} < \frac{a - b}{\ln a - \ln b} < \frac{a + b}{2} < \sqrt{\frac{a^2 + b^2}{2}}\ (a, b \in \mathrm{R^*},a \ne b) \\
ab < \left(\frac{a + b}{2}\right)^2 < \frac{a^2 + b^2}{2}\ (a, b \in \mathrm{R},a \ne b) \\
$$

### 柯西不等式

$$
(x_1^2 + x_2^2 + \cdots)(y_1^2 + y_2^2 + \cdots) \ge (x_1y_1 + x_2y_2 + \cdots)^2
$$

当且仅当 $\frac{x_1}{y_1} = \frac{x_2}{y_2} = \cdots$ 时取等。

## 函数

### 指数函数

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
2\ln x \le x - \frac{1}{x}\ \left(x \ge 1\right) \\
$$

在 $x = 1$ 时取等。

### 帕德近似

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

## 数列

### 裂项放缩

$$
n < \sqrt{n(n + 1)} < \sqrt{(n + 1)^2} = n + 1 \\
\sqrt{n^2 + 2n} < \sqrt{(n^2 + 2n + 1)} = n + 1 \\
\frac{1}{n} < \frac{1}{\sqrt{n(n + 1)}} \\

\frac{1}{n^2} < \frac{1}{n^2 - 1} = \frac{1}{2}\left(\frac{1}{n - 1} - \frac{1}{n + 1}\right) \\
\frac{1}{n^2} = \frac{4}{4n^2} < \frac{4}{4n^2 - 1} = \frac{1}{2}\left(\frac{1}{2n - 1} - \frac{1}{2n + 1}\right) \\
\frac{1}{n^2} < \frac{1}{n(n - 1)} = \frac{1}{n - 1} - \frac{1}{n} \\
\frac{1}{n^2} > \frac{1}{n(n + 1)} = \frac{1}{n} - \frac{1}{n + 1} \\
$$

## 统计

### 统计量

$$
\bar{x} = \frac{1}{n} \sum_{i = 1}^n x_i \\
\bar{x} = \frac{n_1 \bar{x}_1 + n_2 \bar{x}_2}{n_1 + n_2} \\
s^2 = \frac{1}{n} \sum_{i = 1}^n (x_i - \bar{x})^2 = \frac{1}{n}\sum_{i = 1}^n x_i^2 - \bar{x}^2 \\
s^2 = \frac{n_1[s_1^2 + \left(\bar{x}_1 - \bar{x})^2\right] + n_2[s_2^2 + \left(\bar{x}_2 - \bar{x})^2\right]}{n_1 + n_2} = \frac{n_1s_1^2 + n_2s_2^2}{n_1 + n_2} + \frac{n_1n_2(\bar{x}_1 - \bar{x}_2)^2}{(n_1 + n_2)^2} \\
$$

### 线性回归

$$
r = \frac{\sum\limits_{i = 1}^n (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum\limits_{i = 1}^n (x_i - \bar{x})^2}\sqrt{\sum\limits_{i = 1}^n (y_i - \bar{y})^2}} = \frac{\sum\limits_{i = 1}^n x_iy_i - n\bar{x}\bar{y}}{\sqrt{\sum\limits_{i = 1}^n x_i^2 - n\bar{x}^2}\sqrt{\sum\limits_{i = 1}^n y_i^2 - n\bar{y}^2}}
$$

$r \in [-1, 1]$，$|r|$ 越大，拟合效果越好。

$$
R^2 = 1 - \frac{\sum\limits_{i = 1}^{n} (y_i - \hat{y})^2}{\sum\limits_{i = 1}^{n} (y_i - \bar{y})^2}
$$

$R^2 \in [0, 1]$，$R^2$ 越大，拟合效果越好。

$$
\hat{y} = \hat{b}x + \hat{a} \\
\hat{b} = \frac{\sum\limits_{i = 1}^n (x_i - \bar{x})(y_i - \bar{y})}{\sum\limits_{i = 1}^n (x_i - \bar{x})^2} = \frac{\sum\limits_{i = 1}^n x_iy_i - n\bar{x}\bar{y}}{\sum\limits_{i = 1}^n x_i^2 - n\bar{x}^2} \\
\hat{a} = \bar{y} - \hat{b}\bar{x} \\
$$

$\hat{y} = \hat{b}x + \hat{a}$ 过样本中心点 $(\bar{x}, \bar{y})$。

### 独立性检验

$$
\chi^2 = \frac{n(ad - bc)^2}{(a + b)(c + d)(a + c)(b + d)}
$$

## 概率

### 全概率公式与贝叶斯公式

$$
P(A|B) = \frac{P(AB)}{P(B)} = \frac{P(A)P(B|A)}{P(B)} \\
P(A) = \sum_{i = 1}^n P(B_i)P(A|B_i)
$$

### 期望与方差

$$
E(X) = \frac{1}{n}\sum_{i = 1}^n x_iP(X = x_i) \\
D(X) = \frac{1}{n}\sum_{i = 1}^n \left[x_i - E(X)\right]^2 = E\left(X^2\right) - E^2(X)
$$

### 二项分布

$$
X \sim B(n, p) \\
P(X = k) = C_{n}^{k} p^k(1 - p)^{n - k} \\
E(X) = np \\
D(X) = np(1 - p) \\
\frac{P(X = k)}{P(X = k - 1)} = \frac{(n - k + 1)p}{k(1 - p)}
$$

### 超几何分布

$$
X \sim H(n, M, N) \\
P(X = k) = \frac{C_M^kC_{N - M}^{n - k}}{C_N^n} \\
E(X) = \frac{nM}{N} \\
D(X) = \frac{nM(N - M)(N - n)}{N^2(N - 1)} \\
$$

### 正态分布

$$
X \sim N\big(\mu, \sigma^2\big) \\
f(x) = \frac{1}{\sqrt{2\pi}\sigma}\exp\left[-\frac{(x - \mu)^2}{2\sigma^2}\right] \\
E(X) = \mu \\
D(X) = \sigma^2
$$