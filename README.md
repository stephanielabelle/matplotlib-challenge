# Pymaceuticals Inc. - Module 5 Challenge
---
## Goal of this Study
Squamous cell carcinoma (SCC) is a common form of skin cancer.  The pharmaceutical company Pymaceuticals have developed a new SCC treatment called Capomulin.  
This analysis attempts to assess the performance Capomulin against other SCC drug regimens for treatment of squamous cell carcinoma (SCC) in mice.

### Location of Files
The raw [mouse data](Pymaceuticals/data/Mouse_metadata.csv) and [study results](Pymaceuticals/data/Study_results.csv) are available in the Pymaceuticals data folder.

The [analysis](Pymaceuticals/pymaceuticals_capomulin.ipynb) is available in the Pymaceuticals folder under the name pymaceuticals_capomulin.

The analysis contains:

1. Analysis Summary
2. Merged Dataframe of mouse and study data
3. Summary statistics of tumour volume
4. Bar chart comparing the number of data timepoints collected by drug regimen
5. Pie chart comparing 'sex' distribution of study mice
6. Quatitative analysis of potential outliers in Capomulin, Ramicane, Infubinol, and Ceftamin treatment groups
7. Box plot of final tumor volume of Capomulin, Ramicane, Infubinol, and Ceftamin treatment groups
8. Line plot visualizing tumor volume change vs time for single Capomulin treated mouse
9. Scatter plot of average tumor volume vs mouse weight for Capomulin treated cohort
10. Pearson's correlation coefficient and linear regression model of average tumor volume vs mouse weight for Capomulin treated cohort
