[//]: # (
Markdown comments:
1. links: wrap in [](), where the second contains the path)

# Functional response

The per capita feeding rate on prey as a function of prey abundance [@holling_components_1959].
If the prey biomass remains constant over the period in which data are measured, then the result
is an instantaneous measure of feeding rate. Conversely, if prey abundance changes over the period
in which data are measured, then the result is an integrated feeding rate
$\frac{dN}{dt} = -f_i(N, P)P$. Where $i$ is the type of functional response.
Classically, functional response relationships assume that predators encounter
prey items at random, with the number of encounters per predator
being proportional to prey density.
As well as, assuming that the relationship is strictly related to behaviour and that
the rate at which an individual predator eats prey is not affected by the presence of other
predators.
In types Types I-III, predators do not interfere with one another's activities.
Functional responses, and the way in which they are parameterized, are extremely important
in a multispecies context. For instance,
Ecopath with Ecosim results are highly sensitive to the level of predator-dependent functional
responses present, such that predictions change with intensity of predator-dependence [@cox_2002].
Each type of functional response incorporates following parameters:

* search time ($a$) -
* handling time ($b$) - for each captured prey item the predator must spend time eating it
* satiation - the time needed to digest a prey item
* competition - among other predators, most often of the same species; this parameter will
typically be included as $(1 - P)$ to allow a single predator to not influence its own
predation rates. $(1 - P)$ should be changed to $P$ if predators are represented by biomass
and not numbers.

Types include the following:

* Type I: linear, lotka-voltera
* Type II: asymptotic
$$f_2(N,P) = \frac{aN}{1 + bN}$$
* Type III: sigmoid
* Predator-dependent: per-capita consumption rates are influenced by predator abundance,
and work to decouple the linkage between predator abundance and the total amount of prey consumed.
Predator interference models can better explain empirical data than models that are
predator-independent [@skalski_functional_2001]. More specifically, the
Beddington-DeAngelis [@beddington_1975; @deangelis_1975] and Hassel-Varley [@Hassel1969]
models should be used when the predator feeding rate becomes independent of predator density
at high levels of prey density.
The Crowley-Martin [@Crowley1989] model should be used when predator feeding rates decrease with
high abundances of prey.
The Hassel-Varley [@Hassel1969] model assumes a ratio-dependent functional response
when the exponent on the level of the predator is one.
Predator-dependent models can occur with the following behaviours:
    * predator interference behaviour [@beddington_1975; @deangelis_1975] - predators do not
    interfere with other predators when they are handling prey. That is, as the number of prey
    increase to infinity the equation is reduced in the limit to $\frac{a}{b}$.
    $$f_4(N,P) = \frac{aN}{1 + bN + c(P - 1)}$$
    * predator interference behaviour [@Crowley1989] - predators continue to interfere
    with each other even at high prey densities. That is, as the number of prey
    increase to infinity the equation is reduced in the limit to $\frac{a}{b(1 + c(P - 1))}$.
    $$f_4(N,P) = \frac{aN}{1 + bN + c(P - 1) + bcN(P - 1)}$$
    * ratio-dependend [@Hassel1969] - as modified by Sutherland [-@Sutherland1983]
    $$f_5(N,P) = \frac{aN}{bN + P^m}$$
    * prey refuging behaviour [@abrams_1994; @abrams_invulnerable_1996]
    * size-based predation [@armstrong_1999]
    * spatial heterogeneity [@poggiale_1998; @keeling_2000]
    * time lost hunting for prey

# Fisheries induced evolution

Theory indicates with the cessation of fishing stocks should recover,
but in practice recovery has been slow or not at all [@hutchings_spatial_1996].

Fisheries induce multiple changes, but typically the first two are the only ones acknowledged:

* accounted for in stock assessment models
    * reduction in biomass
    * reduction in abundance
* not typically accounted for in stock assessment models
    * truncated age structure: reduced reproductive potential [@Murawski2000],
    increased variability in recruitment [@longhurst_2002],
    increased vulnerability to environmental fluctuations [@hsieh_2008]
    * change the biotic environment: reduce intraspecific competition which could lead to increased growth,
    earlier maturation, can also change interspecific interactions
    * fundamental changes to the natural mortality schedule of fishes
    * changes in ecosystem structure, causing regime shifts and alternative stable states [@jackson_historical_2001; @scheffer_2005]

# Fisheries policy

## Catch share
Institutional change has the ability to change the outcomes of fisheries, whereas we cannot
change the outcomes of fishermen by telling fish what to do.
Specifically for catch shares, rights are transfered to individuals who can then
trade, hold, or harvest their portion of the total allowable catch.
Catch shares are thought to have the ability to greater align incentives present
in fisheries with end societal goals. Globally profits are higher if fish are not overexploited but
individual fishermen have personal incentives to catch as much fish as possible.

## Global fisheries policy
Global fisheries should be looked at as a panarchy, or a hierarchical adaptive cycle.
Where the cycle goes through four phases: growth, conservation, release, and reorganization.
When a system enters a state of create destruction, the collapse can trigger cascades
to the next level which can lead to a crisis. Some have even gone so far as to prevent fishing
on some stocks until others are in a state of despair, such that the stock you were conserving
will have a high abundance and provide catch while you allow the other to rebuild.
If exploitation of world fisheries continue at an increasing rate we could reach a point of global
collapse, which in itself be a tipping point of no return.
Species richness can provide a mechanism against the collapse of fisheries,
providing increased resilience, shown by an exponential decrease in fisheries collapse with increasing species richness [@worm_impacts_2006].

## EBFM
An ecosystem-based approach to fisheries management goes beyond the effects of fishing.
Various definitions mean different things, although they are often used interchangeably.
EBM refers to the entire ecosystem, and not just fisheries. Whereas, EBFM pertains to
how fisheries operate within the ecosystem, and is often considered in a fisheries
ecosystem plan.
EBFM takes a coordinated approach for all fisheries within a management system and attempts
to provide society with the most benefits by looking at more than just yield
(e.g., diversity, resilience, or socio-economic indicators).
Lastly, EAFM is the most narrow, excluding SSFM, and pertains to how the ecosystem
affects the fish stock of interest. The stock is still managed through BRPs, though
they may be influenced by environmental indices or informed by multi-species models.
Additionally, EAFM can provide context to unmodelled uncertainty surrounding BRP or
future management decisions, particularly in a MSE.
Regardless of what species is being managed or which framework is being used to manage it,
fisheries management and ecosystem management are both concerned about productivity, and
the more that is known about the productivity of marine fishes in various environments and
under various anthropogenic stressors the better informed management will be.

### Bottom trawling
The physical contact of bottom-trawl fisheries with the seabed can lead to
several changes to the structure of the benthic ecosystem,
as well as the catch of non-target species (i.e., bycatch).

### Indicators
There are many types of indicators, as well as an entire professional journal
dedicated to the topic,
[*Ecological Indicators*](http://www.sciencedirect.com/science/journal/1470160X).
The symposium on "Quantitative Ecosystem Indicators for Fisheries Management"
co-organized by UNESCO and SCOR, met to provide information and guidelines
about how to develop, test, and apply indicators for EBFM, and the results
are available in
[ICES 62(3)](EBFMIndicators.md).

# Models

All models are a simplification of reality [@walters_1986]

## Model selection

### AIC
Minimizes the sum of the negative log-likelihood and the parameters.

### Likelihood-ratio test
$n(log[\hat{SS}_1] - log[\hat{SS}_2])$, and if 2 is a better fit to the data than 1
than the likelihood ratio test will be positive.

# Somatic growth

Evidence for time-varying somatic growth using real data:
[[@Whitten2013]](notes/notes_processed/Whitten2013.md)

## von Bertalanffy [@von_bertalanffy_quantitative_1938]
A bioenergetic expression of fish growth that uses a mass balance equation.
The model assumes that growth is continuous, and not seasonal.
By using size-at-age data you can determine how much, on average, a fish grows between ages
and back-calculate how much fish they must consume to sustain that growth [@essington_von_2001].

# State-space population dynamics models

power of borrowing information from other populations: [[@Oigard2014]](notes/notes_processed/Oigard2014.md)

# Stock assessment models

## Fisher behaviour

### Authors
* Darren M Gillis
* Adriaan Rijnsdorp

### Risk
#### Safety
Catch shares reduce the risk of fishers exhibiting risky behaviour.
With the implementation of catch shares many fisheries exhibit increased
season lengths; consequently, fishers are less likely to embark in a fishing
expedition in risky weather [[@Pfeiffer2016]](notes/notes_processed/Pfeiffer2016.md).

### Ideal free distribution
Fretwell and Lucas -@Gillis1993

## Pope's approximation
The -@Pope1972 approximation to $F_{a,y}$ is based on the summation of mortality
into two components: (a) natural mortality (*F*) and (b) fishing mortality (*F*).
The population dynamics equation:
$$N_{a,y} = N_{a+1,y+1} e^{Z_y},$$
can be manipulated to:
$$N_{a+1,y+1} e^{M} = N_{a,y} - C_{a,y} \frac{Z_{a,y} (1 - e^{-F_{a,y}})}{F_{a,y} (1 - e^{-Z_{a,y}})}.$$
Over a range of $F$ ($<1.2$) and $M$ ($<0.3$) values, one can assume:
$$N_y = C_y e^{\frac{M}{2}} + N_{y+1} e^{M}.$$
When the catch pertains to the last year's catch of a year-class that is still
being fished:
$$N_y = \frac{C_y Z_y}{F_y(1-e^{-Z_y})}$$
and
$$N_y = (C_i e^{\frac{M}{2}}) + (C_{y+1} e^{\frac{3M}{2}}) + (C_{y+2} e^{\frac{5M}{2}}) + (\frac{C_y Z_y e^{t...i M}}{F_y (1 - e^{-Z})}),$$
which means that
$$F_y = ln(\frac{N_y}{N_{y+1}}) - M.$$

## Recruitment
Typically, recruitment is measured using a lognormal distribution.
Catch-at-age data help inform recruitment and information on its variability
[[@Maunder2003_recruitment]](notes/notes_processed/Maunder2003_recruitment.md).

### Recruitment forecasting
If the environment acts as a driver of recruitment forecasts which do not account for recruitment
are more likely to perform poorly [@Amar2009]. Short-term forecasts (2 years) that include an
environmental index of recruitment for the forecast years showed no improvement over forecasts
that did not include environmental information [@Basson1999]. Conversely, using environmental
information to adjust *F* lead to improved management if the environmental correlation with
recruitment was strong enough [@Basson1999].

## Types

### Multi-species stock assessment models
The study of predator-prey interactions necessitates the study of both what (composition) and
how much ([consumption rates](notes/notes_processed/Essington2001.md)) fish eat.
Consumption rates of wild fish are problematic because (a) stomach sampling is intensive,
(b) bio-energetics requires size and temperature dependence of metabolism,
(c) containment (e.g. Cs, Hg) requires precise estimates of prey containment concentration, and
(d) regression analyses have limited predictive capability.
Using VBGF and size-at-age data [[@essington_von_2001]](notes/notes_processed/Essington2001.md)
to estimate consumption rates was further developed by [@walters_2010, @beaudreau_2009, @ferriss_2014]
to include using tagging data accounting for temperature dependence and energy allocation;
accounting for gastric evacuation rates and gut residence time; and accounting for patterns of Hg-at-size respectively.

MSVPA - A multi-species stock assessment model that estimates current and historical biomass,
while explicitly accounting for predation among species included in the model [@magnusson_1995].
MSVPA assumes stomach-content data and catch are known without error,
when in actuality stomach-content data are highly variable.
Thus, suitability of prey for each predator and the age structure of the catch are not estimated,
but assumed to be known without error.

Gadget - A likelihood based stock assessment method that accounts for multiple species when estimating fishery dynamics.
The method cannot account for length or age structure of diet data.

### Single-species stock assessment models

#### Integrated-analysis
Most analyses are performed using an
[integrated approach](notes/notes_processed/Maunder2003.md),
that has the ability to included data from multiple sources [@maunder2003].

#### VPA
A step-wise procedure to calculate *F* and the size of the population-at-age
for each year-class. The method assumes that catch-at-age and natural *M* are
known without error.
VPAs are based on the following two equations:
$$N_{y+1} = N_y e^{-(F_y+M)}$$
and
$$C_y = N_y \frac{F_y (1 - e^{-(F_y+M)})}{F_y + M}.$$
$$\frac{N_{y+1}}{C_y} = \frac{(F+M) e^{-(F+M)}}{F(1 - e^{-(F+M)})}$$
requires that *F* be solved using an iterative approach, as there is no
analytical solution.

# Definitions

Adaptive co-management - A process whereby institutional arrangements and
ecological knowledge are tested and revised in an ongoing, self-organized and
dynamic process of learning-by-doing

Allometry - the growth of body parts at different rates,
resulting in a change of body proportions

Balanced harvesting - distribution of a moderate fishing mortality rate
for the widest range of species, stocks, and sizes in the ecosystem
based on the productivity of each group that maintains the relative size
and species composition of the ecosystem.

Catabolism - energy expenditure.

Clumsy solutions - Exploratory solutions that include inputs from
a broad range of stakeholders along the fish chain, and
require information-sharing, knowledge synthesis, and trust-building

Co-management - A resource management partnership in which local users and
other stakeholders share power and responsibility with government agencies

Ecosystem stewardship - A strategy to respond to and shape SESs
under conditions of uncertainty and change to sustain the supply and
opportunities for use of ecosystem services to support human well-being

Feeding rate - transfer of biomass between trophic levels.

Functional response - the rate at which an individual predator is able to obtain its prey
given prey and predator densities.

Harvest control rule - formalized decision rules defining the level of *F* that can be
applied to the fishery in the future given the current level of *SSB* and *F* relative
to their reference values

Inclusive management - Management that seeks to incorporate the knowledge, skills,
resources, and perspectives of several actors, and
that embraces the notion of process accountability through deliberation and accountability

Integrative science - Methods and processes to support suitable
institutional responses, a broader planning perspective, and
development of suitable resilience-building strategies

Institutions and incentives - Building of institutional systems that
provide incentives to individual fishers and enterprises that
lead to behaviour consistent with conservation

Polycentric governance - Institutions which are nested,
quasi-autonomous decision-making units operating at multiple scales,
balancing between centralized and decentralized control

Primary fisheries management - The minimum management goal,
where adequate management does not exist, aimed at social and ecological resilience,
food security and poverty reduction

Roving bandit - tragedy of the commons on a world wide scale,
where the supply is stripped by the market with no ties to the land

Social learning - The collaborative or mutual development and sharing of knowledge
by multiple stakeholders through learning-by-doing

Technological creep - technological development is continually increasing, and
increases also lead to increases in the efficiency of vessels.

VBFG - bioenergetic (mass balance) expression of somatic fish growth,
often analyzed using size-at-age data [@von_bertalanffy_quantitative_1938].

Wicked problem - no single definition or single answer to know when it is solved

# Acronyms

AIC - Aikaike Information Criteria

BH - Beverton and Holt stock-recruit relationship

BRP - biological reference point

EAFM - Ecosystem approach to fisheries management

EBFM - Ecosystem-based fisheries management

EBM - Ecosystem-based management

EM - estimation model

*F* - fishing mortality level

GAM - generalized additive model

HCR - harvest control rule

ICES - International Council of the Environment and the Seas

IOC - Intergovernmental Oceanographic Committee

*M* - natural mortality

MSE - management strategy evaluation

MSVPA - multi-species virtual population analysis

NAO - North Atlantic Oscilliation

OM - operating model

SCOR - Scientific Committee on Oceanic Research

SES - social-ecological systems

*SSB* - spawning stock biomass

SSFM - single-species fisheries management

UNESCO - United Nationals Educational, Scientific and Cultural Organization

VBGF - von Bertalanffy growth function

VPA - virtual population analysis

# References
