# Summary
Accuracy of using size-at-age data to estimate fish consumption rates (quantity of fish consumed for a given time interval). Fit the VBGF to bluefin tuna (*Thunnus thynnus*) and yellowfin tuna (*Thunnus albacares*). 

* growth rate (dW/dt; mass*time^{-1}) = rates of energy input and energy expenditure, which are both weight specific. 

$$
\frac{dW_t}{dt} = HW_t^d - kW_t^n \\
$$

$W_t$ = weight at age $t$ (years)

$kW_t^n$ = energy loss

$d$ = allometric scaling of consumption 

$n$ = allometric scaling of energy costs, where von Bertalanffy (@vonbertalanffy_1938) assumed $n = 1$; standard metabolism rates suggest that $n$ should be closer to 0.8, but if so then there is no closed form solution to the integral of the rate equation and standard metabolism does not account for other energy costs (e.g., swimming, reproduction).