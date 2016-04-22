Summary
=======

Introduces the multinomial likelihood for fisheries data and explains its weaknesses (a) cannot replicate correlations found in the data and (b) not self-weighting (i.e., parameters that weight the composition data cannot be estimated inside the model). The distribution was designed for discrete counts, but in the application of fisheries is being used for continuous data (e.g., proportions that range from zero to one and must sum to one). Three alternative distributions are proposed: (1) multivariate normal (which must ignore that all values lie between zero and one and must sum to one), (2) Dirichlet (which does not allow for positive correlations), and (3) logistic-normal.

Introduction
============

Within compositional data, cvs decline with increasing proportions, which is true of the multinomial distribution with expected value \(p\) and sample size \(N\):

\[[\frac{(1-p)}{(pN)}]^{0.5}\]

Problems with multinomial (Hrafnkelsson and Stefánsson, 2004)
-------------------------------------------------------------

Problems arise because the multinomial distribution assumes that the data is a single simple random sample from the total, of which can characterize the population. Instead the random samples are comprised of many individual tows or sets.

    * overdispersion
    Decreasing $N$, such that it is smaller than the actual sample size can help to address
    the problem of overdispersion. Methods have been developed to decrease $N$ in a less
    ad hoc manner, such as using an empirical relationship with the number of trips sampled
    [@Crone1998] or an algorithm to correct $N$ using output from an initial run of the stock
    assessment [@McAllister1997].


    * correlation: With data originating from many individual tows or set, the fish
    within a tow or set are more like each other than fish from different tows or sets
    leading to intra-haul correlation [@Pennington1994]. For example, the proportion of fish
    of length 20 cm in a composition sample is correlated with the proportion of length 21 cm
    fish [@Hrafnkelsson2004]. 
    Correlations reduce the amount of information in the data and therefor the amount of weight
    given to the data should also be reduced. Ignoring this and using a traditional weighting
    scheme with the multinomial can lead to poor fits to the abundance data. 
    Correlations are often negative and positive, which is inconsistent
    with the multinomial likelihood which only produces small negative correlations.

    $$-[\frac {p_b p_c} {(1-p_b)(1-p_c)}]^{0.5}$$

    where $p_c$ and $p_b$ are the expected values in bins $b$ and $c$.

The effective sample size for the composition can be defined as the sample size that would be required to produce the se of the estimated mean from the data if the data were to have came from a simple random sample from the total.

Errors between the observation and the truth lead to observation error, but stock assessment scientists must also think about the process error involved which will lead to the added difference between the observations and the truth plus the difference between the truth and the predicted.

Hrafnkelsson, B., and Stefánsson, G. 2004. A model for categorical length data from groundfish surveys. Canadian Journal of Fisheries and Aquatic Sciences, 61: 1135–1142.
