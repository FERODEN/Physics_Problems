# Vector Algebra – Step by Step Solution

Given vectors:

$$
\vec{a} = [2, 1, -3]
$$

$$
\vec{b} = [4, -2, 1]
$$

---

## a) Magnitude of Each Vector

The magnitude (length) of a vector is given by:

$$
|\vec{v}| = \sqrt{x^2 + y^2 + z^2}
$$

### Magnitude of **a**

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4 + 1 + 9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

---

### Magnitude of **b**

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16 + 4 + 1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

---

## b) Dot Product $\vec{a} \cdot \vec{b}$

The dot product formula:

$$
\vec{a} \cdot \vec{b} = a_1b_1 + a_2b_2 + a_3b_3
$$

Substitute the values:

$$
\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1)
$$

$$
= 8 - 2 - 3
$$

$$
= 3
$$

---

## c) Cross Product $\vec{a} \times \vec{b}$

The cross product is computed using the determinant:

$$
\vec{a} \times \vec{b} =
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

Now compute each component:

### i-component

$$
(1)(1) - (-3)(-2)
$$

$$
= 1 - 6 = -5
$$

### j-component (remember the minus sign!)

$$
- \left[(2)(1) - (-3)(4)\right]
$$

$$
= - (2 + 12)
$$

$$
= -14
$$

### k-component

$$
(2)(-2) - (1)(4)
$$

$$
= -4 - 4
$$

$$
= -8
$$

---

### Final Cross Product:

$$
\vec{a} \times \vec{b} = [-5, -14, -8]
$$

---

## d) Angle Between the Vectors

The formula for the angle between two vectors is:

$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

Substitute the values:

$$
\cos\theta = \frac{3}{\sqrt{14}\sqrt{21}}
$$

Combine radicals:

$$
\cos\theta = \frac{3}{\sqrt{294}}
$$

Now compute the angle:

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
$$

Approximate values:

$$
\sqrt{294} \approx 17.15
$$

$$
\cos\theta \approx \frac{3}{17.15} \approx 0.175
$$

$$
\theta \approx 79.9^\circ
$$

---

# Final Answers

- Magnitude of **a**: $\sqrt{14}$
- Magnitude of **b**: $\sqrt{21}$
- Dot product: $3$
- Cross product: $[-5, -14, -8]$
- Angle between vectors: $\approx 79.9^\circ$