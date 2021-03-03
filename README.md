# Jersey-City-Citibank-Analysis

![Image](https://www.libertytowersapts.com/wp-content/uploads/2015/09/xScreen-Shot-2015-09-10-at-5.48.43-PM.png.pagespeed.ic.jzZmdEQ2h6.webp)

## Background

The purpose of this project is to provide new business initiatives to improve the Jersey City Citi Bike program in 2021.  A presentation will be conducted to city officials by the end of March 2021.  

Research needs to be done by obtaining monthly datasets from 2018 to 2020 from the Citi Bike System Data website.  Then, Python with Pandas (through Jupyter Notebooks) will be used to clean and merge the datasets.  The merged CSV dataset will be loaded on Tableau and a story along with dashboards will be created with interactive maps and visualizations for the final presentation.

## Questions

1.  What are the age and gender demographics?
2.  When are the peak times and seasons?
3.  How many people subscribe to the program?
4.  Have the number of trips and the average trip durations decreased as a result of the pandemic?
5.  Have subscribers and customers decreased?
6.  Are the popularity of the stations still the same?

## Datasets

[2018 -2020 Citi Bike System Data](https://s3.amazonaws.com/tripdata/index.html) - file names are JC-YYYYMM-citibike-tripdata.csv.zip
[Jupyter Notebook](https://github.com/cecileung1208/Jersey-City-Citi-Bike-Analysis/blob/master/Data/JC%20Citibike%20Merge.ipynb) - this is to merge the dataset

## Requirements
* Download the monthly datasets frm the Citi Bike Syste Data website.
* Ensure all table table formats are consistent through the 36 csv datasets.
* Merge the CSV datasets into one dataframe.
* Filter out bad data such as unknown gender, unknown birth year, and wrong inputs of birth year such as 1898 that will not provide an accurate assessment of our analysis.
* Export the dataframe into CSV.
* Load the merged CSV dataset file into Tableau.
* Create graphs and maps.
* Create dashboards by using the graphs and maps created in the previous sets.
* Add filters as needed.
* Create story for final presentation.
* Save on Tableau and Tableau public.
* On Tableau public, publish link to stakeholders.

## Scripts
[Jersey City Citibike Analysis - Tableau](https://github.com/cecileung1208/Jersey-City-Citi-Bike-Analysis/blob/master/Jersey%20City%20Citibike%20Analysis%202018-2020.twbx)

## Tableau Presentation Link
[Tableau Story](https://public.tableau.com/views/JerseyCityCitiBikeAnalysis2018-2020/JerseyCityCitibikeAnalysis?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)

## Data Visualizations

### Demographic Trends

* **User Types**

![Image](https://github.com/cecileung1208/Jersey-City-Citi-Bike-Analysis/blob/master/Image/User%20Type%20Demographics.png)

The User Type Dashboard provides trip, gender and age distribution for customers and subscribers.  The user can use the dropdown menu at the top to filter by year and user types.
