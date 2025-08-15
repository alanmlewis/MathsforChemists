# Workshop 9: Integration
**Authors:** Lizzie Wheeldon and Alan M. Lewis

If integration is new for you, Section 5 in the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#section.5) gives a good introduction. For those who have learnt about integration before, this summary intends to remind you of the key points.

---

## What is Integration?

There are two ways to think about integration. The first is that it is the reverse of differentiation: it answers the question “if this is the gradient of the function, what is the original function?” We write that as:

$$
\int f^\prime(x) \,\mathrm{d}x = f(x) + C, \quad \text{or} \quad \int \frac{\mathrm{d}y}{\mathrm{d}x} \,\mathrm{d}x = y + C
$$

The $x$ in the symbol $\mathrm{d}x$ tells us which variable we are integrating. Note that when we integrate we have to add a unknown constant $C$ to the answer. This is because adding a constant to a function doesn’t change its gradient, so there are lots of different functions which have the same gradient. For example, $x^2$ has the same gradient as $x^2 + 10$. When we integrate a gradient to get back to the function, we don’t know which of those functions we want, so we have to add an unknown constant to show that.

The second way of thinking about integration is that it tells us the area between a function and the $x$ axis between two values of $x$, which we call $a$ and $b$. We write this as

$$
\int_a^b f(x) \,\mathrm{d}x = F(b) - F(a),
$$

where $F(x)$ is the function we get from integrating $f(x)$. This is called definite integration, and the result is a number, not a function.

---

## Rules for Integration

- $\int ax^n \,\mathrm{d}x = \frac{a}{n+1}x^{n+1} + C$
- $\int a \,\mathrm{d}x = ax + C$
- $\int a\sin(bx) \,\mathrm{d}x = \frac{-a}{b}\cos(bx) + C$
- $\int a\cos(bx) \,\mathrm{d}x = \frac{a}{b}\sin(bx) + C$
- $\int ae^{bx} \,\mathrm{d}x = \frac{a}{b}e^{bx} + C$
- $\int \frac{a}{x} \,\mathrm{d}x = a\ln(x) + C$

---

## Examples of Definite Integration

One example of how we can use definite integration is to calculate how much work we need to do to compress a spring. The general formula for work is

$$
W = \int_a^b F(x)\,\mathrm{d}x.
$$

where $F(x)$ is the force applied to change $x$. For a spring, the force is $F(x) = k(x-x_0)$, where $k$ is the spring constant, $x$ is the length of the spring, and $x_0$ is the length of the spring when it’s not stretched or squashed. For a $x_0 = 5\ \text{mm}$ spring with $k = 2\ \text{N mm}^{-1}$, the work done to stretch the string from 5 mm to 7 mm is:

$$
W = \int_5^7 F(x)\,\mathrm{d}x 
= \int_5^7 k(x-x_0)\,\mathrm{d}x 
= \left[ \frac{1}{2}kx^2 - kx_0x\right]_5^7
$$

We’ve used square brackets $[\cdots]_a^b$ to show that we will evaluate the function we’ve just integrated between the limits $a$ and $b$. Inserting all of the constants into the equation gives:

$$
W = (\tfrac{1}{2}\times2\times7^2 - 2\times7\times5) 
- (\tfrac{1}{2}\times2\times5^2 - 2\times5\times5) 
= -21 + 25 = 4\ \text{N mm}
$$

We can choose these limits to be any values: the work done by stretching the string from 7 mm to 9 mm is:

$$
W = \int_7^9 F(x)\,\mathrm{d}x 
= (\tfrac{1}{2}\times2\times9^2 - 2\times9\times5) 
- (\tfrac{1}{2}\times2\times7^2 - 2\times7\times5) 
= 12\ \text{N mm}.
$$

This answer makes physical sense — it take more work to stretch a spring 2 mm when it is already stretched.

