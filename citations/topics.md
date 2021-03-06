# Functional response

The per capita feeding rate on prey as a function of prey abundance (Holling, 1959). If the prey biomass remains constant over the period in which data are measured, then the result is an instantaneous measure of feeding rate. Conversely, if prey abundance changes over the period in which data are measured, then the result is an integrated feeding rate \(\frac{dN}{dt} = -f_i(N, P)P\). Where \(i\) is the type of functional response. Classically, functional response relationships assume that predators encounter prey items at random, with the number of encounters per predator being proportional to prey density. As well as, assuming that the relationship is strictly related to behaviour and that the rate at which an individual predator eats prey is not affected by the presence of other predators. In types Types I-III, predators do not interfere with one another’s activities. Functional responses, and the way in which they are parameterized, are extremely important in a multispecies context. For instance, Ecopath with Ecosim results are highly sensitive to the level of predator-dependent functional responses present, such that predictions change with intensity of predator-dependence (Cox *et al.*, 2002). Each type of functional response incorporates following parameters:

-   search time (\(a\)) -
-   handling time (\(b\)) - for each captured prey item the predator must spend time eating it
-   satiation - the time needed to digest a prey item
-   competition - among other predators, most often of the same species; this parameter will typically be included as \((1 - P)\) to allow a single predator to not influence its own predation rates. \((1 - P)\) should be changed to \(P\) if predators are represented by biomass and not numbers.

Types include the following:

-   Type I: linear, lotka-voltera
-   Type II: asymptotic \[f_2(N,P) = \frac{aN}{1 + bN}\]
-   Type III: sigmoid
-   Predator-dependent: per-capita consumption rates are influenced by predator abundance, and work to decouple the linkage between predator abundance and the total amount of prey consumed. Predator interference models can better explain empirical data than models that are predator-independent (Skalski and Gilliam, 2001). More specifically, the Beddington-DeAngelis (Beddington, 1975; De Angelis, 1975) and Hassel-Varley (<span class="citeproc-not-found" data-reference-id="Hassel1969">**???**</span>) models should be used when the predator feeding rate becomes independent of predator density at high levels of prey density. The Crowley-Martin (Crowley and Martin, 1989) model should be used when predator feeding rates decrease with high abundances of prey. The Hassel-Varley (<span class="citeproc-not-found" data-reference-id="Hassel1969">**???**</span>) model assumes a ratio-dependent functional response when the exponent on the level of the predator is one. Predator-dependent models can occur with the following behaviours:

    -   predator interference behaviour (Beddington, 1975; De Angelis, 1975) - predators do not interfere with other predators when they are handling prey. That is, as the number of prey increase to infinity the equation is reduced in the limit to \(\frac{a}{b}\). \[f_4(N,P) = \frac{aN}{1 + bN + c(P - 1)}\]
    -   predator interference behaviour (Crowley and Martin, 1989) - predators continue to interfere with each other even at high prey densities. That is, as the number of prey increase to infinity the equation is reduced in the limit to \(\frac{a}{b(1 + c(P - 1))}\). \[f_4(N,P) = \frac{aN}{1 + bN + c(P - 1) + bcN(P - 1)}\]
    -   ratio-dependend (<span class="citeproc-not-found" data-reference-id="Hassel1969">**???**</span>) - as modified by Sutherland (1983) \[f_5(N,P) = \frac{aN}{bN + P^m}\]
    -   prey refuging behaviour (Abrams, 1994; Abrams and Walters, 1996)
    -   size-based predation (Armstrong, 1999)
    -   spatial heterogeneity (Keeling *et al.*, 2000; Poggiale *et al.*, 1998)
    -   time lost hunting for prey

# Fisheries induced evolution

Theory indicates with the cessation of fishing stocks should recover, but in practice recovery has been slow or not at all (Hutchings, 1996).

Fisheries induce multiple changes, but typically the first two are the only ones acknowledged:

-   accounted for in stock assessment models
    -   reduction in biomass
    -   reduction in abundance
-   not typically accounted for in stock assessment models
    -   truncated age structure: reduced reproductive potential (Murawski, 2000), increased variability in recruitment (Longhurst, 2002), increased vulnerability to environmental fluctuations (Hsieh *et al.*, 2008)
    -   change the biotic environment: reduce intraspecific competition which could lead to increased growth, earlier maturation, can also change interspecific interactions
    -   fundamental changes to the natural mortality schedule of fishes
    -   changes in ecosystem structure, causing regime shifts and alternative stable states (Jackson *et al.*, 2001; Scheffer *et al.*, 2005)

# Fisheries policy

## Catch share

Institutional change has the ability to change the outcomes of fisheries, whereas we cannot change the outcomes of fishermen by telling fish what to do. Specifically for catch shares, rights are transfered to individuals who can then trade, hold, or harvest their portion of the total allowable catch. Catch shares are thought to have the ability to greater align incentives present in fisheries with end societal goals. Globally profits are higher if fish are not overexploited but individual fishermen have personal incentives to catch as much fish as possible.

## Global fisheries policy

Global fisheries should be looked at as a panarchy, or a hierarchical adaptive cycle. Where the cycle goes through four phases: growth, conservation, release, and reorganization. When a system enters a state of create destruction, the collapse can trigger cascades to the next level which can lead to a crisis. Some have even gone so far as to prevent fishing on some stocks until others are in a state of despair, such that the stock you were conserving will have a high abundance and provide catch while you allow the other to rebuild. If exploitation of world fisheries continue at an increasing rate we could reach a point of global collapse, which in itself be a tipping point of no return. Species richness can provide a mechanism against the collapse of fisheries, providing increased resilience, shown by an exponential decrease in fisheries collapse with increasing species richness (Worm *et al.*, 2006).

## EBFM

An ecosystem-based approach to fisheries management goes beyond the effects of fishing.

### Bottom trawling

The physical contact of bottom-trawl fisheries with the seabed can lead to several changes to the structure of the benthic ecosystem, as well as the catch of non-target species (i.e., bycatch).

### Indicators

There are many types of indicators, as well as an entire professional journal dedicated to the topic, [*Ecological Indicators*](http://www.sciencedirect.com/science/journal/1470160X). The symposium on “Quantitative Ecosystem Indicators for Fisheries Management” co-organized by UNESCO and SCOR, met to provide information and guidelines about how to develop, test, and apply indicators for EBFM, and the results are available in [ICES 62(3)](EBFMIndicators.md).

# Models

All models are a simplification of reality (Walters, 1986)

## Model selection

### AIC

Minimizes the sum of the negative log-likelihood and the parameters.

### Likelihood-ratio test

\(n(log[\hat{SS}_1] - log[\hat{SS}_2])\), and if 2 is a better fit to the data than 1 than the likelihood ratio test will be positive.

# Somatic growth

Evidence for time-varying somatic growth using real data: [(Whitten *et al.*, 2013)](notes/notes_processed/Whitten2013.md)

## von Bertalanffy (Bertalanffy, 1938)

A bioenergetic expression of fish growth that uses a mass balance equation. The model assumes that growth is continuous, and not seasonal. By using size-at-age data you can determine how much, on average, a fish grows between ages and back-calculate how much fish they must consume to sustain that growth (Essington *et al.*, 2001).

# State-space population dynamics models

power of borrowing information from other populations: [(Óigáard and Skaug, 2014)](notes/notes_processed/Oigard2014.md)

# Stock assessment models

## Fisher behaviour

### Authors

-   Darren M Gillis
-   Adriaan Rijnsdorp

### Risk

#### Safety

Catch shares reduce the risk of fishers exhibiting risky behaviour. With the implementation of catch shares many fisheries exhibit increased season lengths; consequently, fishers are less likely to embark in a fishing expedition in risky weather [(Pfeiffer and Gratz, 2016)](notes/notes_processed/Pfeiffer2016.md).

### Ideal free distribution

Fretwell and Lucas Gillis et al. (1993)

## Pope’s approximation

The Pope (1972) approximation to \(F_{a,y}\) is based on the summation of mortality into two components: (a) natural mortality (*F*) and (b) fishing mortality (*F*). The population dynamics equation: \[N_{a,y} = N_{a+1,y+1} e^{Z_y},\] can be manipulated to: \[N_{a+1,y+1} e^{M} = N_{a,y} - C_{a,y} \frac{Z_{a,y} (1 - e^{-F_{a,y}})}{F_{a,y} (1 - e^{-Z_{a,y}})}.\] Over a range of \(F\) (\(<1.2\)) and \(M\) (\(<0.3\)) values, one can assume: \[N_y = C_y e^{\frac{M}{2}} + N_{y+1} e^{M}.\] When the catch pertains to the last year’s catch of a year-class that is still being fished: \[N_y = \frac{C_y Z_y}{F_y(1-e^{-Z_y})}\] and \[N_y = (C_i e^{\frac{M}{2}}) + (C_{y+1} e^{\frac{3M}{2}}) + (C_{y+2} e^{\frac{5M}{2}}) + (\frac{C_y Z_y e^{t...i M}}{F_y (1 - e^{-Z})}),\] which means that \[F_y = ln(\frac{N_y}{N_{y+1}}) - M.\]

## Recruitment

Typically, recruitment is measured using a lognormal distribution. Catch-at-age data help inform recruitment and information on its variability [(Maunder and Deriso, 2003)](notes/notes_processed/Maunder2003_recruitment.md).

### Recruitment forecasting

If the environment acts as a driver of recruitment forecasts which do not account for recruitment are more likely to perform poorly (A’mar *et al.*, 2009). Short-term forecasts (2 years) that include an environmental index of recruitment for the forecast years showed no improvement over forecasts that did not include environmental information (Basson, 1999). Conversely, using environmental information to adjust *F* lead to improved management if the environmental correlation with recruitment was strong enough (Basson, 1999).

## Types

### Multi-species stock assessment models

The study of predator-prey interactions necessitates the study of both what (composition) and how much ([consumption rates](notes/notes_processed/Essington2001.md)) fish eat. Consumption rates of wild fish are problematic because (a) stomach sampling is intensive, (b) bio-energetics requires size and temperature dependence of metabolism, (c) containment (e.g. Cs, Hg) requires precise estimates of prey containment concentration, and (d) regression analyses have limited predictive capability. Using VBGF and size-at-age data [(Essington *et al.*, 2001)](notes/notes_processed/Essington2001.md) to estimate consumption rates was further developed by (Walters and Essington, 2010, Beaudreau and Essington (2009), Ferriss and Essington (2014)) to include using tagging data accounting for temperature dependence and energy allocation; accounting for gastric evacuation rates and gut residence time; and accounting for patterns of Hg-at-size respectively.

MSVPA - A multi-species stock assessment model that estimates current and historical biomass, while explicitly accounting for predation among species included in the model (Magnússon, 1995). MSVPA assumes stomach-content data and catch are known without error, when in actuality stomach-content data are highly variable. Thus, suitability of prey for each predator and the age structure of the catch are not estimated, but assumed to be known without error.

Gadget - A likelihood based stock assessment method that accounts for multiple species when estimating fishery dynamics. The method cannot account for length or age structure of diet data.

### Single-species stock assessment models

#### Integrated-analysis

Most analyses are performed using an [integrated approach](notes/notes_processed/Maunder2003.md), that has the ability to included data from multiple sources (Maunder and Watters, 2003).

#### VPA

A step-wise procedure to calculate *F* and the size of the population-at-age for each year-class. The method assumes that catch-at-age and natural *M* are known without error. VPAs are based on the following two equations: \[N_{y+1} = N_y e^{-(F_y+M)}\] and \[C_y = N_y \frac{F_y (1 - e^{-(F_y+M)})}{F_y + M}.\] \[\frac{N_{y+1}}{C_y} = \frac{(F+M) e^{-(F+M)}}{F(1 - e^{-(F+M)})}\] requires that *F* be solved using an iterative approach, as there is no analytical solution.

# Definitions

Adaptive co-management - A process whereby institutional arrangements and ecological knowledge are tested and revised in an ongoing, self-organized and dynamic process of learning-by-doing

Allometry - the growth of body parts at different rates, resulting in a change of body proportions

Balanced harvesting - distribution of a moderate fishing mortality rate for the widest range of species, stocks, and sizes in the ecosystem based on the productivity of each group that maintains the relative size and species composition of the ecosystem.

Catabolism - energy expenditure.

Clumsy solutions - Exploratory solutions that include inputs from a broad range of stakeholders along the fish chain, and require information-sharing, knowledge synthesis, and trust-building

Co-management - A resource management partnership in which local users and other stakeholders share power and responsibility with government agencies

Ecosystem stewardship - A strategy to respond to and shape SESs under conditions of uncertainty and change to sustain the supply and opportunities for use of ecosystem services to support human well-being

Feeding rate - transfer of biomass between trophic levels.

Functional response - the rate at which an individual predator is able to obtain its prey given prey and predator densities.

Harvest control rule - formalized decision rules defining the level of *F* that can be applied to the fishery in the future given the current level of *SSB* and *F* relative to their reference values

Inclusive management - Management that seeks to incorporate the knowledge, skills, resources, and perspectives of several actors, and that embraces the notion of process accountability through deliberation and accountability

Integrative science - Methods and processes to support suitable institutional responses, a broader planning perspective, and development of suitable resilience-building strategies

Institutions and incentives - Building of institutional systems that provide incentives to individual fishers and enterprises that lead to behaviour consistent with conservation

Polycentric governance - Institutions which are nested, quasi-autonomous decision-making units operating at multiple scales, balancing between centralized and decentralized control

Primary fisheries management - The minimum management goal, where adequate management does not exist, aimed at social and ecological resilience, food security and poverty reduction

Roving bandit - tragedy of the commons on a world wide scale, where the supply is stripped by the market with no ties to the land

Social learning - The collaborative or mutual development and sharing of knowledge by multiple stakeholders through learning-by-doing

Technological creep - technological development is continually increasing, and increases also lead to increases in the efficiency of vessels.

VBFG - bioenergetic (mass balance) expression of somatic fish growth, often analyzed using size-at-age data (Bertalanffy, 1938).

Wicked problem - no single definition or single answer to know when it is solved

# Acronyms

AIC - Aikaike Information Criteria

BH - Beverton and Holt stock-recruit relationship

EBFM - Ecosystem-based fisheries management

EM - estimation model

*F* - fishing mortality level

GAM - generalized additive model

HCR - harvest control rule

ICES - International Council of the Environment and the Seas

*M* - natural mortality

MSVPA - multi-species virtual population analysis

NAO - North Atlantic Oscilliation

OM - operating model

SCOR - Scientific Committee on Oceanic Research

SES - social-ecological systems

*SSB* - spawning stock biomass

UNESCO - United Nationals Educational, Scientific and Cultural Organization

VBGF - von Bertalanffy growth function

VPA - virtual population analysis

# References

Abrams, P. A. 1994. The fallacies of ‘ratio-dependent’ predation. Ecology: 1842–1850. <http://www.jstor.org/stable/10.2307/1939644> (Accessed 11 October 2013).

Abrams, P. A., and Walters, C. J. 1996. Invulnerable prey and the paradox of enrichment. Ecology: 1125–1133. <http://www.jstor.org/stable/10.2307/2265581> (Accessed 11 October 2013).

Armstrong, R. A. 1999. Stable model structures for representing biogeochemical diversity and size spectra in plankton communities. Journal of Plankton Research, 21: 445–464. Oxford Univ Press.

A’mar, Z. T., Punt, A. E., and Dorn, M. W. 2009. The evaluation of two management strategies for the Gulf of Alaska walleye pollock fishery under climate change. ICES Journal of Marine Science, 66: 1614–1632.

Basson, M. 1999. The importance of environmental factors in the design of management procedures. ICES Journal of Marine Science, 56.

Beaudreau, A. H., and Essington, T. E. 2009. Development of a new field-based approach for estimating consumption rates of fishes and comparison with a bioenergetics model for lingcod (ophiodon elongatus). Canadian Journal of Fisheries and Aquatic Sciences, 66: 565–578. Canadian Science Publishing. <http://dx.doi.org/10.1139/F09-021>.

Beddington, J. 1975. Mutual interference between parasites or predators and its effect on searching efficiency. The Journal of Animal Ecology: 331–340. JSTOR.

Bertalanffy, L. von. 1938. A quantitative theory of organic growth (inquiries on growth laws. II). Human Biology, 10: 181–213. <http://www.jstor.org/stable/41447359> (Accessed 8 July 2014).

Cox, S. P., Essington, T. E., Kitchell, J. F., Martell, S. J. D., Walters, C. J., Boggs, C., and Kaplan, I. 2002. Reconstructing ecosystem dynamics in the central pacific ocean, 1952–1998. iI. a preliminary assessment of the trophic impacts of fishing and effects on tuna dynamics. Canadian Journal of Fisheries and Aquatic Sciences, 59: 1736–1747. Canadian Science Publishing. <http://dx.doi.org/10.1139/f02-138>.

Crowley, P. H., and Martin, E. K. 1989. Functional responses and interference within and between year classes of a dragonfly population. Journal of the North American Benthological Society, 8: 211–221. [University of Chicago Press, Society for Freshwater Science]. <http://www.jstor.org/stable/1467324>.

De Angelis, D. L. 1975. Stability and connectance in food web models. Ecology: 238–243. JSTOR.

Essington, T. E., Kitchell, J. F., and Walters, C. J. 2001. The von bertalanffy growth function, bioenergetics, and the consumption rates of fish. Canadian Journal of Fisheries and Aquatic Sciences, 58: 2129–2138. <http://www.nrcresearchpress.com/doi/abs/10.1139/f01-151> (Accessed 8 July 2014).

Ferriss, B. E., and Essington, T. E. 2014. Can fish consumption rate estimates be improved by linking bioenergetics and mercury mass balance models? Application to tunas. Ecological Modelling, 272: 232–241. Elsevier.

Gillis, D. M., Peterman, R. M., and Tyler, A. V. 1993. Movement dynamics in a fishery: Application of the ideal free distribution to spatial allocation of effort. Canadian Journal of Fisheries and Aquatic Sciences, 50: 323–333. Canadian Science Publishing. <http://dx.doi.org/10.1139/f93-038>.

Holling, C. S. 1959. The components of predation as revealed by a study of small-mammal predation of the european pine sawfly. The Canadian Entomologist, 91: 293–320.

Hsieh, C.-h., Reiss, C. S., Hewitt, R. P., and Sugihara, G. 2008. Spatial analysis shows that fishing enhances the climatic sensitivity of marine fishes. Canadian Journal of Fisheries and Aquatic Sciences, 65: 947–961. NRC Research Press.

Hutchings, J. A. 1996. Spatial and temporal variation in the density of northern cod and a review of hypotheses for the stock’s collapse. Canadian Journal of Fisheries and Aquatic Sciences, 53: 943–962. <http://www.nrc.ca/cgi-bin/cisti/journals/rp/rp2_abst_e?cjfas_f96-097_53_ns_nf_cjfas53-96> (Accessed 11 March 2013).

Jackson, J. B., Kirby, M. X., Berger, W. H., Bjorndal, K. A., Botsford, L. W., Bourque, B. J., and Bradbury, R. H.*et al.* 2001. Historical overfishing and the recent collapse of coastal ecosystems. Science, 293: 629–637. <http://www.sciencemag.org/content/293/5530/629.short> (Accessed 11 October 2013).

Keeling, M. J., Wilson, H. B., and Pacala, S. W. 2000. Reinterpreting space, time lags, and functional responses in ecological models. Science, 290: 1758–1761. <http://www.sciencemag.org/content/290/5497/1758.short> (Accessed 11 October 2013).

Longhurst, A. 2002. Murphy’s law revisited: Longevity as a factor in recruitment to fish populations. Fisheries Research, 56: 125–131. Elsevier.

Magnússon, K. G. 1995. An overview of the multispecies VPA - theory and applications. Reviews in Fish Biology and Fisheries, 5: 195–212. <http://link.springer.com/article/10.1007%2FBF00179756>.

Maunder, M. N., and Deriso, R. B. 2003. Estimation of recruitment in catch-at-age models. Canadian Journal of Fisheries and Aquatic Sciences, 60: 1204–1216. Canadian Science Publishing. <http://dx.doi.org/10.1139/f03-104>.

Maunder, M. N., and Watters, G. M. 2003. A-SCALA: An age-structured statistical catch-at-length analysis for assessing tuna stocks in the esastern Pacific Ocean. Inter-American Tropical Tuna Commission, 22: 433–482.

Murawski, S. 2000. Definitions of overfishing from an ecosystem perspective. ICES Journal of Marine Science, 57: 649–658. Oxford University Press (OUP). <http://dx.doi.org/10.1006/jmsc.2000.0738>.

Óigáard, T. A., and Skaug, H. J. 2014. Fitting state-space models to seal populations with scarce data. ICES Journal of Marine Science, 72: 1462–1469. Oxford University Press (OUP). <http://dx.doi.org/10.1093/icesjms/fsu195>.

Pfeiffer, L., and Gratz, T. 2016. The effect of rights-based fisheries management on risk taking and fishing safety. Proceedings of the National Academy of Sciences, 113: 2615–2620. Proceedings of the National Academy of Sciences. <http://dx.doi.org/10.1073/pnas.1509456113>.

Poggiale, J. C., Michalski, J., and Arditi, R. 1998. Emergence of donor control in patchy predator—prey systems. Bulletin of Mathematical Biology, 60: 1149–1166. Springer.

Pope, J. 1972. An investigation of the accuracy of virtual population analysis. ICNAF Research Bulletin, 9: 65–74.

Scheffer, M., Carpenter, S., and Young, B. de. 2005. Cascading effects of overfishing marine systems. Trends in Ecology & Evolution, 20: 579–581. Elsevier.

Skalski, G. T., and Gilliam, J. F. 2001. Functional responses with predator interference: Viable alternatives to the holling type II model. Ecology, 82: 3083–3092. <http://www.esajournals.org/doi/abs/10.1890/0012-9658(2001)082%5B3083:FRWPIV%5D2.0.CO%3B2> (Accessed 11 October 2013).

Sutherland, W. J. 1983. Aggregation and the ‘ideal free’ distribution. Journal of Animal Ecology, 52: 821–828. [Wiley, British Ecological Society]. <http://www.jstor.org/stable/4456>.

Walters, C. J. 1986. Adaptive management of renewable resources. MacMillan Publishing Company, New York.

Walters, C. J., and Essington, T. 2010. Recovery of bioenergetics parameters from information on growth: Overview of an approach based on statistical analysis of tagging and size-at-age data. Open Fish Science Journal, 3: 52–68. <http://benthamopen.com/tofishsj/articles/V003/SI0051TOFISHSJ/52TOFISHSJ.pdf>.

Whitten, A. R., Klaer, N. L., Tuck, G. N., and Day, R. W. 2013. Accounting for cohort-specific variable growth in fisheries stock assessments: A case study from south-eastern Australia. Fisheries Research, 142: 27–36. Elsevier BV. <http://dx.doi.org/10.1016/j.fishres.2012.06.021>.

Worm, B., Barbier, E. B., Beaumont, N., Duffy, J. E., Folke, C., Halpern, B. S., and Jackson, J. B.*et al.* 2006. Impacts of biodiversity loss on ocean ecosystem services. Science, 314: 787–790. <http://www.sciencemag.org/cgi/doi/10.1126/science.1132294>.


