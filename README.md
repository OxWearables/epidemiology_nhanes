# Epidemiology in NHANES - Practical

## About this repository

This repository provides a **worked example of using wearables data available in NHANES for an epidemiological analysis associating daily step count with the risk of all-cause mortality**. Analyses are based on [this paper](https://journals.lww.com/acsm-msse/fulltext/2024/10000/self_supervised_machine_learning_to_characterize.9.aspx) conducted in the UK Biobank.

The included R markdown files describe: - (1) Exploring the NHANES accelerometer data - (2) Conducting an analysis associating daily step count with the risk of all-cause mortality

Visual inspection of the data is invaluable for understanding what the code is doing. Add statements to get a feel for the data as you work through the tutorials (e.g. `head()`, `str()` statements in R).

## What is this repository **not**?

Analytic decisions should be made in the context of each research project. Choices in this repository reflect choices of the authors in the linked papers and the code authors, and should not be interpreted as definitive or widely generalisable.

## Instructions for participants of the 2024 Reproducible Machine Learning of Wearables in Health Data Science course

I. Launch JupyterLab by navigating to <https://wearables2024.bmrc.ox.ac.uk/>

II. Clone the repository by opening the relevant link to your group: \
    **Group A:** <https://wearables2024-1.bmrc.ox.ac.uk/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FOxWearables%2Fepidemiology_nhanes&urlpath=rstudio%2F&branch=main> **Group B:** [https://wearables2024-2.bmrc.ox.ac.uk/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FOxWearables%2Fepidemiology_nhanes&urlpath=rstudio%2F&branch=main](https://wearables2024-1.bmrc.ox.ac.uk/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FOxWearables%2Fepidemiology_nhanes&urlpath=rstudio%2F&branch=main){.uri}

    OR

III. Open a Terminal instance from JupyterLab (File \> New \> Terminal) and then run:

``` shell
$ git clone https://github.com/OxWearables/epidemiology_nhanes.git
```

IV. To work with the repository, change the directory into the repository:

``` shell
$ cd epidemiology_nhanes
```

V. Open an RStudio session from JupyterLab (File \> New Launcher \> RStudio)

VI. You can now open and run the R markdown files from the `epidemiology_nhanes` directory located on the bottom right panel (Files).

## Question? Bugs?

If you have a question, feel free to add an issue on GitHub.

There are probably bugs. If you find them, please let us know! Again, add an issue on GitHub.

## Credits

This repository was generated for use in the Reproducible Machine Learning of Wearables in Health Data Science course by Ben Maylor and Charilaos Zisou, using material by Rosemary Walmsley and Junayed Naushad, with contributions and advice from Ondrej Klempir, Aiden Doherty, and Ben Busby.
