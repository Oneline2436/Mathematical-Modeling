# Mathematical-Modeling
\documentclass{article}
\usepackage{amsmath, amssymb}          % 基础数学库
\usepackage{mathrsfs}                  % 手写体字母
\usepackage{stmaryrd}                  % 逻辑符号
\usepackage{esint}                     % 积分符号扩展
\usepackage{syntonly}                  %试运行
\usepackage{tabularray}                %表格
 \usepackage{color}                    % 颜色
 \usepackage[normalem]{ulem}
\usepackage{tabularray}
\usepackage{graphicx}                  %图像
\usepackage{caption}                   %浮动提标题

以下是涵盖本科数学（微积分、线性代数、概率统计、离散数学等）的所有常用数学符号及其 LaTeX 表示：

---

### **一、基础运算符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $+$ | `+` | $a+b$ |
| $-$ | `-` | $a-b$ |
| $\times$ | `\times` | $a \times b$ |
| $\div$ | `\div` | $a \div b$ |
| $\cdot$ | `\cdot` | $a \cdot b$ |
| $=$ | `=` | $a = b$ |
| $\neq$ | `\neq` | $a \neq b$ |
| $\approx$ | `\approx` | $a \approx b$ |
| $\equiv$ | `\equiv` | $a \equiv b$ |

---

### **二、关系符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $<$ | `<` | $a < b$ |
| $>$ | `>` | $a > b$ |
| $\leq$ | `\leq` | $a \leq b$ |
| $\geq$ | `\geq` | $a \geq b$ |
| $\ll$ | `\ll` | $a \ll b$ |
| $\gg$ | `\gg` | $a \gg b$ |
| $\propto$ | `\propto` | $a \propto b$ |
| $\sim$ | `\sim` | $X \sim N(0,1)$ |

---

### **三、集合符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $\in$ | `\in` | $x \in A$ |
| $\notin$ | `\notin` | $x \notin A$ |
| $\subset$ | `\subset` | $A \subset B$ |
| $\subseteq$ | `\subseteq` | $A \subseteq B$ |
| $\cup$ | `\cup` | $A \cup B$ |
| $\cap$ | `\cap` | $A \cap B$ |
| $\emptyset$ | `\emptyset` | $A = \emptyset$ |
| $\mathbb{N}$ | `\mathbb{N}` | 自然数集 |
| $\mathbb{Z}$ | `\mathbb{Z}` | 整数集 |
| $\mathbb{Q}$ | `\mathbb{Q}` | 有理数集 |
| $\mathbb{R}$ | `\mathbb{R}` | 实数集 |
| $\mathbb{C}$ | `\mathbb{C}` | 复数集 |

---

### **四、微积分符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $\infty$ | `\infty` | $\lim_{x \to \infty}$ |
| $\lim$ | `\lim` | $\lim_{x \to a} f(x)$ |
| $\frac{dy}{dx}$ | `\frac{dy}{dx}` | 导数 |
| $\partial$ | `\partial` | $\frac{\partial f}{\partial x}$ |
| $\int$ | `\int` | $\int f(x)  dx$ |
| $\iint$ | `\iint` | $\iint_D f  dA$ |
| $\oint$ | `\oint` | $\oint_C \mathbf{F} \cdot d\mathbf{r}$ |
| $\nabla$ | `\nabla` | $\nabla f$ (梯度) |
| $\Delta$ | `\Delta` | $\Delta x$ (差分) |

---

### **五、线性代数符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $\mathbf{A}$ | `\mathbf{A}` | 矩阵 |
| $\det(A)$ | `\det(A)` | 行列式 |
| $\mathbf{v}$ | `\mathbf{v}` | 向量 |
| $\langle \mathbf{u},\mathbf{v} \rangle$ | `\langle \mathbf{u},\mathbf{v} \rangle` | 内积 |
| $\times$ | `\times` | $\mathbf{u} \times \mathbf{v}$ (叉积) |
| $\| \mathbf{v} \|$ | `\| \mathbf{v} \|` | 范数 |
| $\otimes$ | `\otimes` | $\mathbf{A} \otimes \mathbf{B}$ (张量积) |
| $\text{tr}(A)$ | `\text{tr}(A)` | 迹 |
| $\text{rank}(A)$ | `\text{rank}(A)` | 秩 |

---

### **六、概率统计符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $P(A)$ | `P(A)` | 概率 |
| $E[X]$ | `E[X]` | 期望 |
| $\text{Var}(X)$ | `\text{Var}(X)` | 方差 |
| $\sigma$ | `\sigma` | 标准差 |
| $\sim$ | `\sim` | $X \sim \text{Binomial}(n,p)$ |
| $\bar{x}$ | `\bar{x}` | 样本均值 |
| $\hat{p}$ | `\hat{p}` | 估计量 |
| $\mathcal{N}(\mu,\sigma^2)$ | `\mathcal{N}(\mu,\sigma^2)` | 正态分布 |
| $\chi^2$ | `\chi^2` | 卡方分布 |
| $\rho$ | `\rho` | 相关系数 |

---

### **七、逻辑与离散数学符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $\forall$ | `\forall` | 任意 |
| $\exists$ | `\exists` | 存在 |
| $\neg$ | `\neg` | 非 |
| $\land$ | `\land` | 且 |
| $\lor$ | `\lor` | 或 |
| $\to$ | `\to` | 蕴含 |
| $\iff$ | `\iff` | 等价 |
| $\equiv$ | `\equiv` | 逻辑等价 |
| $\in$ | `\in` | 属于 |
| $\notin$ | `\notin` | 不属于 |
| $\subseteq$ | `\subseteq` | 子集 |
| $\times$ | `\times` | 笛卡尔积 |
| $|A|$ | `|A|` | 集合基数 |
| $\binom{n}{k}$ | `\binom{n}{k}` | 组合数 |

---

### **八、希腊字母（常用）**
| 大写 | 小写 | LaTeX | 用途 |
|------|------|-------|------|
| $\Gamma$ | $\gamma$ | `\Gamma`, `\gamma` | 伽马函数/角度 |
| $\Delta$ | $\delta$ | `\Delta`, `\delta` | 差分/无穷小 |
| $\Theta$ | $\theta$ | `\Theta`, `\theta` | 角度 |
| $\Lambda$ | $\lambda$ | `\Lambda`, `\lambda` | 特征值 |
| $\Xi$ | $\xi$ | `\Xi`, `\xi` | 随机变量 |
| $\Pi$ | $\pi$ | `\Pi`, `\pi` | 圆周率/乘积 |
| $\Sigma$ | $\sigma$ | `\Sigma`, `\sigma` | 求和/标准差 |
| $\Phi$ | $\phi$ | `\Phi`, `\phi` | 欧拉函数/角度 |
| $\Psi$ | $\psi$ | `\Psi`, `\psi` | 波函数 |
| $\Omega$ | $\omega$ | `\Omega`, `\omega` | 样本空间/角速度 |

---

### **九、其他关键符号**
| 符号 | LaTeX | 示例 |
|------|-------|------|
| $\sum$ | `\sum` | $\sum_{i=1}^n i$ |
| $\prod$ | `\prod` | $\prod_{k=1}^n k!$ |
| $\sqrt{x}$ | `\sqrt{x}` | 平方根 |
| $\sqrt[n]{x}$ | `\sqrt[n]{x}` | n次根 |
| $\bar{z}$ | `\bar{z}` | 共轭复数 |
| $\Re(z)$ | `\Re(z)` | 实部 |
| $\Im(z)$ | `\Im(z)` | 虚部 |
| $\therefore$ | `\therefore` | 因此 |
| $\because$ | `\because` | 因为 |
| $\vdots$ | `\vdots` | 垂直省略号 |
| $\ddots$ | `\ddots` | 对角省略号 |
| $\aleph$ | `\aleph` | 无穷基数 |

---

### **使用示例**
```latex
\documentclass{article}
\usepackage{amsmath, amssymb} % 必须加载的宏包

\begin{document}

微积分示例：
\[
\frac{d}{dx} \left( \int_{0}^{x} f(t)  dt \right) = f(x)
\]

线性代数示例：
\[
\mathbf{A} = \begin{pmatrix}
a_{11} & \cdots & a_{1n} \\
\vdots & \ddots & \vdots \\
a_{m1} & \cdots & a_{mn}
\end{pmatrix}, \quad \det(\mathbf{A}) = \sum_{\sigma \in S_n} \text{sgn}(\sigma) \prod_{i=1}^n a_{i,\sigma(i)}
\]

概率统计示例：
\[
P(X \leq x) = \Phi\left( \frac{x - \mu}{\sigma} \right) \quad \text{其中} \quad X \sim \mathcal{N}(\mu, \sigma^2)
\]

\end{document}
```

> **提示**：
> 1. 需加载宏包：`\usepackage{amsmath, amssymb}`
> 2. 完整符号表参考：[Comprehensive LaTeX Symbol List](https://ctan.org/pkg/comprehensive)
> 3. 手写识别工具：[Detexify](https://detexify.kirelabs.org)

\end{document}
