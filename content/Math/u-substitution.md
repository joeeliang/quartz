# Indefinite Integrals
$$\int 2x\cos (x^2) \, dx $$
This is messy. However, notice that $2x$ is the derivative of $x^{2}$. So if we substitute $x^2$ for $u$, then we take this function from the $x$ word into the $u$ world.
$$\begin{align}
u &= x^{2} \\
du &= 2x\ dx \\
\end{align}$$
Substitute these into the original equation.
$$\int \cos(u) \, du $$
Now that is a lot simpler to solve. Substitute back the $x$ for $u$ after you are done.
$$\int \cos(x^{2})2x \, dx $$

# Definite Integrals
If our old function was a definite integral, we would need more work.
$$\int_{1}^2 2x\cos (x^2) \, dx $$
There are two ways to go about this. 
### Case 1: Substitute bounds
After $u$-substitution, we get
$$\int \cos(u) \, du $$
We cannot put the bounds 1 and 2 though, since they are in respect to $x$. Instead, see what $u$ is when $x$ is at that value. $u = x^2 = 1^2 = 1$. Put these into the bounds, and evaluate that way.

### Case 2: Substitute indefinite integral
The other approach is to continue with normal indefinite integrals, obtain the expression in terms of $x$, and use the same bounds. For this function, it would be
$$\int_{1}^2 \cos(x^{2})2x \, dx $$

## Special cases
There are times u-substitution is not necessary but can simplify the expression. For example,
$$(x-1)(x-3)^4$$
can turn into
$$(u+2)u^{4}$$
[Khan Article](https://www.khanacademy.org/math/ap-calculus-ab/ab-integration-new/ab-6-9/a/review-applying-u-substitution)
