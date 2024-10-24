# King_Nursing_Home_Bed_Analysis
This is a draft of my final project for Advanced Data Journalism. This repository contains data, analytic code, and findings that support portions of a future article. 

## Data
This analysis uses data from New York state's weekly Nursing Home Bed Census. Nursing facilities report their number of available beds each week. This analysis is based on data from the week of October 23: [Nursing_Home_Weekly_Bed_Census_Last_Submission_20241023.csv](https://github.com/user-attachments/files/17512465/Nursing_Home_Weekly_Bed_Census_Last_Submission_20241023.csv)

The spreadsheet contains the following columns which are relevant to the analysis: 
- Facility Name
- County
- Bed Type
- Week Difference
- Available Capacity
- Total Capacity

## Methodology
The notebook performs the following analyses: 
1. Cleaning data by checking for incomplete submissions (in important columns)
2. Narrowing down the data to focus on specific counties, with addressing leftover quirks in "empty" spaces, changes in dtypes, and sums of availible/total capacity.
3. Repeating #2 for remaining Hudson Valley counties.
4. Returning to the main data set to run the same analysis state-wide.
5. Creating a dataframe with the location, calculated vacancy rate, and calculated occupancy rate.
6. Export dataframe to .csv.

## Outputs
The notebook outputs this spreadsheet, which includes location, vacancy rates, and occupancy rates: [HV_Vacancy_Rates.csv](https://github.com/user-attachments/files/17512691/HV_Vacancy_Rates.csv)

## Running the Analysis Yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:
- Python 3

## Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?
Contact Jesse King at jesse.king1218@gmail.com



