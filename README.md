# Extract, Transform, Load

For this project, our team extracted data from a dataset that contained the last five years of H-1B visa (temporary work visa) & PERM (permanent residency application, also known as Green Card). The dataset was collected between October 1 through september 30 (fiscal year) by the US Department of Labor. We extracted data files for FY14 thru FY18. In addition to this dataset, the team also extracted data from the united nations human development report. Specifically, we downloaded csv files detailing unemployment, human development index (HDI), and education index by country for each year between 1990 and 2017. 

The data was cleaned to 32 columns from a starting set of 125 columns which has over 430,000 rows. This cleaned data from utilizing pandas in jupyter notebook was then loaded into the PostGreSQL database for use at a later date.
