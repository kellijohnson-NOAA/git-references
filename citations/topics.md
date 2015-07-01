# Models

All models are a simplification of reality (Walters (1986))

# Functional response

-   Type I: linear, lotka-voltera
-   Type II: asymptotic
-   Type III: sigmoid
-   Predator-dependent: per-capita consumption rates are influenced by predator abundance, Can decouple the linkage between predator abundance and the total amount of prey consumed, Ecopath with Ecosim results are highly sensitive to the level of predator-dependent functional responses present, such that predictions change with intensity of predator-dependence (Cox *et al.* (2002)), Can occur with
    -   predator interference behaviour (Beddington (1975), De Angelis (1975))
    -   prey refuging behaviour (Abrams (1994), Abrams and Walters (1996))
    -   size-based predation (Armstrong (1999))
    -   spatial heterogeneity (Poggiale *et al.* (1998), (<span class="citeproc-not-found" data-reference-id="keeling_2000">**???**</span>))

# Fisheries somatic growth

Evidence for time-varying somatic growth using real data: [(Whitten *et al.*, 2013)](notes/notes_processed/Whitten2013.md)

# Fisheries induced evolution

Theory indicates with the cessation of fishing stocks should recover, but in practice recovery has been slow or not at all (Hutchings (1996)).

Fisheries induce multiple changes, but typically the first two are the only ones acknowledged: \* accounted for in stock assessment models \* reduction in biomass \* reduction in abundance \* not typically accounted for in stock assessment models \* truncated age structure: reduced reproductive potential (Murawski (2000)), increased variability in recruitment (Longhurst (2002)), increased vulnerability to environmental fluctuations (Hsieh *et al.* (2008)) \* change the biotic environment: reduce intraspecific competition which could lead to increased growth, earlier maturation, can also change interspecific interactions \* fundamental changes to the natural mortality schedule of fishes \* changes in ecosystem structure, causing regime shifts and alternative stable states (Jackson *et al.* (2001), Scheffer *et al.* (2005))

# State-space population dynamics models

power of borrowing information from other populations: [(Øigård and Skaug, 2014)](notes/notes_processed/Oigard2014.md)

# Multi-species stock assessment models

The study of predator-prey interactions necessitates the study of both what (composition) and how much ([consumption rates](notes/notes_processed/Essington2001.md)) fish eat. Consumption rates of wild fish are problematic because (a) stomach sampling is intensive, (b) bio-energetics requires size and temperature dependence of metabolism, (c) containment (e.g. Cs, Hg) requires precise estimates of prey containment concentration, and (d) regression analyses have limited predictive capability. Using VBGF and size-at-age data (Essington *et al.*, 2001)(notes/notes\_processed/Essington2001.md) to estimate consumption rates was further developed by (Walters and Essington (2010), Beaudreau and Essington (2009), Ferriss and Essington (2014)) to include using tagging data accounting for temperature dependence and energy allocation; accounting for gastric evacuation rates and gut residence time; and accounting for patterns of Hg-at-size respectively.

MSVPA: A multi-species stock assessment model that estimates current and historical biomass while explicitly accounting for predation among species included in the model (Magnússon (1995)). MSVPA assumes stomach-content data and catch are known without error, when in actuality stomach-content data are highly variable. Thus, suitability of prey for each predator and the age structure of the catch are not estimated but assumed to be known without error.

Gadget: A likelihood based stock assessment method that accounts for multiple species when estimating fishery dynamics. The method cannot account for length or age structure of diet data.

# Fisheries policy

## Global fisheries policy

Global fisheries should be looked at as a panarchy, or a hierarchical adaptive cycle. Where the cycle goes through four phases: growth, conservation, release, and reorganization. When a system enters a state of create destruction, the collapse can trigger cascades to the next level which can lead to a crisis. Some have even gone so far as to prevent fishing on some stocks until others are in a state of despair, such that the stock you were conserving will have a high abundance and provide catch while you allow the other to rebuild. If exploitation of world fisheries continue at an increasing rate we could reach a point of global collapse, which in itself be a tipping point of no return. Species richness can provide a mechanism against the collapse of fisheries, providing increased resilience, shown by an exponential decrease in fisheries collapse with increasing species richness (Worm *et al.* (2006)).

## Catch share

Institutional change has the ability to change the outcomes of fisheries, whereas we cannot change the outcomes of fishermen by telling fish what to do. Specifically for catch shares, rights are transfered to individuals who can then trade, hold, or harvest their portion of the total allowable catch. Catch shares are thought to have the ability to greater align incentives present in fisheries with end societal goals. Globally profits are higher if fish are not overexploited but individual fishermen have personal incentives to catch as much fish as possible.

# Definitions

Allometry: the growth of body parts at different rates, resulting in a change of body proportions

Functional response: the rate at which an individual predator is able to obtain its prey given prey and predator densities. Incorporates search time, handling time for each captured prey item, time needed to digest a prey item (satiation), and competition with other predators.

VBFG: bioenergetic (mass balance) expression of somatic fish growth, often analyzed using size-at-age data ((<span class="citeproc-not-found" data-reference-id="vonbertalanffy_1938">**???**</span>)).

# Acronyms

AIC - Aikaike Information Criteria

MSVPA - multi-species virtual population analysis

VBGF - von Bertalanffy growth function

Abrams, P. A. 1994. The fallacies of ‘ratio-dependent’ predation. Ecology: 1842–1850. <http://www.jstor.org/stable/10.2307/1939644> (Accessed 11 October 2013).

Abrams, P. A., and Walters, C. J. 1996. Invulnerable prey and the paradox of enrichment. Ecology: 1125–1133. <http://www.jstor.org/stable/10.2307/2265581> (Accessed 11 October 2013).

Armstrong, R. A. 1999. Stable model structures for representing biogeochemical diversity and size spectra in plankton communities. Journal of Plankton Research, 21: 445–464. Oxford Univ Press.

Beaudreau, A. H., and Essington, T. E. 2009. Development of a new field-based approach for estimating consumption rates of fishes and comparison with a bioenergetics model for lingcod (ophiodon elongatus). Canadian Journal of Fisheries and Aquatic Sciences, 66: 565–578. Canadian Science Publishing. <http://dx.doi.org/10.1139/F09-021>.

Beddington, J. 1975. Mutual interference between parasites or predators and its effect on searching efficiency. The Journal of Animal Ecology: 331–340. JSTOR.

Cox, S. P., Essington, T. E., Kitchell, J. F., Martell, S. J. D., Walters, C. J., Boggs, C., and Kaplan, I. 2002. Reconstructing ecosystem dynamics in the central pacific ocean, 1952–1998. iI. a preliminary assessment of the trophic impacts of fishing and effects on tuna dynamics. Canadian Journal of Fisheries and Aquatic Sciences, 59: 1736–1747. Canadian Science Publishing. <http://dx.doi.org/10.1139/f02-138>.

De Angelis, D. L. 1975. Stability and connectance in food web models. Ecology: 238–243. JSTOR.

Essington, T. E., Kitchell, J. F., and Walters, C. J. 2001. The von bertalanffy growth function, bioenergetics, and the consumption rates of fish. Canadian Journal of Fisheries and Aquatic Sciences, 58: 2129–2138. <http://www.nrcresearchpress.com/doi/abs/10.1139/f01-151> (Accessed 8 July 2014).

Ferriss, B. E., and Essington, T. E. 2014. Can fish consumption rate estimates be improved by linking bioenergetics and mercury mass balance models? Application to tunas. Ecological Modelling, 272: 232–241. Elsevier.

Hsieh, C.-h., Reiss, C. S., Hewitt, R. P., and Sugihara, G. 2008. Spatial analysis shows that fishing enhances the climatic sensitivity of marine fishes. Canadian Journal of Fisheries and Aquatic Sciences, 65: 947–961. NRC Research Press.

Hutchings, J. 1996. Spatial and temporal variation in the density of northern cod and a review of hypotheses for the stock’s collapse. Canadian Journal of Fisheries and Aquatic Sciences, 53: 943–962. <http://www.nrc.ca/cgi-bin/cisti/journals/rp/rp2_abst_e?cjfas_f96-097_53_ns_nf_cjfas53-96> (Accessed 11 March 2013).

Jackson, J. B., Kirby, M. X., Berger, W. H., Bjorndal, K. A., Botsford, L. W., Bourque, B. J., and Bradbury, R. H. *et al.* 2001. Historical overfishing and the recent collapse of coastal ecosystems. Science, 293: 629–637. <http://www.sciencemag.org/content/293/5530/629.short> (Accessed 11 October 2013).

Longhurst, A. 2002. Murphy’s law revisited: Longevity as a factor in recruitment to fish populations. Fisheries Research, 56: 125–131. Elsevier.

Magnússon, K. G. 1995. An overview of the multispecies VPA - theory and applications. Reviews in Fish Biology and Fisheries, 5: 195–212. <http://link.springer.com/article/10.1007%2FBF00179756>.

Murawski, S. 2000. Definitions of overfishing from an ecosystem perspective. ICES Journal of Marine Science, 57: 649–658. Oxford University Press (OUP). <http://dx.doi.org/10.1006/jmsc.2000.0738>.

Poggiale, J. C., Michalski, J., and Arditi, R. 1998. Emergence of donor control in patchy predator—prey systems. Bulletin of Mathematical Biology, 60: 1149–1166. Springer.

Scheffer, M., Carpenter, S., and Young, B. de. 2005. Cascading effects of overfishing marine systems. Trends in Ecology & Evolution, 20: 579–581. Elsevier.

Walters, C. J. 1986. Adaptive management of renewable resources. MacMillan Publishing Company, New York.

Walters, C., and Essington, T. 2010. Recovery of bioenergetics parameters from information on growth: Overview of an approach based on statistical analysis of tagging and size-at-age data. Open Fish Science Journal, 3: 52–68. <http://benthamopen.com/tofishsj/articles/V003/SI0051TOFISHSJ/52TOFISHSJ.pdf>.

Whitten, A. R., Klaer, N. L., Tuck, G. N., and Day, R. W. 2013. Accounting for cohort-specific variable growth in fisheries stock assessments: A case study from south-eastern Australia. Fisheries Research, 142: 27–36. Elsevier BV. <http://dx.doi.org/10.1016/j.fishres.2012.06.021>.

Worm, B., Barbier, E. B., Beaumont, N., Duffy, J. E., Folke, C., Halpern, B. S., and Jackson, J. B. *et al.* 2006. Impacts of biodiversity loss on ocean ecosystem services. Science, 314: 787–790. <http://www.sciencemag.org/cgi/doi/10.1126/science.1132294>.

Øigård, T. A., and Skaug, H. J. 2014. Fitting state-space models to seal populations with scarce data. ICES Journal of Marine Science. Oxford University Press (OUP). <http://dx.doi.org/10.1093/icesjms/fsu195>.


