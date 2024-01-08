
# BSOL sample project folder

This git repository contains a shell that should be used as the default structure for new projects
in the analytical team.  It won't fit all circumstances perfectly, and you can make changes and issue a 
pull request for new features / changes.

The aim of this template is two-fold: firstly to give a common structure for analytical projects to aid
reproducibility, secondly to allow for additional security settings as default to prevent accidental upload of files that should not be committed to Git and GitHub.

__Please update/replace this README file with one relevant to your project__

## To use this template, please use the following practises:

* Put any data files in the `data` folder.  This folder is explicitly named in the .gitignore file.  A further layer of security is that all xls, xlsx, csv and pdf files are also explicit ignored in the whole folder as well.  ___If you need to commit one of these files, you must use the `-f` (force) command in `commit`, but you must be sure there is no identifiable data.__
* Save any documentation in the `docs` file.  This does not mean you should avoid commenting your code, but if you have an operating procedure or supporting documents, add them to this folder.
* Please save all output: data, formatted tables, graphs etc. in the output folder.  This is also implicitly ignored by git, but you can use the `-f` (force) command in `commit` to add any you wish to publish to github.


### Please also consider the following:
* Linting your code.  This is a formatting process that follows a rule set.  We broadly encourage the tidyverse standard, and recommend the `lintr` package.
* Comment your code to make sure others can follow.
* Consider your naming conventions: we recommend `snake case` where spaces are replaced by underscores and no capitals are use. E.g. `outpatient_referral_data`

# Paramedics Feedback Analysis

## Overview

This repository contains the data analysis project for Paramedics Feedback provided by the Birmingham and Solihull ICB. The aim is to extract insights from textual feedback given by paramedic crews and visualize the frequency of specific terms and phrases to understand common sentiments and issues.

## Dataset

The analysis is based on feedback collected from 77 respondents, focusing on several aspects of ambulance services. The data includes responses to questions about the ease of access to GPs, the support services for avoiding unnecessary admissions, and the use of Same Day Emergency Care services, among others.

## Quarto Markdown Files

* **ParamedicsAnalysis.qmd**: The main Quarto markdown file presenting the detailed analysis, including methodology, results, and visualizations.
* **userinfo.qmd**: Provides background information on the project and data context.
* **howto.qmd**: Offers guidance on how to navigate through the dashboard.
* **contact.qmd**: Contains contact details to report issues or provide feedback.
  
## Analysis Workflow

* **Data Preprocessing**: Cleaning the feedback data, removing stop words, punctuation, and normalizing text.
* **Word Frequency Analysis**: Identifying the most frequently used unigrams and bigrams in the feedback.
* **Visualization**: Creating bar plots and word clouds to represent the frequency of the terms.

## Environment Details

To ensure compatibility and reproducibility, the following versions were used during the development of this project:

* **Python Version**: 3.11.5
* **JupyterLab Version**: 4.0.8
* **Quarto Version**: 1.4.514
* **Plotly Version**: 5.10.0
  Note:Plotly versions greater than 5.11 do not render the plots in the HTML files.
  
>>>>>>> 
This repository is dual licensed under the [Open Government v3]([https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) & MIT. All code can outputs are subject to Crown Copyright.
