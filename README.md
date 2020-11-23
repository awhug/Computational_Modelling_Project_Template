# Generic Computational Modelling Project Template

This folder structure aims to ensure replicability for experiments involving computational modelling from design to publication, and hopefully save time and heaches in the long run. This project template (and notes below) are from Dani Navarro (@djnavarro), Andy Perfors (@perfors), and Charles Kemp (@cskemp), presented at the [2018 Complex Human Data Summer School](https://github.com/cskemp/chdss2018).

People may differ in their preferences for organising the folders, but the key goals of this template are:

*   Clear organisation that is stable from project to project;
*   Shared structure among people on the same project;
*   Folder organisation that parallels and supports your workflow.

### Folder Details

There are four main folders, containing sub-folders. Each of the main folders is modularisable (e.g. for projects involving multiple experiments, copy the sub-folders into 'expt1', 'expt2', etc.)

#### A. Docs

*   `docs/resources`: Any documents you make for yourself, e.g. describing design decisions, or figures (that are not data or model outputs).
*   `docs/ethics`: All ethics and ethics related documents.
*   `docs/readings`: Relevant papers and your notes on them — your future self will thank you! (if you use LaTeX or a bibliography manager, integrate this as appropriate).
*   `docs/papers`: This is what you write. This is also expandable into further sub-folders (e.g. for multiple submissions).
*   `docs/talks`: Any talks or presentations (including posters).

#### B. Experiment

*   `experiment/resources`: Experiment-specific resources like stimuli (through the process of development)
*   `experiment/code`: Code for actually implementing the experiment (e.g. Javascript, qualtrics, etc). If it’s not on a computer then you probably do not need this.
*   `experiment/data`:  Raw data in a easy to read file (e.g., csv) along with a description of the file (definition of variables, etc). It is *very important* to keep the raw data separate from any analyses, so you can always go back to it if you need.

#### C. Analysis

*   `analysis/resources`: Documents explaining analysis choices, etc (you may not need this).
*   `analysis/code`: All of the analysis code.
*   `analysis/data`:  Output datafiles from your analysis code (e.g. subsetted data, cleaned files, etc).
*   `analysis/figures`: Figures generated from doing the data analysis.

#### D. Models

This folder has a similar structure to the analysis folder, but contains everything associated with any of your computational models (not for analysing the data — rather, for theorising about the models).

*   `models/resources`: Documents explaining and/or illustrating modelling choices.
*   `models/code`: All of the modelling code.
*   `models/data`:  Output datafiles from your models (e.g. simulations, model criticism, etc).
*   `models/figures`: Figures generated from running your models.

### Notes

Git does not allow empty folders (as in this project template should be), so each folder has an empty `.gitkeep` file that can safely be removed once the template has been downloaded.
