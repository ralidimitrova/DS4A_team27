## Understanding the factors influencing COVID-19 vaccination uptake rates in the US


![DS4A_team27](/data/figures/cover.png)


Github repo for the DS4A capstone project #Team27.

## Directories:

`./project_docs` - final report. 


`./eda_final` - final data cleaning & EDA

   - *final_data_merging.ipynb* - final cleaning of merged df
   - *final_EDA.ipynb* - final EDA 


`./prediction_modelling` - Predicting vaccination rate in the US

  - *missing_data_imputation.ipynb* - missing data imputation
  - *final_modelling.ipynb* - model training, hyperparamaters optimasation, model selection and application of final model to test data. 


`./eda_notebooks` - all notebooks performing initial EDA on individual datasets

  - *00_vaccination_rate_us.ipynb* - extraction of the vaccination rate data (date: 03/10/21)
  - *01_vaccination_rate_us_visualisation.ipynb* - visualisation of the vacc rate using plotly
  - *02_covid19_severity_us.ipynb* - extraction and visualisation of the covid19 death/cases (date: 03/10/21)
  - *03_covid19_heath_disparity.ipynb* - health disparity data 
  - *10_covid19_datasets.ipynb* - initial merge of datasets for baseic EDA
  - *Hesitancy_SVI_Ethnicity.ipynb* - extraction and visualisation of the Hesitancy, Social Vulnerability Index, Ethnicity
  - *PVI_data.ipynb* - extracted the correlation between Vaccines and the other factors used in the calculation of the PVI
  - *PVI_results.ipynb* - extracted the correlation between Vaccines Index and the indexes of the other factors used in the calculation of the PVI


`./data` - Data used in the project 
   - *./data_source.md* - Data sources for all datasets.
   - *./data_after_imputation.csv* - **FINAL DATASET**

`./data/raw` - raw data downloaded from source

`./data/clean` - cleaned data after initial EDA 

  - *vaccination_rate_US.csv* - vaccine rates US (target feature)
  - *covi19_death_cases.csv* - covid19 cases and death (county level)
  - *covid19_health_disparity.csv* - heath disparity data (county level)
  - *Hesitancy_SVI_Ethnicity.csv* - Hesitancy, Social Vulnerability Index, Ethnicty (county level)
  - *PVI_05_Oct_2021_data_clean.csv* - Vaccines, Infection Rate, Pop Concentration, Intervention and Health & Environment (county level)
  - *PVI_05_Oct_2021_results_clean.csv* - Vaccines, total PVI index, Infection Rate indexes, Pop Concentration indexes, Intervention indexes and Health & Environment indexes (county level)
  - *cdc_90519_DS1.csv* - CDC data on underlying medical conditions associated with high risk of severe covid-19 (county level)


`./data/figures` - Figures for the final report

