# BIOMD0000000249: restif06

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000249.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000249.git@20140916`


# Model Notes


This is the model described in the article:  
**Integrating life history and cross-immunity into the evolutionary dynamics of pathogens. **   
Restif O, Grenfell BT. _Proc Biol Sci._ 2006 Feb 22;273(1585):409-16.
PMID:[16615206](http://www.ncbi.nlm.nih.gov/pubmed/16615206),
doi:[10.1098/rspb.2005.3335](http://dx.doi.org/10.1098/rspb.2005.3335);  
**Abstract:**   
Models for the diversity and evolution of pathogens have branched into two
main directions: the adaptive dynamics of quantitative life-history traits
(notably virulence) and the maintenance and invasion of multiple,
antigenically diverse strains that interact with the host's immune memory. In
a first attempt to reconcile these two approaches, we developed a simple
modelling framework where two strains of pathogens, defined by a pair of life-
history traits (infectious period and infectivity), interfere through a given
level of cross-immunity. We used whooping cough as a potential example, but
the framework proposed here could be applied to other acute infectious
diseases. Specifically, we analysed the effects of these parameters on the
invasion dynamics of one strain into a population, where the second strain is
endemic. Whereas the deterministic version of the model converges towards
stable coexistence of the two strains in most cases, stochastic simulations
showed that transient epidemic dynamics can cause the extinction of either
strain. Thus ecological dynamics, modulated by the immune parameters,
eventually determine the adaptive value of different pathogen genotypes. We
advocate an integrative view of pathogen dynamics at the crossroads of
immunology, epidemiology and evolution, as a way towards efficient control of
infectious diseases.

This version of the model can be used for both the stochastic and the
deterministic simulations described in the article. For deterministic
interpretations with infinite population sizes, set the population size _N_ =
1. The model reproduces the deterministic time courses. Stochastic
interpretation with Copasi UI gave results similar to the article, but was not
extensively tested. The initial conditions for competition simulations can be
derived by equilibrating the system for one pathogen and then adding a
starting concentration for the other.

Originally created by libAntimony v1.3 (using libSBML 4.1.0-b1)


