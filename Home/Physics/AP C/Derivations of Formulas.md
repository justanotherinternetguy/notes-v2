- [1D Kinematics and Const. Accel.](#1D%20Kinematics%20and%20Const.%20Accel.)
- [$v = v_0 + at$](#$v%20=%20v_0%20+%20at$)
- [$x-x_0 = v_0t + \frac{1}{2}at^2$](#$x-x_0%20=%20v_0t%20+%20%5Cfrac%7B1%7D%7B2%7Dat%5E2$)
- [$v^2 = v_0^2 + 2a(x-x_0)$](#$v%5E2%20=%20v_0%5E2%20+%202a(x-x_0)$)


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
