# Andhra-Pradesh-Elections-2019
### This repository consists of Data visualizations of Andhra Pradesh Elections in the year 2019.
### `AP Elections visualizations.ipynb - Colab.pdf` file contains all the Visualizations that I did.
### 1. Handling Datasets:
- The raw data file `data.csv` was from Kaggle.
- Then I handled the missing values and maded `data 2.csv` file.
- After that, I corrected and matched the constituency names in the dataset with the constituency names in the Map Shapefile and made `corrected_data.csv` file.
- later, i just seperated the corrected_data.csv file in two seperate files by the years i.e, `election_results_2014.csv` and `election_results_2019.csv` files.

### 2. Andhra Pradesh Map Shapefile
- I got this shapefile from github itself `ANDHRA_PRADESH_ASSEMBLY.geojson`.
- There was a problem with the shapefile near the Rampachodavaram constituency and badrachalam (st) constituency during the bifurcation of Andhra Pradesh during 2014. So I corrected it and made it into a new file `ANDHRA_PRADESH_MERGED.geojson`.

### 3. Visualizations
- Andhra Pradesh Assembly Constituencies. (Total - 175)
- Age distribution of Election Participants using barplot.
- Age distribution of candidates by party using boxplot.
- Total Votes by each Constituency in 2019 using barplot.
- Candidates category frequency by sex using a Co-relation heat map.
- Map of 2019 Andhra Pradesh Assembly Election Results by party.






