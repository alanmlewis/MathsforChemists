# Workshop 1: Fractions, Powers and Inequalities
**Authors:** Lizzie Wheeldon and Alan M. Lewis

---

## Non-Integer Numbers

There are three usual ways of writing numbers which are not integers (whole numbers): fractions, percentages and decimals. For more details about how to handle these numbers and examples of how they are used in Chemistry, see sections 1.3, 1.4 and 1.5 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.1.3).

### Fractions
- Fractions can be thought of as the ratio between two numbers, or simply as the result of dividing one number by another:  
  $$
  \frac{a}{b} \equiv a \div b
  $$
- Fractions can be multiplied by multiplying the numerators and denominators. Division is the inverse of multiplication, and so dividing by a fraction is the same as multiplying by the inverse of that fraction:  
  $$
  \frac{a}{b} \times \frac{c}{d}  = \frac{ a \times c}{b \times d}; \qquad \frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \times \frac{d}{c} = \frac{ a \times d} {b \times c}
  $$
- Fractions can only be added or subtracted if they have the same denominator. To change the denominator of a fraction, multiply the numerator and denominator by the same amount (this is the same as multiplying by 1, which does not change the number). For example:  
  $$
  \frac{2}{7} - \frac{3}{5} = \left(\frac{2}{7} \times \frac{5}{5} \right)- \left(\frac{3}{5} \times \frac{7}{7}\right) = \frac{10}{35} - \frac{21}{35} = \frac{-11}{35}
  $$

### Percentages
- Percentages are numbers which are fractions of 100:  
  $$
  x \% = \frac{x}{100}
  $$
- Any fraction can be written as a percentage:  
  $$
  \frac{a}{b} = (a \div b \times 100) \%
  $$
- The percentage of a quantity is calculated by:  
  $$
  x\% \ \text{of} \ y = x \times y \div 100
  $$

### Decimals
- Many fractions cannot be written exactly as decimals (e.g $\frac{1}{6} = 0.166666\cdots$).
- Decimals should be rounded to a certain number of decimal places (d.p., numbers after the decimal point) or significant figures (s.f., numbers after the first number which is not zero). For example, 0.00123456 to 4 s.f. is 0.001234, and to 4 d.p. is 0.0012.

---

## Powers

Below is a summary of the key rules for understanding and manipulating powers. More details about powers and examples of how they are used in Chemistry are in sections 2.1 of the [Maths for Chemists document](https://edu.rsc.org/download?ac=15395#subsection.2.1).

- $x^n = x \times x \times x \cdots (n \text{ times})$
- $x^{-n} = \frac{1}{x^n}$
- $\sqrt{x} = x^{1/2}$
- $\sqrt[3]{x} = x^{1/3}$
- $x^a \times x^b = x^{(a+b)}$
- $\frac{x^a}{x^b} = x^{(a-b)}$
- $(x^a)^b = x^{a \times b}$

---

## Inequalities

Inequalities indicate when some information about a variable is known, but it cannot be specified precisely. The four most common inequalities are greater than ($>$), less than ($<$), greater than or equal to ($\geq$), and less than or equal to ($\leq$). The difference between these pairs is whether the limit is an allowed value of the variable:
- If $x > 3$, then $x$ can be any value greater than 3, but not equal to 3;
- If $x \geq 3$, then $x=3$ is also an allowed value of $x$.

We can also write two different inequalities for a single variable:  
$$
0 < x < 1
$$
means that x must be between 0 and 1, and cannot be equal to either zero or 1.

We can also use inequalities to show when one variable is much larger than another, using $\gg$ or $\ll$. These are usually used to show that the smaller of these numbers can effectively be ignored for the particular calculation we are doing, especially if those two numbers are going to be added together. For example, imagine we want to calculate the force which acts on a bowling ball when it falls under gravity. We can use the equation  
$$
F=ma
$$
and we know the mass of the bowling ball is $m=7.3$ kg, and that acceleration under gravity on earth is $a=9.8$ m s$^{-2}$, so the force acting on the ball must be  
$$
F = ma = 7.3\text{ kg} \times 9.8\text{ m s}^{-2} = 71.5 \text{ N}
$$
Now imagine sticking a piece of chewing gum to the bowling ball, and redoing the calculation. Now we will call the mass of the bowling ball $m_1$, and the mass of the chewing gum $m_2$, so the total mass is $m = m_1 + m_2$. But the chewing gum is much lighter than the bowling ball ($m_2 \ll m_1$), so we can say that the total weight is approximately the same as the weight of the bowling ball:  
$$
m = m_1 + m_2 \approx m_1
$$
Therefore the force acting on the bowling ball must be approximately the same as before the chewing gum was stuck to it. Check for yourself how different the force will be if the chewing gum weighs 1 g. Whether this difference matters will depend on the type of experiment we are trying to do.
