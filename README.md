# Sick without signs. Subclinical infections reduce local movements, alter habitat selection, and cause demographic shifts

https://doi.org/10.5281/zenodo.13934755

Give a brief summary of dataset contents, contextualized in experimental procedures and results.

## Description of the data and file structure

**This R-Project contains the following code files (in folder R):**

*01_cmr_data_cleaning:  Code to clean the raw capture-mark-recapture data*

*02_pathogen_data_cleaning* *Code to clean the raw pathogen data*

*03_movement_data_cleaning*: *Code to clean and filter the raw ATLAS movement data*

*04_ctmm_models*: Code to prepare data, applying continuous time movement models (incl. model selection) on movement data. Moreover, track reconstruction is performed

*05_HMM_behaviour_models*: Code to perform Hidden-Markov models (HMMs) to assess behavioural states from movement data

*06_ISSF_habitat_selection_models*: Code to perform Integrated Step Selection Functions (iSSF) to assess habitat selection during foraging behaviour

*07_multivariate_analyses:* Code to perform multivariate analyses on morphological traits in relationship to infection status

*08_population_models_nimble*: (nimble)-Code to perform candidate Multievent models, including model selection to obtain the best fitting models.

*09_simulation_study*: (nimble)-Code to perform simulation study on Multievent models, assessing if we could retrieve unbiased estimates given our sampling regime

*10_resampling_30min:* Code to perform analyses on resampled data (resampled to 30 minutes), to verify that we could not detect subtle parasite-induced effects on movement behaviour by using coarser resolution

**This repository contains the following data files (in folder data-raw)** :

*birds_cmr_2019*: capture-mark-recapture data collected in 2019

*birds_cmr_2020*: capture-mark-recapture data collected in 2020

*birds_cmr_2021*: capture-mark-recapture data collected in 2021

*birds_cmr_2022*: capture-mark-recapture data collected in 2022

*birds_cmr_2023*: capture-mark-recapture data collected in 2023

*swallows_filtered*: Filtered movement data of swallow species (full data set published on movemebank: Movebank-ID: 3053965481)

*pathogen_data*: Blood parasite infection data of swallow species

*stacked.tiff*: Stacked environmental covariates used in anylses (in folder geo-proc)

## Sharing/Access information

NA

## Code / Software

Multievent models (08_XXX) and simulations (09_XXX) require package nimble (de Valpine et al., 2017): [https://doi.org/10.1080/10618600.2016.1172487](https://doi.org/10.1080/10618600.2016.1172487)

Please see R scripts for additional packages used in processing data.
