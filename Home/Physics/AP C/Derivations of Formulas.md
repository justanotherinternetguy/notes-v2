- [1D Kinematics and Const. Accel.](#1D%20Kinematics%20and%20Const.%20Accel.)
- [$v = v_0 + at$](#$v%20=%20v_0%20+%20at$)
- [$x-x_0 = v_0t + \frac{1}{2}at^2$](#$x-x_0%20=%20v_0t%20+%20%5Cfrac%7B1%7D%7B2%7Dat%5E2$)
- [$v^2 = v_0^2 + 2a(x-x_0)$](#$v%5E2%20=%20v_0%5E2%20+%202a(x-x_0)$)
- [Projectile Motion](#Projectile%20Motion)
	- [Horizontal Motion](#Horizontal%20Motion)
	- [Vertical Motion](#Vertical%20Motion)
	- [Trajectory](#Trajectory)
	- [Range](#Range)
- [Uniform Circular Motion](#Uniform%20Circular%20Motion)
	- [Centripetal Acceleration](#Centripetal%20Acceleration)
- [Gravity ($\vec{F}_g$)](#Gravity%20($%5Cvec%7BF%7D_g$))
- [Normal Force ($F_N$)](#Normal%20Force%20($F_N$))


# 1D Kinematics and Const. Accel.
- $x-x_0$
- $v$
- $t$
- $a$
- $v_0$
# $v = v_0 + at$
$$a = a_{\text{avg}} = \frac{v-v_0}{t-0}$$
$$a(t-0) = v-v_0$$
$$at = v - v_0$$
$$\boxed{at + v_0 = v}$$
-----

# $x-x_0 = v_0t + \frac{1}{2}at^2$
$$\bar{v} = \frac{x-x_0}{t-0}$$
$$\bar{v}(t-0) = x-x_0$$
$$\vec{v}t+x_0 = x$$
-----
$$\bar{v} = \frac{v_0 + v}{2}\;\text{(definition of average)}$$

-----
- Substitute
$$x = x_0 + (\frac{v_0 + v}{2})t$$
$$= x_0 + (\frac{v_0  + v_0 + at}{2})t$$
$$x = x_0 + v_0t + \frac{1}{2}at^2$$
-----

# $v^2 = v_0^2 + 2a(x-x_0)$
$$\bar{v} = \frac{v+v_0}{2}$$
- Substitute into $x=x_0+\bar{v}t$
$$x = x_0 + (\frac{v+v_0}{2})t$$
-----
$$v = v_0 + at$$
$$v-v_0 = at$$
$$t = \frac{v-v_0}{a}$$
- Substitute into previous
$$x = x_0 + (\frac{v+v_0}{2}) \cdot (\frac{v-v_0}{a})$$
$$x= x_0 + \frac{v^2 - v_0^2}{2a}$$
- Solve for $v^2$
$$x - x_0 = \frac{v^2 - v_0^2}{2a}$$
$$2a(x - x_0) = v^2 - v_0^2$$
$$\boxed{2a(x-x_0) + v_0^2 = v^2}$$
-----
# Projectile Motion
$$\boxed{v_{x0} = v_0\cos\theta_0}$$
$$\boxed{v_{y0} = v_0 \sin \theta_0}$$

## Horizontal Motion
$$x-x_0 = v_{0x}t$$
$$v_{0x} = v_0 \cos \theta_0$$
$$\boxed{x-x_0 = (v_0 \cos \theta_0)t}$$
-----
## Vertical Motion
$$a = -g$$
- Use [$x-x_0 = v_0t + \frac{1}{2}at^2$](#$x-x_0%20=%20v_0t%20+%20%5Cfrac%7B1%7D%7B2%7Dat%5E2$)
$$y - y_0 = v_{0y}t - \frac{1}{2}gt^2$$
$$\boxed{y-y_0 = (v_0 \sin \theta_0)t - \frac{1}{2}gt^2}$$
- Similarly $v = v_0 + at$ becomes
$$\boxed{v_y = v_0 \sin \theta_0 - gt}$$
$$\boxed{v_y^2 = (v_0 \sin \theta_0)^2 - 2g(y-y_0)}$$
-----
## Trajectory
$$y = (\tan \theta_0)x - \frac{gx^2}{2(v_0 \cos \theta_0)^2}$$
- Derivation TBA
-----
## Range
- From [$x-x_0 = v_0t + \frac{1}{2}at^2$](#$x-x_0%20=%20v_0t%20+%20%5Cfrac%7B1%7D%7B2%7Dat%5E2$)
$$y = y_0 + v_{y0}t + \frac{1}{2}a_yt^2$$
- At the farthest range, the projectile is on the ground
$$0 = 0 + v_{y0}t - \frac{1}{2}gt^2$$
- Solve for $t$
$$t = \frac{2v_{y0}}{g}$$
-----
$$R = x = v_{x0}t$$
$$R = v_{x0}(\frac{2v_{y0}}{g}) = \frac{2v_{x0}v_{y0}}{g} = \frac{2v_0^2\sin\theta_0\cos\theta_0}{g}$$
$$2 \sin\theta\cos\theta = \sin 2 \theta$$
$$\boxed{R = \frac{v_0^2 \sin 2\theta_0}{g}}$$

# Uniform Circular Motion

## Centripetal Acceleration
$$a = \frac{v^2}{r}$$
- Particle $p$ moves at a constant speed $v$ around a circle with radius $r$
- $p$ has coordinates $x_p$ and $y_p$
- $\vec{v}$ of a moving particle is always tangent to the particle's path at the particle's position
- Angle $\theta$ that $\vec{v}$ makes with a vertical at $p$ **equals** the angle $\theta$ that radius $r$ makes with the $x$ axis
![](Pasted%20image%2020230712203536.png)
- The scalar components of $\vec{v}$ can be written as

$$\vec{v} = v_x \hat{i} + v_y \hat{j} = (-v \sin \theta)\hat{i} + (v \cos \theta) \hat{j}$$
![](Pasted%20image%2020230712204142.png)
- Replace $\sin$ and $\cos$ with $y_p/r$ and $x_p/r$ (we defined that the two $\theta$s are equal)
$$\vec{v} = (-\frac{vy_p}{r})\hat{i} + (\frac{vx_p}{r})\hat{j}$$
- To find acceleration $\vec{a}$, we must take $dt$ of the equation (time derivative)
- $v$ (speed) and $r$ do not change with time
$$\vec{a} = \frac{d\vec{v}}{dt} = (-\frac{v}{r}\frac{dy_p}{dt})\hat{i} + (\frac{v}{r} \frac{dx_p}{dt})$$
- The rate ${dy_p}/dt$ at which $y_p$ changes is **equal** to the velocity component $v_y$

$$\frac{dy_p}{dt} = v_y$$
$$\frac{dx_p}{dt} = v_x$$

$$v_x = -v \sin \theta$$
$$v_y = v \cos \theta$$
- Substitute
$$\vec{a} = (-\frac{v^2}{r} \cos \theta) + (-\frac{v^2}{r} \sin \theta)\hat{j}$$
![](Pasted%20image%2020230712204823.png)

$$\boxed{a = \sqrt{a_x^2 + a_y^2} = \frac{v^2}{r} \sqrt{(\cos \theta)^2 + (\sin \theta)^2} = \frac{v^2}{r} \sqrt{1} = \frac{v^2}{r}}$$
$$\tan \phi = \frac{a_y}{a_x} = \frac{-(v^2/r)\sin\theta}{-(v^2/r)\cos\theta} = \tan \theta$$


- https://physicsteacher.blog/2022/05/15/deriving-centripetal-acceleration/

$$T = \frac{2\pi r}{v} \;\text{(period)}$$

# Gravity ($\vec{F}_g$)
- Neglect effects of the air
- Only force acting on a particle in free-fall is $\vec{F}_g$
- Use Newton's 2nd law, position $y$ is upward
$$F_{\text{net, y}} = ma_y$$
$$-\vec{F}_g = m(-g)$$
$$F_g = mg$$
$$\vec{F}_g = m\vec{g}$$
$$W = F_g = mg$$

# Normal Force ($F_N$)
$$F_N - F_g = ma_y$$
$$F_N - mg = ma_y$$
$$F_N = mg + ma_y = m(g + a_y)$$

![](Pasted%20image%2020230712210648.png)
- If table and block are not accelerating relative to the ground, $a_y = 0$ and
$$F_N = mg$$
- However, if the table + block are in an elevator moving upward **at a constant speed**,
	- $F_N$ would still be equal to $mg$ because $a_y$ is not changing
- **HOWEVER**, if the table + block are in an elevator moving upward **at an increasing speed**,
	- $F_N$ would be greater than $mg$ because $a_y$ is now **positive**

# Tension
![](Pasted%20image%2020230713171036.png)


# Friction
## Static Friction (Nonmoving)


# Kinetic Energy
- Assume constant acceleration
$$K = \frac{1}{2}mv^2$$
-----
- Start from **work-energy theorem**
- *The principle of work and kinetic energy (also known as the work-energy theorem) states that the work done by the sum of all forces acting on a particle equals the change in the kinetic energy of the particle*
- $W$ = Work
- $\Delta x$ = Displacement

$$\Delta K = W = F \Delta x - ma \Delta x$$
- Rearrange [$v^2 = v_0^2 + 2a(x-x_0)$](#$v%5E2%20=%20v_0%5E2%20+%202a(x-x_0)$)
$$a \Delta s = \frac{v^2 - v_0^2}{2}$$
$$\Delta K = m(\frac{v^2-v_0^2}{2})$$
$$\Delta K = \frac{1}{2}mv^2 - \frac{1}{2}mv_0^2$$
- $v_0$ = 0
$$K = \frac{1}{2}mv^2$$

# Work
- Consider a bead that can slide along a frictionless wire that is stretched along the $x$ axis
- A constant $\vec{F}$, directed at angle $\phi$, accelerates the bead along the wire
$$F_x = ma_x$$
- As the bead moves through displacement $\vec{d}$, the  force changes the bead's velocity from $\vec{v}_0$ to $\vec{v}$.

- Constraints
	- Force is constant
	- Accel. is constant
	- Object is rigid (everything moves together)


$$v^2 = v_0^2 + 2a_xd$$
$$v^2 - v_0^2 = 2a_xd$$
$$\frac{v^2 - v_0^2}{2d} = a_x$$

- Substitute into $F_x = ma_x$

$$F_x = m(\frac{v^2 - v_0^2}{2d})$$
$$F_x = \frac{mv^2}{2d} - \frac{mv_0^2}{2d}$$
$$F_xd = \frac{mv^2}{2} - \frac{mv_0^2}{2}$$
$$F_xd = \frac{1}{2}mv^2 - \frac{1}{2}mv_0^2$$
- This tells us that the kinetic energy has been changed by $\vec{F}$, so...
$$W = F_xd$$
- If we know $F_x$ and $d$, we can calculate $W$
$$F_x = F \cos \phi$$
$$\boxed{W = Fd \cos \phi}$$
![](Pasted%20image%2020230713201521.png)
- Also can write this with the dot product
$$W = \vec{F} \cdot \vec{d}$$
- When using $\vec{F}_{\text{net}}$
	- Substitute the magnitude $F_{\text{net}}$ for $F$
	- Substitute the angle between the direction of $\vec{F}_\text{net}$ and $\vec{d}$ for $\phi$