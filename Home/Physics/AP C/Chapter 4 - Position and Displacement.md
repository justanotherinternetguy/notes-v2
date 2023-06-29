- [Position](#Position)
- [Displacement](#Displacement)
	- [Problem](#Problem)
		- [Solution](#Solution)
- [Average Velocity](#Average%20Velocity)
	- [Problem](#Problem)
		- [Solution](#Solution)
- [Inst. Velocity](#Inst.%20Velocity)
- [Average Accel.](#Average%20Accel.)
- [Inst. Accel](#Inst.%20Accel)
- [Projectile Motion](#Projectile%20Motion)
	- [Horizontal Analysis](#Horizontal%20Analysis)
	- [Vertical Analysis](#Vertical%20Analysis)
	- [Trajectory](#Trajectory)
	- [Horizontal Range](#Horizontal%20Range)
	- [Problem](#Problem)



# Position
- **Position** vector $\vec{r}$
	- Vector that extends from a reference point (origin) to particle
$$\vec{r} = x\hat{i} + y\hat{j} + z\hat{k}$$
- $x, y, z$ are scalar components


# Displacement
- **Displacement** vector $\Delta \vec{r}$
$$\Delta \vec{r} = \vec{r_2} - \vec{r_1}$$
$$\Delta \vec{r} = (x_2 - x_1) \hat{i} + (y_2 - y_1) \hat{j} + (z_2 - z_1) \hat{k}$$
$$\Delta \vec{r} = \Delta x\hat{i} + \Delta y \hat{j} + \Delta z \hat{k}$$

## Problem
> A rabbit runs across a parking lot. The coordinates (meters) of the rabbit's position as functions of time $t$ (seconds) are:
> $$x = -0.31t^2 + 7.2t + 28$$
> $$y = 0.22t^2 - 9.1t + 30$$
>At $t = 15$, what is the rabbit's position vector $\vec{r}$ in unit-vector and magnitude-angle notation?

### Solution
$$\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j}$$
![](Pasted%20image%2020230628010158.png)
	$$\boxed{\vec{r} = (66)\hat{i} - (57)\hat{j}}$$


# Average Velocity
- Average velocity = displacement/time interval
$$\vec{v_{avg}} = \frac{\Delta \vec{r}}{\Delta \vec{t}}$$
![](Pasted%20image%2020230628010309.png)

## Problem
> If a particle moves through displacement $(12)\hat{i} + (3)\hat{k}$ in $2$ s, what is the average velocity?

### Solution
$$\vec{v}_{\text{avg}} = \frac{\Delta \vec{r}}{\Delta t} = \frac{(12\;\text{m})\hat{i} + (3\;\text{m})\hat{k}}{2.0\;\text{s}} = \boxed{(6\; \text{m/s})\hat{i} + (1.5 \; \text{m/s})\hat{k}}$$


# Inst. Velocity
$$\vec{v} = \frac{d\vec{r}}{dt}$$
![](Pasted%20image%2020230628010811.png)
- The direction of the inst. velo $\vec{v}$ of a particle is **always tangent** to the particle's path at the given position
$$\vec{v} = \frac{d}{dt}(x\hat{i} + y\hat{j} + z\hat{k}) = \frac{dx}{dt}\hat{i} + \frac{dy}{dt}\hat{j}+\frac{dz}{dt}\hat{k}$$
$$\vec{v} = v_x\hat{i}+v_y\hat{j}+v_z\hat{k}$$
![](Pasted%20image%2020230629000145.png)

# Average Accel.
- When a particle's velocity changes from $\vec{v}_1$ to $\vec{v}_2$ in $\Delta t$, the **average acceleration** $\vec{a}_{\text{avg}}$ during $\Delta t$ is
$$\vec{a}_{\text{avg}} = \frac{\vec{v}_2 - \vec{v}_1}{\Delta t} = \frac{\Delta\vec{v}}{\Delta t}$$

# Inst. Accel
- We can shrink $\Delta t$ down to $0$...
$$\vec{a} = \frac{d\vec{v}}{dt}$$
- If velocity changes in **either** direction **or** magnitude, the particle **must have an acceleration**

$$\vec{a} = \frac{d}{dt}(v_x\hat{i} + v_y\hat{j} + v_z\hat{k}) = \frac{dv_x}{dt}\hat{i} + \frac{dv_y}{dt}\hat{j}+\frac{dv_z}{dt}\hat{k}$$

$$\vec{a} = a_x\hat{i}+a_y\hat{j}+a_z\hat{k}$$

![](Pasted%20image%2020230629000711.png)

# Projectile Motion
- Acceleration is **always** gravity $\vec{g}$
- Assume no air resistance
- Horizontal and Vertical motion will **always** be independent of each other
- **NO acceleration** horizontally

- Path of a projectile launched at $\vec{v}_0$ is...
$$\vec{v}_0 = v_{0x}\hat{i} + v_{0y} \hat{j}$$
- Components can be found if we know the angle $\theta_0$ between $\vec{v}_0$ and the positive $x$ direction

$$v_{0x} = v_0 \cos \theta_0$$
$$v_{0y} = v_0 \sin \theta_0$$

## Horizontal Analysis
- At any time $t$, the proj's **horizontal displacement** $x-x_0$ from initial position $x_0$ is...
$$x-x_0 = v_{0x}t$$
- B/c $v_{0x} = v_0 \cos \theta_0$
$$x - x_0 = (v_0 \cos \theta_0)t$$

## Vertical Analysis
$$g = 9.8 \;\text{m/s}^2$$

- Substitute $-g$ for $a$ in 1D kinematic equations

$$y-y_0 = v_{0y}t - \frac{1}{2}gt^2 = \boxed{(v_0 \sin \theta_0)t - \frac{1}{2}gt^2}$$

- Similarly,
$$v_y = v_0 \sin \theta_0 - gt$$
$$v_y^2 = (v_0 \sin \theta_0)^2 - 2g(y - y_0)$$
- When magnitude of vertical velocity component = 0, the proj reaches the maximum height


## Trajectory
- Find the equation of the trajectory by eliminating time $t$
$$y = (\tan \theta_0) x - \frac{gx^2}{2(v_0 \cos \theta_0)^2}$$
- Parabolic

## Horizontal Range
- Horizontal distance the projectile has traveled when it returns to its **initial height**
- To find range $R$, put $x-x_0 = R$ in horizontal motion eq.
- Put $y-y_0 = 0$ in vertical motion rq.
$$R = (v_0 \cos \theta_0)t$$
$$0 = (v_0 \sin \theta_0)t - \frac{1}{2}gt^2$$
- Eliminating $t$ yields...
$$R = \frac{2v_0^2}{g} \sin \theta_0 \cos \theta_0$$
- Use identity $2\theta_0 = 2 \sin \theta_0 \cos \theta_0$
$$R = \frac{v_0^2}{g}\sin 2\theta_0$$
- $R$ will **always** be at max when $\theta_0 = 45^{\circ}$
	- This is b/c the above equation will be at max when $\sin 2\theta_0 = 1$, $\to$ $2\theta_0 = 90^{\circ}$

## Problem
> A rescue plane flies at 198 km/h (55.0 m/s) at a constant height h=500m towards a point directly over a victim, where a rescue capsule is to land.
> What should be the angle $\phi$ of the pilot's line of sight to the victim when the capsule is released?

![](Pasted%20image%2020230629142340.png)

- Once released, the capsule will be a projectile
	- We need to separately consider the horizontal and vertical motion (do not need to consider the actual curved path)

- From the diagram:
$$\phi = \tan^{-1} \frac{x}{h}$$
- We already know $h = 500$, so we need to find $x$ (which is the horizontal coordinate of the victim (and of the capsule when it lands))
$$x - x_0 = (v_0 \cos \theta_0) t$$
- $x_0 = 0$ (origin)
- $\vec{v}_0 = \text{plane's velocity}$
	- $v_0 = 55$ m/s
	- $\theta_0 = 0^{\circ}$
- We do not know time $t$
- To find $t$, we consider **vertical motion**

$$y - y_0 = (v_0 \sin \theta_0)t - \frac{1}{2}gt^2$$
- $y-y_0$ of the capsule is -500m (capsule will fall downward 500m to the ground)

$$-500 = (55.0\;\text{m/s}) (\sin \\0^{\circ})t - \frac{1}{2}(9.8 \; \text{m/s}^2)t^2$$

$$t = 10.1\;\text{s}$$
- Plug $t$ back
$$x - 0 = (55.0\;\text{m/s})(\cos 0^{\circ})(10.1\;\text{s})$$
$$x = 555.5\;\text{m}$$
- Finally,
$$\phi = \tan^{-1}\frac{555}{500} = 48.0^{\circ}$$
> As the capsule reaches the water, what is its velocity $\vec{v}$?
- $v_x$ will not change from $v_{0x}$ because there **is no horizontal acceleration**
$$v_x = 55.0 \;\text{m}$$
$$v_y = v_0 \sin \theta_0 - gt = (55.0)(\sin 0^{\circ}) - (9.8 \;\text{m/s}^2)(10.1) = -99.0 \;\text{m/s}$$
- At the water,
$$\vec{v} = (55)\hat{i} - (99)\hat{j}$$
$$v = \sqrt{55^2 + (-99)^2} \approx \boxed{113.25 \;\text{m/s}}$$
$$\theta = \tan^{-1}(\frac{-99}{55}) = \boxed{-60.95^{\circ}}$$
