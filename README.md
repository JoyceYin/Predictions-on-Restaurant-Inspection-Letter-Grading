# Prediction on Restaurant Inspection Letter Grading in NYC

### Data Description:
-  Restaurant Inspection Results in 2022 <br>
https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j
-  Socio-economic Factors

      **Food Scrap Drop off Location**: https://data.cityofnewyork.us/Environment/Food-Scrap-Drop-Off-Locations-in-NYC/if26-z6xq <br>
      **Subway Station**: https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49 <br>
      **Rodent Inspection Results in 2021**: https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj <br>
      **Demography and Income from ACS Survey data**<br>
      **Social Mobility at taxi zone level** (source from class)
      
      
### Data Preprocess:
Totally, 16753 records with Grade A, 1354 records with Grade B, and 560 records with Grade C.
<br>
Applied data resampling (**SMOTE+ENN / SMOTE+Tomek**)

### Methodology:
Conducted **MultiLable Classification (Grade A, B, C)** and **Binary Classification (A, Not A)** in MultiLayer Perceptron Model <br>
Experiments with dropout unit from 0.2 to 0.5
