## Linear Algebra

**Element-wise product (Hadamard product)**:  ${C = A{\odot} B}: {C_{i,j}} = A_{i,j}B_{i,j}$



A norm is any function f that satisfies:

- ${f(x)=0 \Rightarrow x = 0}$
- ${f(x + y) \le f(x) + f(y) }$
- ${\forall {\alpha} \in \R, f({\alpha}x) = |\alpha|f(x) }$



**Diagonal matrix**: if and only if ${D_{i,j} = 0}$ for all ${i\neq j}$

> diag($\nu$) : a square diagonal , diagonal entries are given by the the entries of vector $\nu$
>
> $diag({\nu})x = {\nu} \odot x$
>
> ${diag(v)^{-1} = diag([\frac{1}{v_1},...,\frac{1}{v_n}]^{\top})}$
>
> *Restricting some matrices to be diagonal can obtain a less expensive algorithm*

Exist a *rectangular* diagonal matrix: **non-square diagonal matrix **$D$

**Symmetrix matrix**:  Any matrix that is equal to its own transpose $A = A^{\top}$

**unit vector**: a vector with *unit norm* $||x||_2 = 1$

**orthogonal**: vector x, y , if ${x^{\top}y=0}$

**orthonormal**: vectors are not only orthogonal but also have unit norm.

**orthogonal matrix**: A square matrix whose row and columns are mutually orthonormal ${A^{\top}A = AA^{\top} = I}$

>  Implies：${A^{-1} = A^{T}}$
>
> 
