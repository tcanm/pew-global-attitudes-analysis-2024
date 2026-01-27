# Censorship Orientations and Perceptions of China
## Analysis of the Pew Global Attitudes Survey (2024)
### Overview

This repository contains code for a statistical analysis examining the relationship between cross-national perceptions of China and domestic attitudes towards censorship. Using data from the Pew Research Center’s Spring Global Attitudes Survey (2024), the analysis investigates how support for internet freedom, press freedom, and free speech correlates with favourability toward China across 35 countries.

The study is motivated by scholarship in social psychology, political science, and critical social theory suggesting that perceptions of foreign states may reflect domestic value orientations and processes of in-group / out-group formation, rather than purely objective evaluations of governance practices.

### Research Question

Do cross-national perceptions of China correlate with attitudes toward freedom from censorship, and what geographic or value-based patterns emerge between nations?

### Data

The analysis is based on a total sample of **n = 41,503 respondents** 

- Country-level statistics are calculated using Pew-provided survey weights to ensure cross-national comparability

- Favourability toward China is measured on a four-point ordinal scale

- Attitudes toward freedom from censorship are operationalised using Pew’s grouped variables on internet freedom, press freedom, and free speech

- Raw survey data is provided in the ``data/`` directory. The dataset is used in unmodified form. An accompanying codebook can be found in the ``docs/`` folder 

### Methods

- Country-level and regional analysis using weighted proportions and distributional comparisons of ordinal survey responses 
- Construction of a composite censorship-orientation score
- Non-parametric statistical tests (Spearman’s ρ, Kruskal–Wallis, Kolmogorov–Smirnov)