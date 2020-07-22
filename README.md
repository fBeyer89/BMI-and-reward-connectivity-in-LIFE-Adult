# BMI_rew_connectivity

This repository contains the preprint, code and synthetic data for the project "Higher BMI, but not obesity-related genetic polymorphisms, correlates with lower structural connectivity of the reward network in a population-based study" by Beyer et al., 2020.

## Preprint on MedRxiv
The preprint can be found [here](https://www.medrxiv.org/content/10.1101/2020.05.06.20087577v1). During the revision, the manuscript underwent some changes, including subject selection, yet, the main analysis steps and results from the preprint remain valid.

## Analysis Code and synthetic data
We are not allowed to share the original data due to legal restrictions (i.e. no permission obtained to share genetic and imaging data). Therefore, we offer synthetic data, based on the original dataset, which can be used to reproduce the structure and key findings of the dataset. The code to generate the data is located in `synthpop_for_rew_connectivity.Rmd`. The synthetic data are in `synth_data.csv`. This script also contains comparisons of the distributions and models in the original and synthetic data.  
The code to reproduce the main analysis of the paper (association of BMI and reward network connectivity, genotype and BMI, genotype and reward network connectivity) is located in `Analysis_BMI_rew_connectivity.Rmd`.  
Full analysis code for the original data (cannot be run because we are not allowed to share those) is in `Analysis_BMI_rew_connectivity_real_data.Rmd`. Here, for privacy reasons, data paths to files have been deleted.
