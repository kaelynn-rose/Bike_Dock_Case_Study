# Bike Dock Capacity Case Study

The goal of this case study was to determine whrere to install more bike docks at bike docking stations, and which stations already have more than enough bike docks and do not need any additional docks installed. To do this, I wanted to identify stations where bike dock capacity was over-utilized, and stations where capacity was under-utilized.

### Data Pre-Processing and Cleaning

I first loaded the station data and trips data from separate CSV files. There were 3 files for trips data, one for Q3-07, one for Q3-07 and -08, and one for Q4. I merged these into one dataframe before beginning data analysis. After loading the station and trips data, I examined the data for null values. All of the columns of interest to this case study were non-null, only gender and birth year had null values because these were only available for subscribers. 

Next, I cleaned up the start-times and stop-times in trips dataset. I converted start-times and stop-times to Pandas datetime format, and then created additional columns for start-day, stop-day, start-hour, and stop-hour for data analysis and plotting purposes.

### Exploratory Data Analysis

After cleaning and pre-processing the data, I began exploratory data analysis to inform my goal of determining underutilized and over-utilized bike stations.

