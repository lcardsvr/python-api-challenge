# Module 6 Challenge

## Background


You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specialises in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumours received treatment with a range of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.


## WeatherPy Results


In this deliverable, a Python script was used to visualise the weather of over 500 cities of varying distances from the equator.

The code generated random geographic coordinates and the nearest city to each latitude and longitude combination.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

Latitude vs. Temperature

![Latitude vs. Temperature](/output_data/Fig1.png)

Latitude vs. Humidity

![Latitude vs. Humidity](/output_data/Fig2.png)

Latitude vs. Cloudiness

![Latitude vs. Cloudiness](/output_data/Fig3.png)

Latitude vs. Wind Speed

![Latitude vs. Wind Speed](/output_data/Fig4.png)


### Requirement 2: Compute Linear Regression for Each Relationship

Northern Hemisphere: Temperature (C) vs. Latitude

![Northern Hemisphere: Temperature (C) vs. Latitude](/output_data/NH_Temp_Lat_LR.png)

Southern Hemisphere: Temperature (C) vs. Latitude

![Southern Hemisphere: Temperature (C) vs. Latitude](/output_data/SH_Temp_Lat_LR.png)

Northern Hemisphere: Humidity (%) vs. Latitude

![Northern Hemisphere: Humidity (%) vs. Latitude](/output_data/NH_Humidity_Lat_LR.png)

Southern Hemisphere: Humidity (%) vs. Latitude

![Southern Hemisphere: Humidity (%) vs. Latitude](/output_data/SH_Humidity_Lat_LR.png)

Northern Hemisphere: Cloudiness (%) vs. Latitude

![Northern Hemisphere: Cloudiness (%) vs. Latitude](/output_data/NH_Cloudiness_Lat_LR.png)

Southern Hemisphere: Cloudiness (%) vs. Latitude

![Southern Hemisphere: Cloudiness (%) vs. Latitude](/output_data/SH_Cloudiness_Lat_LR.png)

Northern Hemisphere: Wind Speed (m/s) vs. Latitude

![Northern Hemisphere: Wind Speed (m/s) vs. Latitude](/output_data/NH_WindSpeed_Lat_LR.png)

Southern Hemisphere: Wind Speed (m/s) vs. Latitude

![Southern Hemisphere: Wind Speed (m/s) vs. Latitude](/output_data/SH_WindSpeed_Lat_LR.png)


## Results and analysis

The instructions were carried out as instructed, and the graphs below were obtained. Duplicate data was removed for Mouse g989, and the analysis was performed with the remaining data. 

The analysis reviewed four main regimes: Capomulin, Ramicane, Infubinol, and Ceftamin.

230 Mice underwent treatment with Capomulin, 228 with Ramicane, 178 with Infubinol, and 178 with Ceftamin.



The proportion of mice tested was almost the same between genders (51% Male and 49% Female)

![Male-Female tested percentage](Male_Female_Percentage.png)

The Drug Regimes with the lowest Tumor Volumes over time were Capomulin and Ramicane, with final mean tumour volumes of 36.667 mm3 and 36.191 mm3, respectively. The lowest performer was Infubinol, with last mean tumour volumes of 57.754 mm3.

![Box plots Final Tumor Volume per Drug Regime](Box_plot_Final_Tumor_DrugRegime.png)

Volume decrease over time is evident in a mouse undergoing Capomulin treatment, as depicted below.

![Tumor volume evolution in a Mouse under Capomulin Treatment](Tumor_Vol_time_Capomulin.png)

There is a strong correlation between the Average Tumor Volume and the Mice’s Weight. The correlation between mouse weight and the average tumour volume is 0.84

![Relation between Average Tumor Volume vs Mouse Weight](AvgTumorVol_Weight.png)


## Submission

1. Submitted and available in GitHub under https://github.com/lcardsvr/Module---5-Challenge

2. Written report is included in the Readme.md file 

3. Code for the submission is available under https://github.com/lcardsvr/Module---5-Challenge/blob/main/Pymaceuticals/pymaceuticals_starter.ipynb



