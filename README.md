# Exploring the Correlation between Solar Activities and Earth's Global Temperature

## Repository Description : 
1. Gilbert Adriel Tantoso (gilb007@e.ntu.edu.sg / U2320621D)
2. Lionel Owen Wijaya (lwijaya001@e.ntu.edu.sg / U2320502B)
3. Melisa Lee (mlee100@e.ntu.edu.sg / U2320732A)

School of Computer Science and Engineering
Nanyang Technological University

April 2024

This repository is submitted to Nanyang Technological University as part of a graded assignment for the course SC1015 (Introduction to Data Science & Artificial Intelligence).

## Repository Contents : 

### FDAC Team03 : 
1. FDAC_Group3_Mini Project.ipynb
2. README.txt
3. Sunspots.csv
4. GlobalTemperatures.csv
5. annual-co2-emissions-per-country.csv
6. Presentation File Mini Project.pdf

### File Description : 
FDAC_Group3_Mini Project.ipynb

	A jupyter notebook containing the main source code for the project. 
 
README.txt

	Basic information about the project repository.
 
Sunspots.csv

	Dataset for number of sunspots
 
GlobalTemperatures.csv

	Dataset for global temperature
 
annual-co2-emissions-per-country.csv

	Dataset for annual carbon dioxide emission
 
Presentation File Mini Project.pdf

	A copy of our presentation file
### Background:
In recent years, global temperature has been increasing significantly. Our project aims to analyse this temperature and find the factors that affect it. One factor that we hypothesise to be correlated is the solar activity level. The level of solar activity is closely related to the number of sunspots (black dots on the Sun's surface). Thus, a dataset containing sunspot number is used for this analysis.

### Problem definition :
* Is there any correlation between Earth’s surface temperature and the Solar activity level of the sun?
* Are there any other contributing factors to Earth’s surface temperature?
  
### Content of the Notebook :
* Analysis of Sunspot
   * Periodic pattern of the number of sunspots was observed .This was shown using lag plot, which produced a non-random structure and autocorrelation plot which gives the lag value. Further exploratory work was done on the spread of sunspot data (IQR).
   * Rolling average technique was used to smoothen out the sunspot graph, showing the underlying trend of solar activity level.
* Correlation of Sunspot and Temperature
   * Global average temperature and number of sunspots were compared and the correlation was calculated.
* CO2 analysis
   * Global CO2 emissions over the years were plotted and compared against average global temperature and the correlation was calculated.
* Temperature prediction
   * Using multivariate linear regression, a linear model, which uses CO2 emission level and sunspot number as parameters, was created.

### Conclusion:
* Solar activity level shows a periodic pattern of 11 years.
* Speed of change of solar activity is fastest during peak solar activity level.
* There is a low, but apparent correlation between solar activity level and global temperature.
* The correlation was especially highlighted during “Dalton Minimum” (Lowest solar activity and very low global temperature period).
* There is an unexplained temperature increase which does not follow the solar activity level pattern in the 1960s.
* Increase in temperature was due to steep increase in CO2 global emission.
* CO2 global emission overshadows solar activity's effect on global temperature.
* Multivariate regression can be used to build temperature prediction models using CO2 global emission and number of sunspots as parameters.

 
## References :

https://www.kaggle.com/code/shubhammaheshwari1/sunspots-analysis/notebook
https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data
https://ourworldindata.org/co2-emissions
https://www.geeksforgeeks.org/lag-plots/
https://www.geeksforgeeks.org/python-pandas-plotting-the-autocorrelation-plot/
https://www.geeksforgeeks.org/how-to-make-a-time-series-plot-with-rolling-average-in-python/
