# Stuart_etal_2024_InsectConsDiv

All code used to analyse data and prepare figures for Stuart, O. et al. (2024) "Gene flow stimulates recovery of reproductive fitness in a captive bred insect." *Insect Conservation and Diversity*.  

The code is contained in the "Analysis" folder and is divided into two `.Rmd` files.

- `LHISI_Phenotype_Data_Cleaning.Rmd`: here I make some quick summaries of the phenotypic measurements taken from ZIMS and clean any obvious errors. This script generates the input file for the next `.Rmd` file: `Data/cleaned_phenotype_data.Rdata` which is included in this repository
- `LHISI_Phenotype_Data_Modelling.Rmd`: all actual modelling and plotting goes here.

The raw data used as input for `LHISI_Phenotype_Data_Cleaning.Rmd` is available on request: oliver.stuart93@gmail.com
