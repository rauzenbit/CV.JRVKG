# CV.JRVKG
My first ever science project. Calculations of Doppler factor, Lorentz factor and viewing angle of 0851+202

1st Cell: fit a coefficient in quadratic $y = ax^2$ model with curve_fit and plot data and model.

2nd Cell: fit a, b, c coefficients in non-linear $y = a e^{−b} \sin(x) + c x$ model with curve_fit and plot data and model.

3rd Cell: sum of n Gaussians: $y = \sum_{i=0}^{n-1} a_i * exp{-((x - b_i)/c_i)^2}$. Fit 3n parameters $(a_i, b_i, c_i)$, plot data and model.

4th Cell: modeling light curves as exponential flares and compute Doppler factor $D_{var}$

5th Cell is lost: Lorentz factor and viewing angle were calculated using the following equations $Γ_{var} = \frac{β_{app}^2 + D_{var}^2 + 1}{2D_{var}}$ and $θ_{var} = \arctan{ \frac{2β_{app}}{β_{app}^2 + D_{var}^2 − 1}}$
