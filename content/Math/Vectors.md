# Definitions
**Co-linear:** Same line
**Co-planer:** Same plane

Every vector coplanar with **a** and **b** can be expressed as a linear combination of the two.

**Position wevector**: starting at origin and ending on point P.

Magnitude is just distance from the start and ending point.

Unit vector can be obtained by dividing the vector by its magnitude.
## Dot Product
Algebraic definition:
$$\mathbf{u} \cdot \mathbf{v} = u_1 v_1 + u_2 v_2 + \cdots + u_n v_n$$
Geometric definition:
$$\mathbf{u} \cdot \mathbf{v} = |\mathbf{u}| |\mathbf{v}| \cos \theta$$
If the dot product is zero, the two vectors are perpendicular. 
If they are parallel, $a \cdot b = \pm|a||b|$
Also, $a \cdot a = |a|^2$

# Equation of Lines
**Vector equation:**
$$\mathbf{r}=\mathbf{a}+\lambda \mathbf{d}\\ \Rightarrow \begin{pmatrix} x\\y\\z\end{pmatrix} = \begin{pmatrix} a_{1}\\a_{2}\\a_{3}\end{pmatrix} + \lambda\begin{pmatrix} d_{1}\\d_{2}\\d_{3}\end{pmatrix}
$$
**Parametric Form:**
$$
\begin{align}
x=a_1+λd_1\\y=a_2+λd_2\\z=a_3+λd_{3}
\end{align}
$$
**Cartesian Form**
$$
\frac{x-a_1}{d_1} = \frac{y-a_2}{d_2} = \frac{z-a_3}{d_3}
$$
Understand where the directional vector and positional vector are in each form. They are all there.

A pair of lines can have three states:
- Intersection
- Parallel
- Not intersect nor parallel (skewed)

# Cross product
$$\mathbf{a} \times \mathbf{b} = (a_2b_3 - a_3b_2)\mathbf{i} - (a_1b_3 - a_3b_1)\mathbf{j} + (a_1b_2 - a_2b_1)\mathbf{k}$$
An important property:
$$\mathbf{a}\times \mathbf{b}=(|a||b|\sin \theta )\hat{n}$$
where $\hat{n}$ is the unit vector whose direction is given by the [[right hand rule]] to $a$ and then $b$.

So, if we only take the magnitude of both sides, we will obtain the other identity:
$$|\mathbf{a}\times \mathbf{b}|=|a||b|\sin \theta$$
 Examining the right side, we can also see that this magnitude is the same as the area of the parallelogram enclosed by the two vectors $a$ and $b$.

Operation properties:
- Non-communitive
- Non-associative
- Distributive
- You can distribute a scalar into ONE of the vectors. ie. $$\lambda(a\times b)=\lambda a\times b=a\times \lambda b$$
# Mixed Product  
The mixed product $|(a\times b)\cdot c|$ gives the volume of the parallelepiped formed by three non-coplaner vectors. The proof is as follows:
$$\begin{align} V &= \text{Base } \times \text{height}\\
V &= |a\times b||c|\cos \theta \\ V &= |(a\times b)\cdot c|\end{align}$$
To find the cone, we can continue with the idea: $\frac{1}{6}|(a\times b)\cdot c|$. The base is half of the parallelogram, and the height is multiplied by $\frac{1}{3}$ for a cone or pyramid.
