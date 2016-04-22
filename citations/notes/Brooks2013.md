~~~~~
Author: Kelli Faye Johnson
~~~~~

# Summary

Spawning potential has the ability to differ between fish of the same species.
Additionally, biological rates can vary over time making SPR cohort specific.
Simulations were used to investigate the effects of different biological rates
on SPR reference points and how parameterizing the stock recruit function in terms
of maximum lifetime reproductive rate is superior. 
References points based on SPR were influenced by density independent survival
of recruits (i.e., slope at the origin) and spawner condition.

# Notes

Proxy reference points, i.e., SPR, must be derived for when MSY reference points
are not calculable because of their derivation from a stock recruit function.
Steepness is often estimated at its bound (i.e., 1.0), which implies no reduction
in recruitment at any SSB. Even if a meta-analysis of similar stock is used to try
and estimate $h$, high recruitment variability and low contrast in levels of $SSB$
make it difficult to estimate. If $h$ is fixed then one essentially specifies
a $\%SPR$ because of the analytical relationship between $SPR$ and $\hat{\alpha}$.
$R_0$, which defines the unexploited level of recruitment, is a constant estimated
value that typically depends on habitat. $h$ is defined by the intersection of the
replacement line ($\frac{1}{\varphi_0}$) and $R_0$. If parameters that define the
replacement line vary, than $h$ must vary as well because $R_0$ will be constant.
When $\%SPR$ is calculated, it assumes that biological parameters at unexploited 
stock levels are similar to conditions observed for the period in which data are
available.
If one parameterizes the stock recruit function in terms of $\hat{\alpha}$ than
variability can be explicitly incorporated. This may or may not make the assessment
more realistic but it will facilitate the inclusion of more realistic process error.
One would also have to acknowledge that reference points will vary year to year
as well if the stock recruit function varies annually. 

It is often assumed that weight at age can be used as a surrogate for fecundity
at age. Not all biomass of spawners should be created equal though, which may 
lead to biased estimates of fecundity. Experience could be an important determiner
of spawning potential regardless of weight. Additionally, if weights at age 
vary with time and catch is recorded in biomass rather than numbers than the number
of fish caught to reach the same number of pounds will change and thus for the 
same amount of biomass more fish will be caught and the reproductive potential
of the stock could be decreased, depending on the stock recruit function.

Growth may be cohort dependent and using an average of growth across all cohorts
may end up failing to represent the growth of any cohort.

$ \varphi_o $ is the unexploited SPR and $\frac{1}{\varphi_0}$ is the replacement line.

MER defines the reference point where yield in numbers if maximized, where MSY defines 
the maximum yield in biomass. MER reference points often can withstand a higher $F$
and lower $\%SPR$ but it depends on biology and selectivity, though not as much when
steepness is low (i.e., recruits are highly dependent on SSB).
$\hat{\alpha}$ is the maximum lifetime reproductive rate, which equals $a\varphi_0$, 
where $a$ is the slope at the origin, reflecting density-independent survival of recruits.
$h=\frac{\hat{\alpha}}{\hat{\alpha} + 4}$, thus $\hat{\alpha}$ is just a rescaled $h$,
where $h$ [0.2, 1.0] and $\hat{\alpha}$ [1.0, $\infinity$].

\[\begin{aligned} SPR_{MER} = \frac{1}{\sqrt{\hat{\alpha}}} = \frac{\sqrt{1-h}}{2}\sqrt{h} \end{aligned}\]

Environmental effects can also constrain survival of recruits at the origin, e.g.,
temperature and advection to suitable environments.

Selectivity can amplify or dampen the perceived differences between alternative 
reproductive potential scenarios. When young fish are selected the curves of $\%SPR$
were difficult to distinguish. 

# Management implications

Stock status references how the stock is fairing relative to its biomass at 
unexploited levels, or the stock relative to estimated reference points.
Reference points should be characterized by the observed variability over time
rather than updating them each time new information about a single parameter is 
observed. Conversely if selectivity drastically changes such that younger fish are
or are not being caught then reference points will need to be updated. 
If you are not able to estimate $a$ then you have to assume a value for $\%SPR$, where
$40\%$ is reasonable for demersal fish life-history types. 

Projections into the future beyond 3 years rely heavily on 'paper fish', fish
which were not estimated in the stock assessment model but are rather direct outcomes
of projections. Projected year classes are often highly dependent on regimes
and other environmental and maternal factors which are often not taken into account
during the forecasting methods. Furthermore, biological parameters are often correlated
and so even if a distribution is used for a parameter to characterize its uncertainty
into the future, other parameters may depend upon this variability which should also
be accounted for; a task that is made even further difficult by the tendency of
environmental relationships to break down over time. 
