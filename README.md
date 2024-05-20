Melchizedek Ackah-Blay
2024-04-14

## Project Overview
The Behavioral Risk Factor Surveillance System (BRFSS) is the nation’s premier system of health-related telephone surveys that collect state data about U.S. residents regarding their health-related risk behaviors, chronic health conditions, and use of preventive services. Established in 1984 with 15 states, BRFSS now collects data in all 50 states as well as the District of Columbia and three U.S. territories. BRFSS completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world. By collecting behavioral health risk data at the state and local level, BRFSS has become a powerful tool for targeting and building health promotion activities.

The following analysis seeks to identify target populations for physical health interventions. In order to identify these target populations, we would like to perform statistical testing in order to determine whether or not the interventions should differ across different demographics. One demographic variable we are interested in looking into is sex.

The BRFSS includes a section on the Health-Related Quality of Life. In order to measure the "Number of Days Physical Health was Not Good", respondents were asked: Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? This question will be used as a proxy to measure overall physical health for survey respondents, where the higher the number of days indicated, the lower overall physical health. The following analysis seeks to determine whether the Number of Days Physical Health was Not Good is greater in males, compared to females.


## Research Question for Analysis:
Does the number of days of poor physical health differ between males and females in the United States? This research is significant as it aims to identify potential disparities in health outcomes between different demographic groups, which can inform the design of targeted interventions and policies. By analyzing the Behavioral Risk Factor Surveillance System (BRFSS) data, we aim to understand if there are gender differences in the number of days individuals report experiencing poor physical health. This information can help public health officials, healthcare providers, and policymakers develop more effective health promotion strategies and address health equity concerns.
Objectives

## Data Cleaning and Preparation:
- Import the BRFSS dataset.
- Recode specific values in the "Number of Days Physical Health Not Good" variable to NA.
- Create a new variable to differentiate between males and females.

## Exploratory Data Analysis:
- Calculate the number of observations and variables.
- Recode the "Number of Days Physical Health Not Good" variable.
- Calculate the mean number of days of poor physical health.
- Determine the percentages of males and females in the dataset.

## Data Visualization:
- Create a histogram to show the distribution of the number of days of poor physical health.
- Create a boxplot to compare the number of days of poor physical health between males and females.

## Hypothesis Testing:
- Conduct a two-sided t-test to determine if there is a significant difference in the mean number of days of poor physical health between males and females.

## Steps Taken

Data Cleaning and Preparation:
- Importing Data: Imported the BRFSS dataset into R.
- Recode Values: Reassigned values indicating "None" (88), "Don’t know/Not sure" (77), and "Refused" (99) to NA for the "Number of Days Physical Health Not Good" variable.
- Create Gender Variable: Created a new variable, "SEX2," based on the existing "SEX" variable, where 1 represents "Male" and 2 represents "Female".

Exploratory Data Analysis:
- Number of Observations and Variables: Determined that the dataset consisted of 414,509 observations and 18 variables.
- Recode Verification: Verified the recode of the "Number of Days Physical Health Not Good" variable by checking the unique values.
- Mean Calculation: Calculated the mean number of days of poor physical health.
- Gender Percentages: Calculated that approximately 69.45% of individuals were female and 30.55% were male.

Data Visualization:
- Histogram Creation: Created a histogram to visualize the distribution of the number of days of poor physical health.
- Boxplot Creation: Created a boxplot to compare the number of days of poor physical health between males and females.

Hypothesis Testing:
- Two-Sided T-Test: Conducted a two-sided t-test to test the hypothesis that there is no difference in the mean number of days of poor physical health between males and females
