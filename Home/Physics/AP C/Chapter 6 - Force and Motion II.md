- [Friction](#Friction)
	- [Static Friction](#Static%20Friction)
- [Properties](#Properties)
- [Angled force applied to a stationary block](#Angled%20force%20applied%20to%20a%20stationary%20block)
- [Downhill friction](#Downhill%20friction)


# Friction
## Static Friction
![](Pasted%20image%2020230706170424.png)
![](Pasted%20image%2020230706170441.png)![](Pasted%20image%2020230706174833.png)


# Properties
$$f_{\text{s, max}} = \mu_s F_N$$
- $\mu_s$ is the **coefficient of static fiction**
- If the magnitude of the force applied $\vec{F}$ that is parallel to the surface exceeds $f_{\text{s, max}}$, then the body begins to move
$$f_k = \mu_k F_N$$
# Angled force applied to a stationary block
> Force of $F = 12.0\;\text{N}$ is applied to an $8.00\;\text{kg}$ block at a downward angle of $\theta = 30^{\circ}$
> $\mu_s = 0.7$, $\mu_k = 0.4$
> Does the block begin to slide?
> What is the magnitude of the frictional force on the block?

- First, we need to compare $F_x$ against $f_{\text{s, max}}$

$$F_x = F \cos \theta = (12.0\;\text{N}) \cos 30^{\circ}  = 10.39\;\text{N}$$
- Next, find $F_N$ to find $f_{\text{s, max}}$
- Because $F_N$ is vertical, we need to write Newton's second law ($F_{\text{net, y}} = ma_y$) for the vertical force components acting on the block
	- $mg$
	- Applied force has downward component $F_y = F \sin \theta$
	- $a_y = 0$
$$F_N - mg - F \sin \theta = m(0)$$
$$F_N = mg + F \sin \theta$$
$$f_{\text{s, max}} = \mu_s (mg + F \sin \theta)$$$$= (0.7)((8.00\;\text{kg})(9.8\;\text{m/s}^2) + (12.0\;\text{N})(\sin 30^{\circ}))$$
$$\boxed{59.08\;\text{N}}$$

$$F_x < f_{\text{s, max}}$$
- Block stays still
- Magnitude of frictional force **acting on the block** is the **same** as the $F_x$
$$F_x - f_s = m(0)$$

# Downhill friction
![](Pasted%20image%2020230708101827.png)
> Car has initial speed of $10.0\;\text{m/s}$
> Normal horizontal road ($\mu_k = 0.6$)

- Frictional force is only force with an $x$ component...Newton's second law
$$-f_k = ma_x$$$$-\mu_k F_N = ma_x$$
$$-\mu_k mg = ma_x$$
$$-\mu_k g = a_x$$
- Constant-acceleration equations
$$v^2 = v_0^2 + 2a(x-x_0)$$
$$x-x_0 = \frac{v^2 - v_0^2}{2a_x}$$
$$x-x_0 = \frac{v^2 - v_0^2}{-2\mu_kg}$$
$$x-x_0 = \frac{0^2 - 10^2}{-2 \cdot 0.6 \cdot 9.8} \approx \boxed{8.5 \;\text{m}}$$



# Drag Force
- Air is the fluid
- Object is blunt
- Relative motion is fast enough that air behind gets turbulent
- Magnitude of drag force $\vec{D}$ is
	- $C$ is drag coefficient (typically ranges from 0.4-1.0)
	- $\rho$ is air density (mass per volume)
	- $A$ is **effective cross-sectional area** (area of cross section taken perpendicular from $\vec{v}$)
$$D = \frac{1}{2}C\rho A v^2$$


# Terminal Speed
$$v_t = \sqrt{\frac{2F_g}{C\rho A}}$$
- Any other equations can be derived

# Uniform Circular Motion
$$a = \frac{v^2}{R} \;\text{(centripetal acceleration)}$$
- A centripetal force accelerates a body by **changing the direction** of the velocity without changing the speed

$$F = m\frac{v^2}{R} \;\text{(magnitude of centripetal force)}$$
