# Derivatives
$$f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}$$

#### Differentiability implies continuity
- Let $f(x)$ be a function and $a$ be in its domain. If $f(x)$ is differentiable at $a$, then $f$ is continuous at $a$
- However, a continuous function does not imply differentiability

#### Higher order derivs.
$$f^{(n)}(x)$$
$$\frac{d^ny}{dx^n}$$

## Deriv rules

#### Constant Rule
- Let $c$ be a constant
- If $f(x) = c$, then $f'(c) = 0$

$$\frac{d}{dx}(c) = 0$$

#### Power Rule
- If $n$ be a positive integer. If $f(x) = x^n$, then...
$$f'(x) = nx^{n-1}$$

- Let $f(x)$ and $g(x)$ be differentiable functions and $k$ be a constant
#### Sum Rule

$$\frac{d}{dx} (f(x) + g(x)) = \frac{d}{dx}(f(x)) + \frac{d}{dx}(g(x))$$

#### Difference Rule

$$\frac{d}{dx} (f(x) - g(x)) = \frac{d}{dx}(f(x)) - \frac{d}{dx}(g(x))$$
 

#### Constant Multiple Rule
$$\frac{d}{dx}(kf(x)) = k \frac{d}{dx}(f(x))$$

#### Product Rule
$$\frac{d}{dx} (f(x) g(x)) = \frac{d}{dx}(f(x)) \cdot g(x) + \frac{d}{dx}(g(x)) \cdot f(x)$$

#### Quotient Rule

$$\frac{d}{dx} (\frac{f(x)}{g(x)}) = \frac{\frac{d}{dx}(f(x)) \cdot g(x) - \frac{d}{dx}(g(x)) \cdot f(x)}{(g(x))^2}$$

#### Ext. Power Rule
- If $k$ is a negative integer...
$$\frac{d}{dx}(x^k) = kx^{k-1}$$

#### Common Derivatives
$$\frac{d}{dx}(cx) = c$$
$$\frac{d}{dx}(x^n) = nx^{n-1}$$
$$\frac{d}{dx} = nc^{n-1}$$

#### Chain Rule
$$\frac{d}{dx}(f(g(x))) = f'(g(x)) \cdot g'(x)$$

#### L'Hopital's Rule
- If $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{0}{0}$ or $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\pm \infty}{\pm \infty}$:

$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}$$

## Derivs as Rates of Change

- The **amount of change** of $f(x)$ over the interval $h$ is given by:
$$f(a + h) - f(a)$$

- **Average rate of change** is given by:

$$\frac{f(a + h) - f(a)}{h}$$
- **Instantaneous rate of change** is given by:

$$f'(a) = \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}$$

- For small enough values of $h$, $f'(a) \approx \frac{f(a + h) - f(a)}{h}$.
	- We can solve for $f(a + h)$ to get the amount of change:
$$f(a + h) \approx f(a) = f'(a)h$$
![](Pasted%20image%2020230428202915.png)

#### Population Change
- If $P(t)$ is the number of entities present in a population, then the population growth rate of $P(t)$ is defined to be $P'(t)$

#### Changes in Cost and Revenue
- If $C(x)$ is the cost of producing $x$ items, then the **marginal cost** $MC(x)$ is $MC(x) = C'(x)$
- If $R(x)$ is the revenue obtained by selling $x$ items, then the **marginal revenue** $MR(x)$ is $MR(x) = R'(x)$
- If $P(x) = R(x) - C(x)$ is the profit obtained from selling $x$ items, then the **marginal profit** $MP(x)$ is $MP(x) = P'(x) = MR(X) - MC(x) = R'(X) - C'(x)$
