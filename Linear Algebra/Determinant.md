The *determinant* of a $n\times n$ - [[matrix]] $M$ with entries in a [[field]] $K$ is an element of $K$ used to characterize a matrix. It is denoted by $det(M)$ or $|M|$

### Leibniz formula 


$$ det(M)=\sum_{\tau\in S_n} sgn(\tau)\Pi_{i=1}^n m_{i,\tau{i}}= \sum_{\tau\in S_n}sgn(\tau)\Pi_{i=1}^n m_{\tau(i),i}$$

For $sgn$ and $S_n$ see [[Symmetric Group]]

For a $3\times 3$ matrix $A$ with entries $a_{ij}$ this gives 

$$det(A) = a_{1,1}(a_{2,2}a_{3,3}-a_{2,3}a_{3,2})-a_{1,2}(a_{2,1}a_{3,3}-a_{2,3}a_{3,1})+a_{1,3}(a_{2,1}a_{3,2}-a_{2,2}a_{3,1})$$

Since this formula is difficult to calculate, others are often used.

### Minors 

The $i,j$-th minor $M^\#_{ij}$ of $M$ is the determinant of the matrix obtained by removing row $i$ and column $j$ from $M$.

### Laplace expansion

$$ det(M) = \sum_{j=1}^n (-1)^{i+j} M_{ij}M^\#_{ij})$$

### Properties 

* $det(E_n) = 1$ 
* the determinant is a  [[Multilinear Form]] in the columns of $M$
* the determinant is an Alternating Form ([[Multilinear Form#Alterating Forms]])
* $det(cA)=c^ndet(A)$
* Exchanging columns of a matrix mutliplies the determinant by $-1$ 
* If a matrix has less than maximum [[Rank]], then its determinant is 0
* For a triangular matrix, the determinant is the product of diagonal entries
* $det(A^T)=det(A)$
* $det(AB)=det(A)det(B)$
* $det(A^{-1})=\frac{1}{det(A)}$