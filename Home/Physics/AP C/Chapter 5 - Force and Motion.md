- [Force](#Force)
- [Newton's First Law (Law of Inertial)](#Newton's%20First%20Law%20(Law%20of%20Inertial))
- [Inertial Reference Frames](#Inertial%20Reference%20Frames)
- [Mass](#Mass)
- [Newton's Second Law](#Newton's%20Second%20Law)
- [Gravitational Force](#Gravitational%20Force)
	- [Free fall](#Free%20fall)
	- [Weight](#Weight)
- [Normal Force](#Normal%20Force)
- [Tension](#Tension)
- [Newton's Third Law](#Newton's%20Third%20Law)
- [Application - Pulleys](#Application%20-%20Pulleys)
	- [What is the problem all about?](#What%20is%20the%20problem%20all%20about?)
- [Application - Ramp](#Application%20-%20Ramp)
- [Problems](#Problems)
	- [54](#54)
	- [57 (incline + pulley)](#57%20(incline%20+%20pulley))
	- [58](#58)


# Force
- **Unit** = The acceleration a force would give to the standard kilogram
- Suppose we put a body on a horizontal, frictionless surface and pull horizontally such that the body has an acceleration of **1 $\text{m/s}^2$**. Then, we can define our applied force as 1 **newton (N)**
- If we pulled with a force magnitude of 2N, the acceleration would be 2 $\text{m/s}^2$
- **If the standard body of 1 kg has an acceleration of magnitude $a$, then the force (newtons) would equal $a$**

# Newton's First Law (Law of Inertial)
- If $\vec{F}_\text{net} = 0$, the body's velocity cannot change

# Inertial Reference Frames
- An inertial frame is a reference frame where Newton's laws hold true
- We can assume the ground is an inertial frame **provided we ignore the Earth's astronomical movement**
![](Pasted%20image%2020230630160153.png)

# Mass
- Acceleration is **inversely related** to mass
- We push on the standard body (1 kg) with 1N of force
	- Accel. of 1 $\text{m/s}^2$
- Push on body X with the same force
	- Accel. of $0.25\; \text{m/s}^2$

$$\frac{m_x}{m_0} = \frac{a_0}{a_x}$$

$$m_x = m_0 \frac{a_0}{a_x} = (1.0\;\text{kg})\frac{1.0\;\text{m/s}^2}{0.25\;\text{m/s}^2} = 4.0\;\text{kg}$$
- In this context, **the mass of a body is the characteristic that relates a force on the body to he resulting acceleration**


# Newton's Second Law
$$\vec{F}_{\text{net}} = m\vec{a}$$
- Similarly,
$$F_{\text{net, x}} = ma_x$$
$$F_{\text{net, y}} = ma_y$$
$$F_{\text{net, z}} = ma_z$$
- Accel. component along a given axis is caused **only by** the sum of the force components on the **same axis**

# Gravitational Force
- Assume ground is the inertial frame, $\vec{F}_g$ pulls the body directly towards the center of Earth
## Free fall
- Suppose mass $m$ is in **free fall** with free-fall acceleration of magnitude $g$. If we neglect air resistance, the only force acting on the body is $\vec{F}_g$.
$$F_g = mg$$
$$\vec{F}_g = -F_g\hat{j} = -mg\hat{j} = m\vec{g}$$

## Weight
$$W = mg$$

# Normal Force
- When a body presses against a surface, the surface deforms and pushes on the body with normal force $\vec{F}_N$ that is **perpendicular** to the surface
![](Pasted%20image%2020230704144320.png)
$$F_N = mg + ma_y = m(g + a_y)$$
$$F_N = mg$$
![](Pasted%20image%2020230704144622.png)
a) Magnitude of $\vec{F}_N$ is **equal** to $mg$
b) **Greater than** $mg$ because acceleration is upward; thus net force on body must be greater upward

# Tension
- When a cord is attached to a body and pulled **taut**, the cord pulls on the body with a force $\vec{T}$ directed **away** from the body and **along** the cord
- Tension in the cord has magnitude $T$ of force on the body
	- If $T = 50\;\text{N}$, then the tension in the cord is $50\;\text{N}$
![](Pasted%20image%2020230704144955.png)

# Newton's Third Law
- *When two bodies interact, the forces on the codes from each other are always equal in magnitude, and opposite in direction*
$$F_{BC} = F_{CB}$$
$$\vec{F}_{BC} = -\vec{F}_{CB}$$
- **Third-law force pair** = The pair of forces applied on two interacting objects
	- (Gravity of Sun on Earth, Gravity of Earth and Sun)

# Application - Pulleys
![](Pasted%20image%2020230705162855.png)
> Block $S$ with mass $M = 3.3\;\text{kg}$. The block is free to move along a horizontal frictionless surface and connected, by a cord that wraps around a frictionless pulley, to a second block $H$ with mass $m = 2.1\;\text{kg}$. Cord and pulley are massless. The hanging block $H$ falls as $S$ accelerates to the right. Find (a) the acceleration of $S$, (b) the acceleration of $H$, and (c) the tension in the cord

## What is the problem all about?
- Must consider the force of **Earth**
1. Cord pulls to the right on $S$ with force of magnitude $T$
2. Cord pulls upward on $H$ with force of magnitude $T$, counteracting free-fall
3. Earth pulls down on $S$ with gravitational force $\vec{F}_{gS}$, which has a magnitude equal to $Mg$
4. Earth pulls down on $H$ with gravitational force $\vec{F}_{gH}$ with magnitude $mg$
5. Table pushes up on $S$ with normal force
- Note that blocks will move together with the same magnitude of acceleration ($a$)
- Apply $\vec{F}_{\text{net}} = m\vec{a}$ on all bodies
- Draw free-body diagram for $S$

![](Pasted%20image%2020230705163611.png)
![](Pasted%20image%2020230705163624.png)

- How do we apply $\vec{F}_{\text{net}} = m\vec{a}$? to $S$?
- Split $\vec{F}_{\text{net}} = m\vec{a}$ into components
$$F_{\text{net, x}} = Ma_x$$
$$F_{\text{net, y}} = Ma_y$$
$$F_{\text{net, z}} = Ma_z$$

- Consider $S$. $S$ only moves along the $x$ axis, so
$$F_N - F_{gS} = 0 \to F_N = F_{gS}$$
- On the $x$ axis, there is only one force component, $T$.
Thus $F_{\text{net, x}} = Ma_x$ becomes
$$T = Ma$$

- How do we apply $\vec{F}_{\text{net}} = m\vec{a}$ to $H$?
- This time, acceleration is along the $y$ axis
$$T - F_{gH} = ma_y$$
$$T - mg = -ma$$
- Subtract $T = Ma$ and $T - mg = -ma$
$$a = \frac{m}{M+m}g$$
- Substitute
$$T = \frac{Mm}{M+m}g$$
- Plug in numbers
$$a = \frac{2.1}{3.3 + 2.1}(9.8) = 3.8\;\text{m/s}^2$$
$$T = \frac{(3.3)(2.1)}{3.3 + 2.1}(9.8) = 13\;\text{N}$$

# Application - Ramp
> A cord pulls a box of sea biscuits up along a frictionless plane inclined at $\theta = 30.0^{\circ}$. The box has mass $m = 5.00\;\text{kg}$, and the force from the cord has magnitude $T = 25.0\;\text{N}$. What is $a$ along the inclined plane?

![](Pasted%20image%2020230706165101.png)

- Tension force $\vec{T}$ has $T = 25.0 \;\text{N}$
- $\vec{F}_g$ is downward and has magnitude $mg = (5\;\text{kg})(9.8\;\text{m/s}^2) = 49.0\;\text{N}$

$$F_{\text{net, x}} = ma_x$$
- $\vec{T}$ is in the $+x$ direction and $mg \sin \theta$ is in the $-x$ direction?

$T - mg \sin \theta = ma$
$$25 - (5)(9.8) \cdot \sin 30^{\circ} = 5a$$
$$a \approx 0.1 \text{m/s}^2$$


# Problems
## 54
- If two bodies are connected by a taut rope or some other incompressible beam, you can treat the two bodies as one larger body
	- (i.e both bodies must have some velocity and acceleration)

## 57 (incline + pulley)
![](Pasted%20image%2020230706170911.png)

- $\theta = 30.0^{\circ}$
- $m_1 = 3.7\;\text{kg}$
- $m_2 = 2.3\;\text{kg}$

![](2023-07-06-Note-17-15.png)
## 58
![](2023-07-06-Note-17-29-2.png)