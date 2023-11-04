# Israelis-and-Palestine-conflict
### Table of content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools used](#tools-used)
- [Data cleaning/preparation](#data-cleaning/preparation)
- [Exploratiory data analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)

### Project Overview
This data analysis project aims to provide insight into the conflict between Palestine and Israel from the year 2000 -2021

![Palestine israel dashboard](https://github.com/Uchenna-eucharia/israelis-and-palestine-conflict/assets/55831056/84f52cd3-1e38-420e-9b59-f3f4556ed08b)

### Data Source
Palestine body count: The primary dataset used for this analysis is the "Palestine body count.csv" file containing detailed information about 
injuries and fatalities data from both sides from 2000 - 2021. It has a year, month, and number of people killed and injured in Israel and Palestine.

### Tools used
- Python - Data cleaning and analysis
- Powerbi - creating report
  
### Data cleaning/preparation
In the initial data preparation phase, we performed the following:

1. Data loading and inspection

2. Handling missing values

3. cleaning and formatting

### Exploratory data analysis
EDA involves exploring the data to answer key questions such as
- Total casualties
- Total deaths
- Total injuries
- Total killed by years of both countries

### Data analysis

  ```
df["Palestinians Casualties"] = (df["Palestinians Killed"]+ df["Palestinians Injuries"])
df["Israelis Casualties"] = (df["Israelis Killed"]+ df["Israelis Injuries"])
 ```


