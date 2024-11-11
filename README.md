# Outbreak Analytics: Project Overview

During the summer of 2024, I completed a three-month undergraduate internship under the supervision of Mircea Sofonea at the PCCEI lab in Montpellier. My initial focus was on examining biases and uncertainties in estimating key epidemiological metrics (such as serial interval and incubation period) during the early stages of infectious disease outbreaks.
As my work progressed, it expanded to include the analysis of a pilot intervention — a short-term intervention applied early in an outbreak to assess its impact — using modeling approaches. I also conducted an in-depth analysis of one of the models I developed, revealing theoretical insights related to lockdown interventions. Finally, I have continued these investigations as part of a master’s course project in October 2024.

This Git repository contains the codes from my internship in the "internship" folder. It also includes the code for my master’s project in the "master_project" folder.

## Uncertainty in Epidemiology: From Estimation Challenges to Public Health Intervention Evaluation
### Internship Project

The internship project is organized into three main sections:

- Regression Analyses: This section includes three simple linear regression analyses investigating relationships between key epidemiological estimates: the mean serial interval and incubation period for the COVID-19 outbreak in 2020, and the mean incubation period for the Mpox epidemic in 2022, analyzed as functions of the data collection period. No correlation was found between the serial interval and the data collection period for COVID-19, and opposite correlations were observed for the incubation period between COVID-19 and Mpox. Therefore, our initial hypothesis about these relationships was not supported, indicating the need for further investigation to uncover and understand potential biases affecting real-time data collection during outbreaks.

- Pilot Intervention Study: In this section, we developed a modified SIR model to explore the design of a pilot intervention—an innovative approach to evaluate intervention effectiveness during outbreaks. The code calculates the minimum sample size required to assess the impact of a lockdown intervention given specific model parameters.

- Model Analysis: This part includes a detailed numerical analysis of the modified SIR model used in the pilot intervention study.

## Optimizing Public Health Intervention Impact: A Modeling Approach
### Master’s Course Project

Building on the third part of my internship project, this section advances the analysis by deriving analytic expressions and results from the modified SIR model. Here, I defined model limits not only through numerical simulations but also by confirming them analytically. The notebook provided in the folder contains the code for generating the figures included in the report.

For any questions or if you’re interested in discussing this work, feel free to contact me at paul.petit@ens-lyon.fr.
