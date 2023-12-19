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
  
This repository is dual licensed under the [Open Government v3]([https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) & MIT. All code can outputs are subject to Crown Copyright.
