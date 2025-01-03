# MA26100 Notes

## Lecture 1: Vectors

**Ex.**

- $P(x, y)$ and $Q(x, y)$ are two points in the plane. The vector from $P$ to $Q$ is the vector $\vec{PQ} = \vec{Q} - \vec{P} = (x_2 - x_1, y_2 - y_1)$.

- The vector $\vec{PQ}$ is the same as the vector $\vec{QP}$, but in the opposite direction.

- $\vec{PQ} = -\vec{QP}$

- Vector from $P$ to $Q$: $\vec{PQ} = \langle x_2 - x_1, y_2 - y_1 \rangle$

- $P(1, 2)$ and $Q(3, -5)$: $\vec{PQ} = \langle 3 - 1, -5 - 2 \rangle = \langle 2, -7 \rangle$

- The zero vector is the vector with both components equal to zero.

- The magnitude of a vector $\vec{v} = \langle a, b \rangle$ is the length of the vector, denoted by $||\vec{v}|| = \sqrt{a^2 + b^2}$.

- The direction of a vector $\vec{v} = \langle a, b \rangle$ is the angle $\theta$ between the vector and the positive x-axis, where $0 \leq \theta < 2\pi$.

- Magnitude/length of a vector: $||\vec{v}|| = \sqrt{a^2 + b^2}$

- Direction of a vector: $\theta = \arctan\left(\frac{b}{a}\right)$

- Addition/subtraction of vectors: 
  - $\vec{v} + \vec{w} = \langle a + c, b + d \rangle$
  - $\vec{v} - \vec{w} = \langle a - c, b - d \rangle$
  - where $\vec{v} = \langle a, b \rangle$ and $\vec{w} = \langle c, d \rangle$.

- Scalar multiplication: $c\vec{v} = \langle ca, cb \rangle$

- Notation: 
  - $\mathbb{R}^2 = \{(x, y) \mid x, y \in \mathbb{R}\}$ is the set of all ordered pairs of real numbers.
  - $\mathbb{R}^3 = \{(x, y, z) \mid x, y, z \in \mathbb{R}\}$ is the set of all ordered triples of real numbers.
  - $\mathbb{R}^n = \{(x_1, x_2, \ldots, x_n) \mid x_1, x_2, \ldots, x_n \in \mathbb{R}\}$ is the set of all ordered $n$-tuples of real numbers.

- Circle: $x^2 + y^2 = r^2$

- Sphere: $x^2 + y^2 + z^2 = r^2$

- The dot product of two vectors $\vec{v} = \langle a, b \rangle$ and $\vec{w} = \langle c, d \rangle$ is $\vec{v} \cdot \vec{w} = ac + bd$.

- The dot product of two vectors is a scalar.

- The cross product of two vectors $\vec{v} = \langle a, b \rangle$ and $\vec{w} = \langle c, d \rangle$ is $\vec{v} \times \vec{w} = ad - bc$.

- The cross product of two vectors is a vector.

- The cross product of two vectors is perpendicular to both vectors.

- The cross product of two vectors is perpendicular to the plane containing the two vectors.

- The cross product of two vectors is a vector with magnitude equal to the area of the parallelogram spanned by the two vectors.

## Lecture 2: Lines and Planes

- A line in $\mathbb{R}^2$ is determined by a point $P(x_1, y_1)$ on the line and a vector $\vec{v} = \langle a, b \rangle$ parallel to the line.

- Line: a collection of points that lie along a straight path.

- Lines have a direction vector, which is essentially the slope of the line.

- Finding the direction vector involves selecting two points on the line and calculating the difference between their coordinates.

- The equation of a line in $\mathbb{R}^2$ is given by $\vec{r}(t) = \vec{P} + t\vec{v}$ where $P(x_1, y_1)$ is a point on the line and $\vec{v} = \langle a, b \rangle$ is a direction vector.

- The equation of a line in $\mathbb{R}^3$ is given by $\vec{r}(t) = \vec{P} + t\vec{v}$ where $P(x_1, y_1, z_1)$ is a point on the line and $\vec{v} = \langle a, b, c \rangle$ is a direction vector.

- Parameterizing a line involves expressing the coordinates of a point on the line in terms of a parameter $t$.

- A plane in $\mathbb{R}^3$ is determined by a point $P(x_1, y_1, z_1)$ on the plane and two vectors $\vec{v} = \langle a, b, c \rangle$ and $\vec{w} = \langle d, e, f \rangle$ that are parallel to the plane.

- The equation of a plane in $\mathbb{R}^3$ is given by $\vec{r}(u, v) = \vec{P} + u\vec{v} + v\vec{w}$ where $P(x_1, y_1, z_1)$ is a point on the plane and $\vec{v} = \langle a, b, c \rangle$ and $\vec{w} = \langle d, e, f \rangle$ are direction vectors.

- The equation of a plane in $\mathbb{R}^3$ can also be written in the form $Ax + By + Cz = D$, where $A$, $B$, $C$, and $D$ are constants.

- The normal vector to a plane is perpendicular to the plane.

- The normal vector to a plane can be found by taking the cross product of the direction vectors of the plane.

- The normal vector to a plane can also be found by taking the coefficients of $x$, $y$, and $z$ in the equation of the plane.

- The distance from a point $P(x_0, y_0, z_0)$ to a plane $Ax + By + Cz = D$ is given by $d = \frac{|Ax_0 + By_0 + Cz_0 - D|}{\sqrt{A^2 + B^2 + C^2}}$

- The distance from a point to a plane is the length of the perpendicular line segment from the point to the plane.

- Two lines do not have to intersect if they have the same slope in $\mathbb{R}^3$.

- Two lines are parallel if they have the same direction vector.

- Two lines are skew if they are not parallel and do not intersect.

- Two planes are orthogonal if their normal vectors are orthogonal.

- The direction vector of a line is perpendicular to the normal vector of a plane.
