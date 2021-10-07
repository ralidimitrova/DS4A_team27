## DS4A_team27


Github repo for the capstone project Team #27.




### Directories:

#### Current Goal Week 3: Data Cleaning & initial EDA:

`./DS4A_team27/eda_notebooks` - all notebooks performing initial EDA pushed by repo members

  - `00_vaccination_rate_us.ipynb` - extraction of the vaccination rate data (date: 03/10/21)
  - `01_vaccination_rate_us_visualisation.ipynb` - visualisation of the vacc rate using plotly
  - `02_covid19_severity_us.ipynb` - extraction and visualisation of the covid19 death/cases (date: 03/10/21)
  - `03_covid19_heath_disparity.ipynb` health disparity data 
  - `Hesitancy_SVI_Ethnicity.ipynb` - extraction and visualisation of the Hesitancy, Social Vulnerability Index, Ethnicity
  - `PVI_data.ipynb` - extracted the correlation between Vaccines and the other factors used in the calculation of the PVI
  - `PVI_results.ipynb` - extracted the correlation between Vaccines Index and the indexes of the other factors used in the calculation of the PVI


----

`./data/data_source.md` - where do all the data come from?

`./data/raw` - raw data downloaded from source

`./data/clean` - cleaned data after initial EDA 

  - `vaccination_rate_US.csv` - vaccine rates US (target feature)
  - `covi19_death_cases.csv` - covid19 cases and death (county level)
  - `covid19_health_disparity.csv` - heath disparity data (county level)
  - `Hesitancy_SVI_Ethnicity.csv` - Hesitancy, Social Vulnerability Index, Ethnicty (county level)
  - `PVI_05_Oct_2021_data_clean.cs` - Vaccines, Infection Rate, Pop Concentration, Intervention and Health & Environment (County level)
  - `PVI_05_Oct_2021_results_clean.cs` - Vaccines, total PVI index, Infection Rate indexes, Pop Concentration indexes, Intervention indexes and Health & Environment indexes (County level)

----


`./data/plots` - plots/figures for report

