- [Vector Operations](#Vector%20Operations)
	- [Addition (Graphical)](#Addition%20(Graphical))
	- [Subtraction](#Subtraction)
- [Vector Resolution](#Vector%20Resolution)
- [Adding Vectors Analytically](#Adding%20Vectors%20Analytically)
	- [Example Problem](#Example%20Problem)
		- [Solution](#Solution)
- [Subtracting Vectors Analytically](#Subtracting%20Vectors%20Analytically)
- [Unit Vectors](#Unit%20Vectors)
	- [Problem](#Problem)
		- [Solution](#Solution)
- [Rotation of Axes](#Rotation%20of%20Axes)
	- [Problem](#Problem)
	- [Problem](#Problem)
		- [Solution](#Solution)
- [Vector Multiplication](#Vector%20Multiplication)
	- [Multiplication by Scalar](#Multiplication%20by%20Scalar)
	- [VxV multiplication](#VxV%20multiplication)



# Vector Operations

## Addition (Graphical)
$$\vec{s} = \vec{a} + \vec{b}$$

![](Pasted%20image%2020230622205914.png)
![](Pasted%20image%2020230625153111.png)
![](Pasted%20image%2020230625153124.png)

## Subtraction
$$\vec{V_1} - \vec{V_2} = \vec{V_1} + (-\vec{V}_2)$$
![](Pasted%20image%2020230625141403.png)

![](Pasted%20image%2020230625153156.png)
![](Pasted%20image%2020230625153207.png)
![](Pasted%20image%2020230625153220.png)


# Vector Resolution
- Breaking up a vector into its $x$ and $y$ components
![](Pasted%20image%2020230625153252.png)
![](Pasted%20image%2020230625153401.png)
![](Pasted%20image%2020230625153451.png)

$$A_x = A \cos \theta$$
$$A_y = A \sin \theta$$
$$\theta = \tan^{-1}(\frac{A_y}{A_x})$$

# Adding Vectors Analytically
![](Pasted%20image%2020230628001536.png)

- We can find $R$ and $\theta_R$  with:
$$A = \sqrt{A_x^2 + A_y^2}$$
$$\theta = \tan^{-1}(\frac{A_y}{A_x})$$

1. Identify $x$ and $y$ axes in the problem
2. Find components of each vector to be added along the chosen perpendicular axes

$$A_x = A \cos \theta$$
$$A_y = A \sin \theta$$
![](Pasted%20image%2020230628001748.png)

3. Find the components of the **resultant** along each axis
$$R_x = A_x + B_x$$
$$R_y = A_y + B_y$$
![](Pasted%20image%2020230628001831.png)

4. Get magnitude and direction of $R$
$$A = \sqrt{A_x^2 + A_y^2}$$
$$\theta = \tan^{-1}(\frac{A_y}{A_x})$$

## Example Problem
![](Pasted%20image%2020230628001934.png)

- $A = 53 \; \text{m}$
- $\theta_A = 20.0^{\circ}$
- $B = 34.0 \; \text{m}$
- $\theta_B = 63.0^{\circ}$

### Solution

$$A_x = A \cos \theta_A = (53.0 \; \text{m})(\cos 20^{\circ}) = (53)(0.940) = 49.8\;\text{m}$$
$$A_y = A \sin \theta_A = (53.0 \; \text{m})(\sin 20^{\circ}) = (53)(0.342) = 18.1 \; \text{m}$$
$$B_x = B \cos \theta_B = (34\;\text{m})(\cos 63^{\circ}) = (34)(0.454) = 15.4 \; \text{m}$$
$$B_y = B \sin \theta_B = (34 \; \text{m})(\sin 63^{\circ}) = (34)(0.891) = 30.3\;\text{m}$$

$$R_x = A_x + B_x = 49.8 + 15.4 = \boxed{65.2 \; \text{m}}$$
$$R_y = A_y + B_y = 18.1 + 30.3 = \boxed{48.4 \; \text{m}}$$

$$R = \sqrt{R_x^2 + R_y^2} = \sqrt{65.2^2 + 48.4^2} = \boxed{81.2 \;\text{m}}$$
$$\theta = \tan^{-1}(R_y/R_x) = \tan^{-1}(48.4/65.2) = \tan^{-1}(0.742) = \boxed{36.6^{\circ}}$$

![](Pasted%20image%2020230628002543.png)

# Subtracting Vectors Analytically
- Addition of a negative vector

$$R_x = A_x + (-B_x)$$
$$R_y = A_y + (-B_y)$$
![](Pasted%20image%2020230628002719.png)


# Unit Vectors
- **Unit vector** = Vector with **magnitude of 1** and points in a particular direction
	- Lacks dimension and unit
	- Only purpose is to **point**
	- $(x, y, z) \to (\hat{i}, \hat{j}, \hat{k})$
- Useful for expressing components of another vector

$$\vec{a} = a_x \hat{i} + a_y \hat{j}$$
$$\vec{b} = b_x \hat{i} + b_y \hat{j}$$

## Problem
![](Pasted%20image%2020230628003240.png)

### Solution
a) (+, +)
b) (+, -)
c) (+, +)


# Rotation of Axes
- We can rotate the $x$ and $y$ axes by angle $\phi$
- In this case, components would have new values $a\prime_x$ and $a\prime_y$
- Infinite number of "valid" pairs of components

$$a = \sqrt{a_x^2 + a_y^2} + \sqrt{a\prime_x^2 + a\prime_y^2}$$
$$\theta = \theta\prime + \phi$$
![](Pasted%20image%2020230628003721.png)


## Problem

![](Pasted%20image%2020230628003857.png)
> Start at $i$ and end at $c$. We undergo 3 displacements:
> $d_1 = 6.00 \; \text{m}$
> $\theta_1 = 40^{\circ}$
> 
> $d_2 = 8.00 \; \text{m}$
> $\theta_2 = 30^{\circ}$
> 
> $d_3 = 5.00\;\text{m}$
> $\theta_3 = 0^{\circ}$
> 
> When we reach $c$, what are the magnitude and angle of our neg displacement $\vec{d}_{\text{net}}$ from $i$?

1. Sum three individual displacement vectors
$$\vec{d}_{\text{net}} = \vec{d}_1 + \vec{d}_2 + \vec{d}_3$$

2. Components alone
$$d_{\text{net, x}} = d_{1x} + d_{2x} + d_{3x}$$
$$d_{\text{net, y}} = d_{1y} + d_{2y} + d_{3y}$$

3. Construct from components
![](Pasted%20image%2020230628004438.png)
![](Pasted%20image%2020230628004447.png)
![](Pasted%20image%2020230628004457.png)

4. Calculations
![](Pasted%20image%2020230628004521.png)
![](Pasted%20image%2020230628004529.png)
![](Pasted%20image%2020230628004556.png)
![](Pasted%20image%2020230628004601.png)

$$d_{\text{net}} = \sqrt{(13.6)^2 + (-3.07)^2} = \boxed{13.9 \;\text{m}}$$
$$\theta = \tan^{-1}(\frac{-3.07}{13.6}) = \boxed{-12.7^{\circ}}$$


## Problem
> $$\vec{a} = (4.2)\hat{i} - (1.5)\hat{j}$$
> $$\vec{b} = (-1.6)\hat{i} + (2.9)\hat{j}$$
> $$\vec{c} = (-3.7)\hat{j}$$
> What is the vector sum $\vec{r}$?
> ![](Pasted%20image%2020230628004921.png)

### Solution
$$r_x = a_x + b_x + c_x = 4.2 - 1.6 + 0 = \boxed{2.6 \; \text{m}}$$
$$r_y = a_y + b_y + c_y = -1.5 + 2.9 - 3.7 = \boxed{-2.3\; \text{m}}$$
$$\boxed{\vec{r} = (2.6)\hat{i} - (2.3) \hat{j}}$$
$$r = \sqrt{(2.6)^2 + (-2.3)^2} \approx \boxed{3.5 \;\text{m}}$$
	$$\theta = \tan^{-1}(\frac{-2.3}{2.6}) = \boxed{-41^{\circ}}$$

# Vector Multiplication
## Multiplication by Scalar
$$c\vec{V}$$
- $c\vec{V}$ has the same direction as $\vec{V}$ and has magnitude of $cV$
- If $c<0$, then $c\vec{V}$ is in the opposite direction
- To divide $\vec{V}$ by $c$, we multiple $\vec{V}$ by $1/c$

## VxV multiplication
- Two ways to VxV
- **Scalar product**
- **Vector product**