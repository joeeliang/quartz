# Imaginary
$i=\sqrt{ -1 }$.
All complex numbers have a real part and an imaginary part. The modulus is
$$\sqrt{ Re + Im }$$
When its at the bottom of a fraction, you can multiply by the conjugate to make it more normal. The method leverages the difference of squares.
# Division with Polynomials
## Synthetic division
Coefficients inside the box. The root in the outside. Sum down a column, multiply difference by the root and bring to next box. The remaining solution is one degree less in every term in comparison to prior.
## Long Division
Line the digits up, but instead of place values, its the degree of the terms that sets the places.
# Remainder Theorem
When polynomial $f(x)$ is divided by $(x-a)$, the remainder is $f(a)$.
# Factor theorem
Builds off of remainder theorem. If you substitute in the $f(a)$ to obtain zero, then $(x-a)$ is a factor.
# Complex roots
If a real polynomial has complex roots, the complex roots must come in conjugate pairs. Quite a helpful fact. All synthetic division stuff work with this too.
# Sum and Product rule
For a polynomial $$\sum^n_{r=0} a_{r}x^r$$
Sum of roots is $-\frac{a_{n-1}}{a_{n}}$ and the product is $\frac{(-1)^na_{0}}{a_{n}}$
Summary: Sum is second term divided by first term. Product is last term divided by first term, alternating signs every time the degree increases.
# Solving systems
Matrix of coefficents and then the result on the rightmost column. Rref() it  to get the solution.