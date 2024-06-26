# Replication of "Anti-Immigrant Rhetoric and ICE Reporting Interest: Evidence from a Large-Scale Study of Web Search Data"

This project covers replications and extensions of [this article](https://www.cambridge.org/core/journals/british-journal-of-political-science/article/abs/antiimmigrant-rhetoric-and-ice-reporting-interest-evidence-from-a-largescale-study-of-web-search-data/AF982680AEC49AE65CACFD73352A44AD) on the relationship between media cues and public interest in reporting suspected unauthorized immigrants to Immigration and Customs Enforcement (ICE). The study uses Google Trends and Bing search data, combined with automated content analysis of cable news transcripts. Our replication only uses Google Trends data, and reuses the original paper's model of news transcripts.

After replicating some of the paper's major findings, we questioned whether some of their unproven claims were actually true.

## Requirements

R, with the following packages: tidyverse, modelr, modelsummary, knitr.

## Running the Code

To reproduce results, open and run the `recreating_immigrant_plots.Rmd` file.

## Files

* `recreating_immigrant_plots.Rmd`: Main analysis code in Rmarkdown format  
* `recreating_immigrant_plots.Rmd`: Rendered output from running `recreating_immigrant_plots.Rmd` containing all results and figures in the paper  
* `from_google_trends/`: CSV files containing data downloaded from Google Trends
* `from_replication_files/`: Files containing data and the model from the original paper
