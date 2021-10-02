## Conditions for Existence
**Fourier Transform** can exist for:

1. Energy Signals (they are integratable)
1. Power Signals
1. Impulse related Signals (exception: they are NENP signals but they have FT)

**Laplas Transform** can exist for:

1. Energy Signals
1. Power Signals
1. NENP (only up to some extent)

​

**Dirichlet Conditions**

1. Signal should have finite number of maxima and minima over any finite interval
1. Singal should have finitenumber of discontinuities over any finite interval
1. Signal should be absolutely **integrable**

​

### Representation
$$x(t) \rightleftharpoons X(j\omega)\ \text{or}\ X(f)$$
As for the $X(f)$, we could first calculate the $X(j\omega)$. Then, use the formula $\omega = 2\pi f$ to transfer to $X(f)$.
### Formula
#### Fourier Transform
$$x(t) \rightarrow X(j\omega) $$

$$X(j\omega) = \int_{-\infty}^{\infty} x(t) \cdot  e^{-j\omega t} dt$$
#### Inverse Fourier Transform
$$X(j\omega) \rightarrow x(t) $$
$$X(j\omega) = \frac{1}{2\pi}\int_{-infty}^{\infty} X(j\omega) \cdot e^{j\omega t} d\omega$$
Above two formulas only work for absolutely integratable signals.
#### Conversion of LT to FT
$$LT \xrightarrow{s=j\omega} FT$$
