pangea
======

This is a repository of analyses for the PANGEA-HIV Phylodynamics Methods Comparison exercise. Datasets and instructions can be found [here](http://bit.ly/PANGEAHIVsim). The intention of this repository is to generate trees, evolutionary rates, *etc.*, so that more interesting things can be addressed in the (mere!) month for the first set of analyses to be completed.

* sequences: raw and processed sequence files
* raxmltrees: ML trees generated by RAxML
* lsd: clock-like trees generated by LSD, based on the RAxML trees
* mrbayestrees: input files for MrBayes and corresponding outputs
* phymltrees: input files for PhyML (assuming GTR+freerates(20))
* mixedmodel: BEAST XML files for Bethany's mixed epidemic model
* phytime: input files for phytime, using RAxML topologies rooted with rtt from ape
* skyride: skyrides based on LSD trees
* traits: M2 model fitting of M/F
* treeshape: Sackin's index and cherries for LSD trees
* treeshape_raxml: Sackin's index and cherries for RAxML trees