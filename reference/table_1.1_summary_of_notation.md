### Table 1.1. Summary of Notation

| Symbol | Meaning |
| --- | --- |
| $\mathbb{R}$ | The set of real numbers |
| $\mathbb{R}^d$ | The set of $d$-dimensional vectors over $\mathbb{R}$ |
| $\mathbb{R}_+$ | The set of non-negative real numbers |
| $\mathbb{N}$ | The set of natural numbers |
| $O, o, \Theta, \omega, \Omega, \tilde{O}$ | Asymptotic notation (see text) |
| $\mathbb{1}_{\text{[Boolean expression]}}$ | Indicator function (equals 1 if expression is true and 0 otherwise) |
| $[a]_+$ | $\max(0, a)$ |
| $[n]$ | The set $\{1, \ldots, n\}$ (for $n \in \mathbb{N}$) |
| $\mathbf{x}, \mathbf{w}$ | (Column) vectors |
| $x_i, w_i$ | The $i$-th element of a vector |
| $\langle \mathbf{x}, \mathbf{w} \rangle$ | $\sum_i x_i w_i$ (inner product) |
| $\|\mathbf{x}\|_2$ or $\|\mathbf{x}\|$ | $(\langle \mathbf{x}, \mathbf{x} \rangle)^{1/2}$ (the $\ell_2$ norm of $\mathbf{x}$) |
| $\|\mathbf{x}\|_1$ | $\sum_i |x_i|$ (the $\ell_1$ norm of $\mathbf{x}$) |
| $\|\mathbf{x}\|_\infty$ | $\max_i |x_i|$ (the $\ell_\infty$ norm of $\mathbf{x}$) |
| $\|\mathbf{x}\|_0$ | The number of nonzero elements of $\mathbf{x}$ |
| $A \in \mathbb{R}^{d \times k}$ | A $d \times k$ matrix over $\mathbb{R}$ |
| $A^\top$ | The transpose of $A$ |
| $A_{i,j}$ | The $(i, j)$-th element of $A$ |
| $\mathbf{x} \mathbf{x}^\top$ | The $d \times d$ matrix s.t. $A_{i,j} = x_i x_j$ (where $\mathbf{x} \in \mathbb{R}^d$) |
| $\mathbf{x}_1, \ldots, \mathbf{x}_m$ | A sequence of $m$ vectors |
| $w^{(t)}$ | The values of a vector $\mathbf{w}$ during an iterative algorithm |
| $w^{(t)}_i$ | The $i$-th element of the vector $w^{(t)}$ |
| $\mathcal{X}$ | Instances domain (a set) |
| $\mathcal{Y}$ | Labels domain (a set) |
| $\mathcal{Z}$ | Examples domain (a set) |
| $\mathcal{H}$ | Hypothesis class (a set) |
| $\ell$ | Loss function |
| $\mathcal{D}$ | A distribution over some set (usually over $\mathcal{Z}$ or over $\mathcal{X}$) |
| $\mathcal{D}(A)$ | The probability of a set $A \subseteq \mathcal{Z}$ according to $\mathcal{D}$ |
| $z \sim \mathcal{D}$ | Sampling $z$ according to $\mathcal{D}$ |
| $z_1, \ldots, z_m$ | A sequence of $m$ examples |
| $\mathbf{z} = (z_1, \ldots, z_m) \sim \mathcal{D}^m$ | Sampling $\mathbf{z} = z_1, \ldots, z_m$ i.i.d. according to $\mathcal{D}$ |
| $\mathbb{P}[f(z)]$ | Probability and expectation of a random variable |
| $\mathbb{P}_\mathcal{D}[f(z)]$ | $\mathbb{P}(f(z))$ for $z : \mathcal{Z} \rightarrow \{\text{true, false}\}$ |
| $\mathbb{E}[f(z)]$ | Expectation of the random variable $f : \mathcal{Z} \rightarrow \mathbb{R}$ |
| $\mathbb{E}_\mathcal{D}[f(z)]$ | $\mathbb{E}[f(z)]$ for $z \sim \mathcal{D}$ |
| $\mathcal{N}(\mu, C)$ | Gaussian distribution with expectation $\mu$ and covariance $C$ |
| $f'(x)$ | The derivative of a function $f : \mathbb{R} \rightarrow \mathbb{R}$ at $x$ |
| $f''(x)$ | The second derivative of a function $f : \mathbb{R} \rightarrow \mathbb{R}$ at $x$ |
| $\frac{\partial f}{\partial w_i}(\mathbf{w})$ | The partial derivative of a function $f : \mathbb{R}^d \rightarrow \mathbb{R}$ w.r.t. $w_i$ at $\mathbf{w}$ |
| $\nabla f(\mathbf{w})$ | The gradient of a function $f : \mathbb{R}^d \rightarrow \mathbb{R}$ at $\mathbf{w}$ |
| $\nabla^2 f(\mathbf{w})$ | The differential set of a function $f : \mathbb{R}^d \rightarrow \mathbb{R}$ at $\mathbf{w}$ |
| $\min_x f(x)$ | $\min \{f(x) : x \in C\}$ (minimal value of $f$ over $C$) |
| $\max_x f(x)$ | $\max \{f(x) : x \in C\}$ (maximal value of $f$ over $C$) |
| $\arg\min_x f(x)$ | $\text{argmin} \{f(x) : x \in C\} = \{x \in C : f(x) = \min_{x \in C} f(x)\}$ |
| $\arg\max_x f(x)$ | $\text{argmax} \{f(x) : x \in C\} = \{x \in C : f(x) = \max_{x \in C} f(x)\}$ |
| $\log$ | The natural logarithm |

