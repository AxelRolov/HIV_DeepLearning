#  Drug Resistance Prediction Using Deep Learning Techniques on HIV-1 Sequence Data

This repository contains code used to train and evaluate deep learning classifiers for HIV-1 drug resistance prediction from sequence data (Steiner et al., 2020, _in review_). All data is publicly available via the [Stanford HIV Drug Resistance Database](https://hivdb.stanford.edu). All code was written in R, and all classifiers were developed and trained using the R interface to [Keras](https://keras.rstudio.com). Other packages used include the [IML](https://cran.r-project.org/web/packages/iml/vignettes/intro.html) package for model interpretation and [ggplot2](https://ggplot2.tidyverse.org) for data visualization.

**Author:** Margaret C. Steiner ([GitHub](https://github.com/maggiesteiner)), Computational Biology Institute, The George Washington University

Copyright (C) 2020, Margaret C. Steiner

**Citation information:** 
When referencing this project, please cite our recent publication (citation & link will be added here).

## Code and Data Files

Below are brief descriptions of the files included in this repository.

### Data Scripts

CSV files: input from Stanford database (https://hivdb.stanford.edu). Data cleaning files: generate drug-specific datasets from CSV files. Sequence_maker.R: Functions to create FASTA files. FASTA script files: scripts to generate fastas from output of data cleaning files.

### FASTA Files

Output of data script files.

### Test Scripts

Scripts to train & evaluate all classifiers.

### Figures

Scripts used to generate figures. imp_plots_script.R: top-20 feature importance plots. new_impplots_script_sequence.R: whole-gene feature importance plots. roc_script_mlp.R, roc_script_cnn.R, roc_script_brnn.R: ROC curve plots. histogram_script.R: histograms from feature importance data.

### Results

Output files of test scripts.

## Helpful Resources

For readers 
