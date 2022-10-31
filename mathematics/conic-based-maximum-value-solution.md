## 定义
圆锥曲线的一般方程为 $Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0$。若变量 $x,y$ 满足一个二元二次方程，则可以进行三角换元求关于 $x,y$ 的式子的最值。

## 常见模型
### 圆
若 $x,y$ 满足以下关系：

$$
x^2 + y^2 + Dx + Ey + F = 0
$$

即

$$
\left(x + \frac{D}{2}\right)^2 + \left(y + \frac{E}{2}\right)^2 = \frac{D^2 + E^2 - 4F}{4} = R^2
$$

则可以得出一组参数方程：

$$
\begin{cases}
    x = R\cos \theta - \frac{D}{2}\\
    y = R\sin \theta - \frac{E}{2}\\
\end{cases}
$$

### 椭圆
若 $x,y$ 满足以下关系：

$$
Ax^2 + Bxy + Cy^2 + F = 0
$$

则可以想办法配凑为如下形式：

$$
\frac{(px+qy)^2}{a^2} + \frac{(sx+ty)^2}{b^2} = 1\ (a > b > 0)
$$

然后得出参数方程：

$$
\begin{cases}
    px + sy = a\cos \theta\\
    sx + ty = b\sin \theta\\
\end{cases}
$$

即可用 $\theta$ 表示出 $x, y$ 然后再代入其他式子。

> > 已知 $x, y \in \mathrm{R}$ 且 $x^2 + 2xy + 5y^2 = 4$，求 $z = 2x + y$ 的最大值。
>
> 参考答案：
>
>
> $\because x^2 + 2xy + 5y^2 = 4$
>
> $\therefore (x + y)^2 + 4y^2 = 4$
>
> $\therefore \frac{(x + y)^2}{4} + y^2 = 1$
>
> $\therefore \begin{cases} x + y = 2\cos\theta\\ y = \sin\theta\\ \end{cases}$
>
> $\therefore \begin{cases} x = 2\cos\theta - \sin\theta\\ y = \sin\theta\\ \end{cases}$
>
> $\therefore z = 2x + y = 4\cos\theta - \sin\theta = -\sqrt{17}\sin[\theta + \arctan(-4)]$
>
> $\therefore z_{\mathrm{max}} = \sqrt{17}$