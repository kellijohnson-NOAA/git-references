# Summary
Accuracy of using size-at-age data to estimate fish consumption rates (quantity of fish consumed for a given time interval). Wanted to test the assumptions that scaling of energy expenditures ($n$) are linear (i.e., equal 1) and the allometric scaling of consumption is close to $2/3$. Allometric scaling of consumption is assumed to be $2/3$ in the specialized VBGF compared to unity in the generalized VBGF. Fit the VBGF to simulated data and real data from bluefin tuna (*Thunnus thynnus*, length-at-age) and yellowfin tuna (*Thunnus albacares*, weight-at-age). Bayesian analysis was used to generate estimates of parameters and their posteriors, using uniform priors over the likely parameter spaces for each parameter.

* growth rate (dW/dt; mass*time^{-1}) = rates of energy input and energy expenditure, which are both weight specific. 

$$
\frac{dW_t}{dt} = HW_t^d - kW_t^n \\
$$

$W_t$ = weight at age $t$ (years)

$kW_t^n$ = energy loss

$d$ = allometric scaling of consumption 

$n$ = allometric scaling of energy costs, where von Bertalanffy (@vonbertalanffy_1938) assumed $n = 1$ (linear); standard metabolism rates suggest that $n$ should be nonlinear and closer to 0.8, but if so then there is no closed form solution to the integral of the rate equation and standard metabolism does not account for other energy costs (e.g., swimming, reproduction).

$W_{\inf}$ = asymptotic mass, by solving the rate equation for zero.

Generalized VBGF - solving for asymptotic mass, this can also be converted to the specialized VBGF where consumption rate scales with body size to the 2/3 power (i.e., $d=2/3$).
$$
W_t = W_{\inf}(1-exp(-k(1-d)(t-t_0)))^{\frac{1}{1-d}} \\
$$

Length - length mass relationship $W = aL^b$. Using the specialized VBGF $b=3$ and $d=2/3$ such that $m=0$ and the expression simplies to the empirically derived growth curve.
$$
L_t = L_{\inf}(1-exp(-K(1-m)(t-t_0)))^{1/(1-m)} \\
$$

$m = db + 1 - b$ \\

$E = (H/b)a^{d-1}$ \\

$K = k/b$ \\

$L_{\inf} = (E/k)^{1/(1-m)}$ \\

Consumption - Consumption rate is related to assimilation by $C = (H/A)W^d_t$. Where $A$ is the assimilation efficiency, which is assumed to be constant across body sizes, and $C$ is the consumption rate. If $t$ is in years, the daily mass-specific consumption rate of an individual is $C_{ind} = \frac{(H/A)W_t^{d-1}} {365}$ with the units of $kg*kg^{-1}*day^{-1}$, $H$ must be greater than $k$ for positive growth. Consumption can also be calculated for the entire population by defining yearly recruitment rate ($number*year^{-1}$), instantaneous mortality ($year^{-1}$), and integrating across $t_r$ (age of recruitment) to $t_{max}$. 

# Results: simulation
VBGF underestimates consumption rates when the true value of allometric slope of energy expenditure ($n$) is $< 1$ and overestimates consumption rate when $n > 1$. 

Specialized VBGF underestimates consumption rate by 45% on average. 

# Results: real data
Meta-analysis - Allometric slope of energy expenditure from 17 different species had a mean of 1.02. Allometric slope of consumption ($d$) was more variable, ranging from 0.39 to 1.44. Consumption rates were higher from contaminant analyses compared to bioenergetic analyses, with no statistically significant relationship detectable between mass-specific consumption and body size for contaminant data ($\bar{d} = 1.00$). 

Consumption - for both tuna species the posterior for $d$ did not contain 0.67; large amounts of uncertainty were reflected in the posterior estimates when the consumption rates were scaled up to the population level for both species, which reflects the long-lived nature of the species and the inability to adequately determine their age, too  many parameter combinations fit the data as the sample sizes are very small for older individuals, holding animals in captivity may provide better estimates. 

bluefin tuna - show a deceleration in growth rate at large body sizes, but VBGF estimates parameters with relatively high precision (long right tail). 

yellowfin tuna - wider posterior distributions, no well-defined mode for daily consumption (displayed equal probability), many combinations of parameter estimates that violated the prior probability criteria that a 50 kg individual consumes less than 7.5\% body mass per day. 

# Conclusion
Key data needed to estimate fish consumption rates are not available for the vast majority of fish species. VBGF holds promise to take available data and estimate consumption rates when contaminant analyses and bioenergetics models are not feasible. Accuracy of parameter estimates depends on form of VBGF used and the quality of the data. 

The specialized VBGF is good for yield-per-recruit analyses but the parameters only correspond to $d = 2/3$ and $b = 3$ which is not always true. 