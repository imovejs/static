# 复杂 LaTeX 公式示例

本文档展示了一些复杂的 LaTeX 公式，适用于高等数学、物理和工程学科。

## 1. 复杂数学公式

1. **多元函数的偏导数**：
   $$
   \frac{\partial f}{\partial x} = \lim_{\Delta x \to 0} \frac{f(x + \Delta x, y) - f(x, y)}{\Delta x}
   $$

2. **梯度向量**：
   $$
   \nabla f = \left( \frac{\partial f}{\partial x_1}, \frac{\partial f}{\partial x_2}, \ldots, \frac{\partial f}{\partial x_n} \right)
   $$

3. **重积分**：
   $$
   \iint_D f(x, y) \, dA = \lim_{m, n \to \infty} \sum_{i=1}^{m} \sum_{j=1}^{n} f(x_i, y_j) \Delta A
   $$

4. **无穷级数**：
   $$
   S = \sum_{n=0}^{\infty} a_n = a_0 + a_1 + a_2 + \cdots
   $$

## 2. 线性代数和微分方程

5. **特征值和特征向量**：
   $$
   A \mathbf{v} = \lambda \mathbf{v}
   $$

6. **常微分方程的一般解**：
   $$
   y'' + p(x)y' + q(x)y = 0
   $$

7. **线性方程组的矩阵表示**：
   $$
   \mathbf{Ax} = \mathbf{b}
   $$

8. **拉普拉斯变换**：
   $$
   \mathcal{L}\{f(t)\} = \int_0^{\infty} e^{-st} f(t) \, dt
   $$

## 3. 物理公式

9. **麦克斯韦方程组**：
   $$
   \begin{align*}
   \nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
   \nabla \cdot \mathbf{B} &= 0 \\
   \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
   \nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
   \end{align*}
   $$

10. **相对论性动量**：
    $$
    \mathbf{p} = \frac{m \mathbf{v}}{\sqrt{1 - \frac{v^2}{c^2}}}
    $$

11. **费米能级**：
    $$
    E_F = \frac{\hbar^2}{2m} \left( \frac{3\pi^2 n}{2} \right)^{2/3}
    $$

12. **薛定谔方程**：
    $$
    i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t) = -\frac{\hbar^2}{2m} \nabla^2 \Psi(\mathbf{r}, t) + V(\mathbf{r}) \Psi(\mathbf{r}, t)
    $$

## 总结

以上展示了更复杂的 LaTeX 公式，涉及偏导数、梯度、无穷级数、拉普拉斯变换、麦克斯韦方程组等高等数学和物理学的关键概念。
