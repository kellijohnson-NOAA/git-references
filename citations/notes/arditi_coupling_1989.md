~~~~
 Title: Coupling in predator-prey dynamics: ratio-dependence
~~~~

# Summary
The responses of predator-prey systems differ remarkably in the instances
where prey-dependent or ratio-dependent predator responses are assumed.
Prey-dependent responses,
such as the traditional Type I or Type II Holling models
should only be used in simple homogeneous systems with rapid turnover rates.
Whereas, the ratio-dependent models are more important for
large-scale heterogeneous systems where predation is part of a sharing process.
Ratio-dependent functional responses will lead to the same amount of prey
being consumed per predator when the ratio of prey to predators is the same
but the absolute numbers are different.

# Introduction

## Scale
The scale at which the predator-prey dynamics are looked at plays a roll
in which functional response best represents the data.
The functional response for the prey population must operate at the same
time scale in which they reproduce, because together the two elements
add up to determine how many prey are added or subtracted from the population
during time $t$. Heterogeneities introduced from the fact that not all
predators encounter prey at random will lead to instances where it
appears as though predators *share* prey or interfere with each other.
When prey reproduce intermittently instead of continuously can also lead
to a situation that makes it seem as though predators share prey items.
The ratio-dependent functional response is the result of *perfect sharing*.

## Shape
As the number of prey become relatively abundant compared to the number
of predators the consumption rate of the predators will asymptote.
At the origin, the consumption rate increases quickly because predators
will experience short bursts of time where predators encounter prey
inversely proportional to their density, and they will
not have enough time or resources to become full.

## Rationale
Various causes will lead to predator dependence in the functional response
when it is calculated on the generational scale even if predators
do not interfere directly.

* mutual interference
* simple refugia
* proportional refugia
* temporal refugia
* non-random search
* other spatial and temporal heterogeneity
  such as that which occurs because of the life-dinner principle
  because the prey is running for its life while the predator is only
  running for its next meal
* spatial aggregation of predators relative to their prey [@Hanski1991]
* intermittent prey reproduction

# Models

## Equations
First order differential prey-dependent equations:
$$ \frac{dN}{dt} = f(N) * N - g(N,P) * P$$
$$ \frac{dP}{dt} = h(N,P) * P - \mu * P$$
where, $N$ and $P$ are prey and predators in numbers, respectively.
Typically, predator production can be approximated through a proportionality
constant and prey intake:
$$ h(N,P) = g(N,P) * e$$,
where $e$ is predator conversion of prey to production efficiency.
First order differential ratio-dependent equations:
$$ \frac{dN}{dt} = f(N) * N - g(\frac{N}{P}) * P$$
$$ \frac{dP}{dt} = e * g(\frac{N}{P}) * P - \mu * P$$
Thus, the functional response is the sole link between prey and their predators.
For internal consistency, $g(N,P)$ must be interpreted as an average
consumption rate of a typically predator over the time it takes to produce a single
generation of prey or predators.

## Isoclines
### Prey dependent
The predator isocline is always vertical for the prey-dependent functional
response, and $A$ decreases with increasing predator efficiency.
$$ \frac{dP}{dt} = h(N,P) * P - \mu * P$$
$$ 0 = h(N,P) * P - \mu * P$$
$$ h(N,P) * P = \mu * P$$
$$ e * g(N,P) * P = \mu * P$$
$$ \frac{e * g(N,P) * P}{P} = \mu$$
$$ e * g(N,P) = \mu$$
$$ g(N,P) = \frac{\mu}{e}$$
$$ A = g^{-1}(\frac{\mu}{e})$$

The prey isocline can be dome shaped, but does not have to be.
$$ \frac{dN}{dt} = f(N) * N - g(N,P) * P$$
$$ 0 = f(N) * N - g(N,P) * P$$
$$ f(N) * N = g(N,P) * P$$
$$ \frac{f(N)}{g(N,P)} = \frac{P}{N}$$

If the slope at the origin of $g(N)$ is low then the hump shape will
not appear.
The equilibrium will be unstable if the isoclines cross on the ascending
limb. If they do not cross because $\frac{\mu}{e}$ is steep and greater
than the asymptote of $g$ then predators will never grow.

### Ratio dependent
$$g(\frac{N}{P}) * P <= \alpha * N$$
where $\alpha$ is the slope at the origin of $g(\frac{N}{P})$.


