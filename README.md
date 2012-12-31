monomol
=======

The expected maximum number of OTUs can be predicted with estimating the asymptote values in monomolecular model 
(Larue et al. 2005) as following:
OTUs=α (1-β•e-k•n)
 where the α (asymptote), β and k values were estimated using the nonlinear least squares method with R.
 The value of n and OTUs represents the number of unique sequences and OTUs, respectively. 
 The rarefaction curve is proposed to break into piecewise function, which switched from linear 
 to monomolecular at a break point. The number of OTUs could exceed the total unique species if 
 only a monomolecular curve is used. However, the asymptote values were varied over a large range 
 by assigning different break points. The rarefaction curve is switched from linear to monomolecular 
 model, but the estimated asymptote varied with the break point values in large range. For example, 
 the estimated asymptote for archaea, indicating maximum taxonomic abundance, ranged from 1336 to 1756 
 with different break point values (Fig. S1). Values of t for monomolecular model fitting increased while 
 break point values increased from zero, since the fitting of rarefaction curve with monomolecular model 
 was improved by removing the linear fragment. However, the t value reached to maximum and decreased while 
 break value at 390 since the decrease of free degree. Hence, the estimated asymptote value while break 
 value at 390 were regarded as the optimized asymptote value and the expected maximum taxonomic abundance 
 for Archaea. All the estimated asymptotes of rarefaction curve were determined through optimizing break 
 point values by evaluating t values of fitting with R code available in the supplementary materials. 
