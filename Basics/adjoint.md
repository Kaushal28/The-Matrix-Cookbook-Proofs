
**1.**
### $A.adj(A)= adj(A).A = |A|I$
<!-- spaces -->
#### Let  A be a square matrix of order n and C represent the cofactor matrix of A and adj(A) represent the adjoint of matrix A .

$$(adj(A))_{ij} = [C_{ij}]^T = C_{ji}$$
<br>
$$(A.adj(A))_{ij} = \sum_{r=1}^{r=n} a_{ir}.(adj(A))_{rj}$$
<br>
$$(A.adj(A))_{ij} = \sum_{r=1}^{r=n} a_{ir}.C_{jr}$$
<br> 
#### We Know,
<!-- spaces -->
##### Sum of products of  elements with their corresponding cofactor is equal to the determinant of the matrix.
<br>
$$(A.adj(A))_{ij} = \sum_{r=1}^{r=n} a_{ir}.C_{jr} = \left\{\begin{array}\\ 
|A| & \mbox{if } \ i=j\\ 
0 & \mbox{if } \ i \neq j
\end{array}\right.$$

<!-- spaces -->
#### So,
<br>
$$ A.adj(A) = \begin{bmatrix} |A| &  0  &  0  & . & . & 0
                            \\  0  & |A| &  0  & . & . & 0
                            \\  .  & . & . & . & . & .
                            \\  .  & . & . & . & . & .
                            \\  0  & 0 & . & . & . & |A|
                            \end{bmatrix}_{n\times n}$$
                            
<br>
$$ A.adj(A) = |A|.\begin{bmatrix} 1 &  0  &  0  & . & . & 0
                            \\  0  & 1 &  0  & . & . & 0
                            \\  .  & . & . & . & . & .
                            \\  .  & . & . & . & . & .
                            \\  0  & 0 & . & . & . & 1
                            \end{bmatrix}_{n\times n}$$
                            
<br>
$$A.adj(A) = |A|.I_{n}$$

<!-- spaces -->
##### Similarly we can prove adj(A).A = |A|.I



