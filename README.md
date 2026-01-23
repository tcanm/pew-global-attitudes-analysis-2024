{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Information Freedom Values and Global Perceptions of China\
# Censorship Orientations and Perceptions of China
## Analysis of the Pew Global Attitudes Survey (2024)
### Overview

This repository contains code for a statistical analysis examining whether cross-national perceptions of China are associated with domestic attitudes toward censorship and freedom of expression. Using data from the Pew Research Center’s Spring Global Attitudes Survey (2024), the analysis investigates how support for internet freedom, press freedom, and free speech correlates with favourability toward China across 35 countries.

The study is motivated by scholarship in social psychology, political science, and critical social theory suggesting that perceptions of foreign states may reflect domestic value orientations and processes of in-group / out-group formation, rather than purely objective evaluations of governance practices.

### Research Question

Do cross-national perceptions of China correlate with attitudes toward freedom from censorship, and what geographic or value-based patterns emerge between nations?

### Data

The analysis is based on a total sample of **n = 41,503 respondents** 

Country-level statistics are calculated using Pew-provided survey weights to ensure cross-national comparability.

Favourability toward China is measured on a four-point ordinal scale.

Attitudes toward freedom from censorship are operationalised using Pew’s grouped variables on internet freedom, press freedom, and free speech.

Raw survey data is provided in the ``data/`` directory. The dataset is used in unmodified form. An accompanying codebook can be found in the ``docs/`` folder. 

### Methods

- Country-level and regional analysis using weighted proportions and distributional comparisons of ordinal survey responses 
- Construction of a composite censorship-orientation score
- Non-parametric statistical tests (Spearman’s ρ, Kruskal–Wallis, Kolmogorov–Smirnov)



}