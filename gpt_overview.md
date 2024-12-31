# MA26100: Multivariate Calculus Notes

## Overview

MA26100 (Multivariate Calculus) expands the concepts learned in single-variable calculus to higher dimensions. The course focuses on the analysis of functions of two or more variables, vector-valued functions, and integration in multiple dimensions. This knowledge is foundational for many fields, including engineering, physics, computer science, and applied mathematics.

Key learning objectives include:

- Understanding and visualizing functions in 2D and 3D.
- Mastering vector calculus and its applications in physics and engineering.
- Applying partial derivatives and multiple integrals in real-world scenarios.
- Solving problems involving vector fields and theorems of vector calculus.

### List of Topics
1. **Vectors and the Geometry of Space**  
2. **Vector Functions and Space Curves**  
3. **Partial Derivatives**  
4. **Multiple Integrals**  
5. **Vector Fields**  
6. **Line Integrals**  
7. **Surface Integrals and Stokes' Theorem**

## 1. Vectors and the Geometry of Space

### Key Concepts

- **Vectors in 3D Space:** Represented as $\vec{v} = \langle v_1, v_2, v_3 \rangle$
  
- **Dot Product:** $\vec{u} \cdot \vec{v} = u_1v_1 + u_2v_2 + u_3v_3$. Used to find angles and projections.
  
- **Cross Product:** $\vec{u} \times \vec{v}$. Results in a vector perpendicular to both $\vec{u}$ and $\vec{v}$

- **Planes and Lines in Space:** Parameterized using vectors.

### Applications
- Calculating work in physics.
- Finding angles between vectors.
- Describing motion paths in 3D.

### How to Solve
- Compute the magnitude: $|\vec{v}| = \sqrt{v_1^2 + v_2^2 + v_3^2}$
  
- For dot product problems, use $\cos \theta = \frac{\vec{u} \cdot \vec{v}}{|\vec{u}||\vec{v}|}$
  
- For plane equations, use the normal vector $\vec{n}$: $\vec{n} \cdot \vec{r} = d$

## 2. Vector Functions and Space Curves

### Key Concepts

- **Vector-Valued Functions:** $\vec{r}(t) = \langle f(t), g(t), h(t) \rangle$
  
- **Derivatives and Tangents:** Derivative of $\vec{r}(t)$ gives the tangent vector.
  
- **Arc Length:** $\int_a^b |\vec{r}'(t)| \, dt$
  
- **Curvature:** Describes how sharply a curve bends.

### Applications
- Modeling motion (velocity, acceleration).
- Computing the length of trajectories.
- Describing curvature for road and object design.

### How to Solve

- Compute velocity: $\vec{v}(t) = \vec{r}'(t)$
  
- Compute acceleration: $\vec{a}(t) = \vec{r}''(t)$
  
- For arc length, integrate $|\vec{r}'(t)|$

## 3. Partial Derivatives

### Key Concepts

- **Partial Derivatives:** $\frac{\partial f}{\partial x} \), \( \frac{\partial f}{\partial y}$

- **Gradient Vector:** $\nabla f = \langle f_x, f_y, f_z \rangle$. Points in the direction of steepest ascent.

- **Chain Rule for Multivariable Functions.**

- **Directional Derivatives:** $D_{\vec{u}}f = \nabla f \cdot \vec{u}$

### Applications
- Optimization problems.  
- Analyzing fluid flow and heat transfer.  
- Estimating changes in engineering systems.

### How to Solve

- Compute each partial derivative separately.

- Use the gradient for optimization problems.

- Apply the chain rule: $\frac{dz}{dt} = \frac{\partial z}{\partial x} \frac{dx}{dt} + \frac{\partial z}{\partial y} \frac{dy}{dt}$

## 4. Multiple Integrals

### Key Concepts

- **Double Integrals:** $\int \int_R f(x, y) \, dA$

- **Triple Integrals:** $\int \int \int_E f(x, y, z) \, dV$

- **Change of Variables:** Using polar, cylindrical, or spherical coordinates.

### Applications
- Calculating volume and mass.  
- Computing center of mass and moments of inertia.  
- Describing distributions over a region.  

### How to Solve

- For double integrals: $\int_a^b \int_c^d f(x, y) \, dy \, dx$

- Convert to polar coordinates when regions are circular.

## 5. Vector Fields

### Key Concepts

- **Vector Field Representation:** $\vec{F}(x, y, z) = \langle P, Q, R \rangle$

- **Divergence:** $\nabla \cdot \vec{F}$. Measures "outflow" from a point.

- **Curl:** $\nabla \times \vec{F}$. Measures rotation of the field.

### Applications
- Modeling fluid flow and electromagnetic fields.  
- Computing flux and circulation.

### How to Solve
- Compute divergence: $\nabla \cdot \vec{F} = \frac{\partial P}{\partial x} + \frac{\partial Q}{\partial y} + \frac{\partial R}{\partial z}$

- Compute curl:
```math
\begin{aligned}
\nabla \times \vec{F} = 
\begin{vmatrix} 
\vec{i} & \vec{j} & \vec{k} \\ 
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ 
P & Q & R 
\end{vmatrix}
\end{aligned}
```

## 6. Line Integrals

### Key Concepts

- **Line Integrals of Scalar Fields:** $\int_C f(x, y, z) \, ds$

- **Line Integrals of Vector Fields:** $\int_C \vec{F} \cdot d\vec{r}$

- **Conservative Fields:** $\vec{F} = \nabla f$. Path-independent.  

### Applications
- Calculating work done by a force field.
- Solving problems in physics and engineering.

### How to Solve

- Parameterize the curve $C$: $\vec{r}(t) = \langle x(t), y(t), z(t) \rangle$

- Substitute into $\int_C f(x, y, z) \, ds$

## 7. Surface Integrals and Stokes' Theorem

### Key Concepts

- **Surface Integrals:** $\int \int_S \vec{F} \cdot d\vec{S}$

- **Stokes' Theorem:** Relates surface integrals to line integrals: $\int \int_S (\nabla \times \vec{F}) \cdot d\vec{S} = \int_C \vec{F} \cdot d\vec{r}$

- **Divergence Theorem:** $\int \int \int_E (\nabla \cdot \vec{F}) \, dV = \int \int_S \vec{F} \cdot d\vec{S}$

### Applications
- Calculating flux in physics.  
- Analyzing electromagnetic fields.  

### How to Solve
- Parameterize the surface.  
- Use Stokes' Theorem to simplify calculations when possible.  
