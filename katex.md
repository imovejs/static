# 项目文档示例

## 简介

这是一个 Markdown 文档的示例，展示了各种常见格式。

### 目的

该文档的目的是提供一个关于如何使用 Markdown 的简单指南。

## 目录

1. [简介](#简介)
2. [基本语法](#基本语法)
3. [示例代码](#示例代码)
4. [图像](#图像)
5. [表格](#表格)
6. [结论](#结论)

## 基本语法

### 1. 段落

Markdown 允许您创建段落。段落之间要有一个空行。

### 2. 列表

#### 无序列表

- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
- 项目 3

#### 有序列表

1. 第一项
2. 第二项
3. 第三项

### 3. 链接和引用

- [Markdown 官方网站](https://daringfireball.net/projects/markdown/)
- 这是一个引用的示例：
  > “这是一条引用。”

## 示例代码

以下是一个 Python 函数的代码示例：

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("World"))
```


## 表格
## 开源 SSH 客户端工具列表

| 工具名称 (Tool Name)        | 主要平台 (Primary Platform(s)) | 类型 (Type) | 主要特点 (Key Features)                                                                 | 开源协议 (License) | 备注 (Notes)                                                                 |
| :-------------------------- | :----------------------------- | :---------- | :------------------------------------------------------------------------------------ | :----------------- | :--------------------------------------------------------------------------- |
| **OpenSSH (Client)**        | Linux, macOS, Windows (内置或可安装), BSD | CLI         | 行业标准、极其稳定可靠、功能全面、支持最新加密算法、可通过配置文件高度定制、支持密钥对、代理跳转、端口转发等 | BSD / MIT-like   | 绝大多数 Linux 和 macOS 系统自带。Windows 10/11 也内置了客户端 (`ssh.exe`)。是许多 GUI 工具的基础。 |
| **PuTTY**                   | Windows (主要), Linux/macOS (非官方移植版) | GUI         | 轻量级、单文件可执行 (Windows)、支持 SSH/Telnet/Rlogin/Serial、会话管理、配置简单、稳定性好       | MIT                | Windows 平台上历史悠久且非常流行的选择。                                                |
| **KiTTY**                   | Windows                        | GUI         | PuTTY 的一个分支 (fork)，增加了许多 PuTTY 没有的功能，如自动登录脚本、会话过滤器、快捷方式、透明度等 | MIT                | 对于需要比 PuTTY 更多便捷功能的用户来说是个好选择。                               |
| **Tabby** (原 Terminus)     | Windows, macOS, Linux          | GUI         | 现代化界面、高度可定制（主题、插件）、支持 SSH/Telnet/Serial/SFTP/PowerShell/WSL、多标签页、分屏、云同步 | MIT                | 基于 Electron 构建，功能丰富，界面美观。                                            |
| **Electerm**                | Windows, macOS, Linux          | GUI         | 现代化界面、集成了终端模拟器、文件管理器 (SFTP/FTP)、SSH 客户端、支持同步配置到 Gitee/GitHub、多语言 | MIT                | 同样基于 Electron，功能与 Tabby 类似，提供了集成的文件管理功能。                           |
| **Windows Terminal**        | Windows 10/11                  | GUI (宿主)  | 微软官方现代终端应用、支持多标签页、分屏、高度自定义（主题、配色、字体）、可无缝集成运行 CMD、PowerShell、WSL 以及 OpenSSH 客户端 (`ssh.exe`) | MIT                | 本身是终端模拟器，但通过调用系统内置的 `ssh.exe` 提供了优秀的 SSH 连接体验。              |
| **iTerm2**                  | macOS                          | GUI         | macOS 平台功能最强大的终端模拟器之一、高度可定制、支持分屏、标签页、搜索、触发器、自动完成、密码管理器集成等 | GPLv2              | macOS 用户的首选之一，提供了非常丰富的终端增强功能。                                    |

**选择建议:**

*   **跨平台 & 现代化 UI:** `Tabby` 或 `Electerm` 是不错的选择。
*   **Windows 平台经典 & 轻量:** `PuTTY` 或功能增强的 `KiTTY`。
*   **Linux/macOS 命令行用户:** `OpenSSH` (通常已内置) 是不二之选。
*   **Windows 现代原生体验:** 使用 `Windows Terminal` 调用内置的 `OpenSSH` 客户端。
*   **macOS 强大功能:** `iTerm2` 是标杆。


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
