# GitHub repository for materials associated with the research project "Attribution of undesirable character traits, rather than trait-based dehumanization, predicts punishment decisions."

These materials are a computationally reproducible version of the paper:

Brennan, R.A., Enock, F.E. & Over, H. (2023). Attribution of undesirable character traits, rather than trait-based dehumanization, predicts punishment decisions.

The file manuscript.Rmd is an R markdown file that will perform all analyses and figure creation, and produce a pdf version of the manuscript.

The full repository can be downloaded (cloned), and will automatically download the required packages and data files, depending on the level of analysis requested.

The 'docker' directory contains a Dockerfile and instructions for making a local computationally reproducible version of the analysis. In addition, the Docker environment is set up to run automatically on a remote server via Github Actions, each time a change is made (i.e. on a 'commit' to the repo). The output document is then posted back to the main repository (manuscript.pdf). If you want to make changes to the analysis and have these build automatically, you can fork the repository into your own account.

![autobuild](https://github.com/robraonain/DualModel-Criminals/workflows/autobuild/badge.svg)