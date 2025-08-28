# Workshop 3: Logarithms, Exponentials, Trigonometric Identities
**Authors:** Lizzie Wheeldon and Alan M. Lewis

---

## Exponential functions

Exponential functions combine two things we've seen elsewhere: they are functions in which one of the variables is a power. $y = a^x$ is an exponential function. We can use the same rules for manipulating powers to manipulate exponential functions. They are discussed in more detail in section 2.4 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.2.4).

There is a particular type of exponential function which is very common, and very important, and so it is called "The Exponential Function". This is when $a$ is equal to a particular value called $e$:  

$$
e = 2.718281 \cdots
$$

Just like $\pi$, $e$ is just a name we give to a specific number. That number is "transcendental" - it goes on forever, and can't be written as a fraction. The reason the exponential function $y = e^x$ is important is because when you differentiate it, you get the same function again - we'll talk about this more in a later workshop.

---

## Logarithms

Logarithms are the inverse of exponential functions. They answer the question "how many times do we have multiply $a$ by itself to get $y$"? Or, mathematically, if $y = a^x$, then $x = \log_a(y)$. For example, $\log_{10}(1000)=3$, because $10^3 = 1000$. Logarithms can have any "base" (constant $a$), but they are almost always used with a base of either 10 or $e$. If you see $\log(x)$ with no base $a$ given, that almost certainly means $\log_{10}(x)$; $\ln(x)$ is the same as the logarithm with base $e$: $\ln(x) = \log_e(x)$. Logarithms are discussed in more detail in section 2.5 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.2.5). There are four main laws which we can use to manipulate logarithms:

1. $\log_a (a^{x}) = x$  
2. $\log_a(x\times y) = \log_a(x) + \log_a(y)$  
3. $\log_a\left(\frac{x}{y}\right) = \log_a(x) - \log_a(y)$  
4. $\log_a(x^b) = b\times \log_a(x)$  

---

## Trigonometric Identities

A thorough discussion of trigonometry is found in Section 3.2 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.3.2); here we just summarise the key equations and identities you might need.

- Angles can be written in degrees ($^\circ$) or radians; these are just different units for angles. There are 360$^\circ$ or 2$\pi$ radians in a circle.  

- In a right angled triangle, trigonometric functions are given by the ratios of the lengths of its sides:  

$$
\sin{\theta} = \frac{\text{Opposite}}{\text{Hypotenuse}}; \quad 
\cos{\theta} = \frac{\text{Adjacent}}{\text{Hypotenuse}}; \quad 
\tan{\theta} = \frac{\text{Opposite}}{\text{Adjacent}} = \frac{\sin{\theta}}{\cos{\theta}}
$$

- In a right angled triangle, the square of the length of the longest side is equal to the sum of the square of the lengths of the other two sides (this is called Pythagoras's Theorem):  

$$
\text{Hypotenuse}^2 = \text{Opposite}^2 + \text{Adjacent}^2
$$

- All trigonometric functions have an inverse:  

$$
\sin^{-1} \left(\sin{\theta}\right) = \theta; \quad 
\cos^{-1} \left(\cos{\theta}\right) = \theta; \quad 
\tan^{-1} \left(\tan{\theta}\right) = \theta
$$

- We write the square of trigonometric functions as follows: $\left( \sin{\theta}\right)^2 = \sin^2{\theta}$.

- There is a special relationship between the square of sin and cosine functions:  
$\sin^2{\theta} + \cos^2{\theta} = 1$.

