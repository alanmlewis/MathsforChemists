# Workshop 7: Errors and Uncertainty  
**Authors:** Lizzie Wheeldon and Alan M. Lewis

---

For a more complete overview of errors, measurements and uncertainty, please refer to [the full notes](https://github.com/alanmlewis/MathsforChemists/raw/refs/heads/main/notes/EU_Handout_2024.docx).

---

## Error vs Uncertainty

Whenever we make some measurements, we need to ask two questions: are the measurements accurate, and are they precise? Or, to ask the same questions in a different way — how big is the error in the measurements, and how big is the uncertainty? Accurate measurements, or measurements with a low error, are very close to the “true” value. Precise measurements, or measurements with low uncertainty, are all very close to one another. Error is introduced by systematic bias, whereas uncertainty is introduced by random variation. Often in science, there is no way of measuring errors, because the “true” value of the measurement is unknown; however, any time we take multiple measurements, we can always measure how large the uncertainty in a measurement is.

---

## Reporting Uncertainty

Whenever we write down a measurement, we indicate the uncertainty in the measurement in one way or another.

- **Significant Figures:** the number of significant figures indicates the degree of precision of the measurement, as the true value could be any number which rounds to that number of significant figures. For example, if you measure a piece of string and report that it is 5.41 cm long, that means you are confident that your measurement is somewhere between 5.405 and 5.415 cm; if you report that the string is 5 cm long, the uncertainty is much larger, as the string could be anywhere from 4.5 to 5.5 cm long.  
- **Explicit Uncertainty:** Normally uncertainty is written as $x \pm \delta x$, where $\delta x$ is the uncertainty in the measurement. To make the implied uncertainty in the example above an explicit uncertainty instead, you could write that the length of the string is $5.41 \pm 0.005$ cm long.

---

## Measuring Uncertainty

The most common way of measuring the uncertainty in an experiment is to do it multiple times, and then work out the mean and standard error of the measurements. The mean value is the best estimate of the “true” value of the measurement, and the standard error in the mean (or just standard error) is the usual estimate of the uncertainty in the measurement. If $N$ experiments are performed, and each experiment produces a measurement $x_i$, then the mean $\bar{x}$ and standard error $\sigma_{\bar{x}}$ of the measurements are:  

$$
\text{mean} = \bar{x} = \frac{1}{N}\sum_i^N x_i, 
\qquad 
\text{standard error} = \sigma_{\bar{x}} 
= \frac{1}{\sqrt{N}}\sqrt{\frac{1}{N-1}\sum_i^N (x_i - \bar{x})^2}
$$  

Sometimes it is better to use the standard deviation or the variance as the estimate of the uncertainty:  

$$
\text{standard deviation} = \sigma_x 
= \sqrt{\frac{1}{N-1}\sum_i^N (x_i - \bar{x})^2};
\qquad
\text{variance} = \sigma_x^2 
= \frac{1}{N-1}\sum_i^N (x_i - \bar{x})^2
$$  

These three estimates are all related: the standard error is just the standard deviation divided by $\sqrt{N}$, and the variance is the square of the standard deviation. The most important difference between them is that the standard error gets smaller as the number of experiments $N$ increases, because it shows how precisely we know the mean value. However, standard deviation and variance don’t get smaller as $N$ increases: these estimate the random variation associated with a single measurement.

