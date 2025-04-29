# DS4002-CS3 Predicting Chicago Taxi Ridership 

This repository contains all the code scripts, data, and addtional materials needed to complete a case study of predicting Chicago Taxi Ridership. A hook document outlining the motivation behind this case study and its deliverables can be found as "Hook.pdf". A rubric detailing all components and analysis needed to complete this case study can be found as "Case Study Rubric.pdf"

## Data Folder
This folder contains both an uncleaned, raw version of the taxi ridership data from the Chicago Data Portal (https://data.cityofchicago.org/Transportation/Taxi-Trips-2013-2023-/wrvz-psew/about_data) and a cleaned version of this dataset that will set you up to build the SARIMA and BSTS models. **Note:** if opting to use the website, there is a built in query option that may faciliate you obtaining the data yourself

## Scripts Folder
This folder contains all the code scripts needed to conduct this case study. This includes "Data Cleaning and Validation Graph.R" which will be used to clean the data and create some EDA plots,"BSTS model and evaluation metric.R" which will be used to build and calculate the evaluation metrics for the BSTS model, and "SARIMA model and evaluation metrics.R" which will be employed to build and calculate the evaluation metrics for the SARIMA model.

## Reference Materials Folder
This folder holds all reference materials such as reports, blog posts, and articles that provide supplemental information about declining Taxi ridership[1][2]. There are also a few files detailing how to build a SARIMA[3] or BSTS[4] model and other background information on these models.

## References

[1] Badgujar, S. (2022, July 28). Chicago public taxi data analysis (over 200 million rows!). Medium. https://medium.com/@sumeetbadgujar/chicago-public-taxi-data-analysis-over-200-million-rows-f0b4549a09bf

[2] Cab Drivers United. (n.d.). Run off the road: Chicago’s taxi medallion foreclosure crisis. https://actionnetwork.org/user_files/user_files/000/016/049/original/Medallion_Report_(FINAL).pdf

[3] GeeksforGeeks. (2023, November 17). SARIMA (Seasonal Autoregressive Integrated Moving Average). GeeksforGeeks. https://www.geeksforgeeks.org/sarima-seasonal-autoregressive-integrated-moving-average/

[4] Scott, S. L. (2017, July 11). Fitting Bayesian structural time series with the bsts R package. The Unofficial Google Data Science Blog. https://www.unofficialgoogledatascience.com/2017/07/fitting-bayesian-structural-time-series.html
