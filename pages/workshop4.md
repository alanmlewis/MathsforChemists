# Workshop 4: Quadratic and Simultaneous Equations
**Authors:** Lizzie Wheeldon and Alan M. Lewis

---

## Quadratic Equations

Lots of equations in chemistry and physics are quadratic: they include variables which are squared. Hooke's Law which describes springs (and approximately chemical bonds) is quadratic, and calculating equilibrium concentrations of acids usually involves solving a quadratic equation. Quadratic equations are written as:  

$$
f(x) = x^2 + bx + c = (x+A)(x+B)
$$  

Here the second form is called a factorised quadratic equation.

To solve a quadratic equation, we need to find the value(s) of $x$ where $f(x)=0$. The three main methods to do this are described in detail in Section 2.9 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.2.9), and are summarised here. It doesn't matter which method you use to solve a quadratic equation!

- **Completing the square**  
  
$$
  x^2 + bx + c = \left(x+\frac{b}{2}\right)^2 + c - b^2 = 0 \\
  \left(x+\frac{b}{2}\right)^2 = b^2 - c \\
  x = \pm \sqrt{b^2 - c} - \frac{b}{2}
  $$

- **Inspection (or factorisation)**  

  $$
  x^2 + bx + c = (x+A)(x+B) = 0; \qquad x = -A \text{ or } x = -B
  $$

- **Quadratic formula**  

  $$
  \text{If } ax^2 + bx + c = 0, \text{ then } x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
  $$

---

## Simultaneous Equations

Simultaneous equations are a set of multiple equations, each of which contain multiple unknown variables. As long as we have at least as many equations as variables, we can find the value of all of the variables. When we have 2 unknown variables, we can solve these sets of equations by substituting one equation into the other, or subtracting one equation from the other and rearranging until we find a value for one of the variables. We can then use that value to find the value of the other variable.

There are lots of examples of simultaneous equations and how they are used in chemistry in Section 2.7 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.2.7); we'll give one example of how simultaneous equations can provide important chemical information here. The Arrhenius equation  

$$
\ln k = \ln A - \frac{E_a}{RT}
$$  

describes how the rate of a reaction $k$ is determined by the temperature $T$, the activation energy of the reaction $E_a$, and a prefactor $A$ which describes how likely collisions between molecules are. In an experiment, the rate can be measured and the temperature controlled, but it's hard to directly measure $E_a$ or $A$. However, if two experiments are done at two different temperatures which give two different rates, that leaves two equations with two unknown variables:  

$$
\ln (4.75 \times 10^{-4}) = \ln A - \frac{E_a}{293R} \, (1); \quad
\ln (5.48 \times 10^{-2}) = \ln A - \frac{E_a}{333R} \, (2)
$$  

By subtracting (2) from (1), and doing a bit of rearranging, we can work out the value of $E_a$ and $A$:  

$$
E_a = 96.3 \text{ kJ mol}^{-1};  \qquad A = 6.95 \times 10^{13}.
$$

