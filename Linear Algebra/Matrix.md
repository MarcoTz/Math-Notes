A $n\times m$-*matrix* over a [[field]] $K$ is an element of $K^{n\times m}$, i.e. a tuple of $n$ elements of $K^m$ or equivalently $m$ elements of $K^n$.
We write a matrix $M\in K^{n\times m}$ as $M = (M_{ij})_{1\leq i\leq n, 1\leq i\leq m}$ or in a grid 

$\left[\begin{array}{ccc}M_{11} & \dots & M_{1m}\\ \vdots & \ddots & \vdots\\ M_{n1} & \dots & M_{nm}\end{array}\right]$

For two matrices with the same dimensions $A,B$, their *sum* is defined as $(A+B)_{ij} = A_{ij} + B_{ij}$
For a matrix $A$ with dimension $n\times k$ and $B$ with dimension $k\times m$, their *product* is defined as the $n\times m$ matrix $C$ with $C_{ij} = \sum_{k=1}^k a_{ik}b_{jk}$.
With this definition of addition and multiplication, $n\times n$ matrices over a field $K$ form a [[Ring]] $M_n(K)$

The $n\times n$ matrix with ones on the diagonal and $0$ everywhere else is called the *identity* matrix, denoted $E_n$.

A *diagonal matrix* is a square matrix with only entries on the diagonal being nonzero. We write $diag(a_1,\dots,a_n)$ for a $n\times n$ diagonal matrix with $a_1,\dots a_n$ on the diagonal. 

A triangular matrix is a matrix where all entries above or below the diagonal are 0. In the first case it is called an *lower triangular matrix* and in the second an *upper triangular matrix*

#### Matrix - Vector Multiplication 

Given a $K$-[[Vector Space]] $K^n$ and a $n\times m$ matrix $M$ with elements in $K$, the product $Mv$ for any $v\in V$ is defined as the element $w \in K^m$ with entries $w_j = \sum_{i=1}^n M_{ji}v_j$


#### Transpose of a matrix 

Given a $n\times m$-matrix $M$, the *transpose* of $M$, denoted $M^T$ is the $m\times n$-matrix with entries $M^T_{ij} = M_{ji}$. We have $(M^T)^T = M$.

#### Trace 

Given a $n\times n$- matrix, the *trace* of $M$, denoted $trM$ is defined as 

$tr(M) = \sum_{i=1}^n M_{ii}$