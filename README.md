# Messy-Employee-Data-Cleaning-and-Visualization

## Summary
The dataset analyzed within this project concerns employee data, including performance scores, salaries, and geographic locations. Within this project, the data was cleaned within Python. Data Cleaning techniques include filling in missing values and splitting columns. Visualization was performed in both Python and Tableau. Through Tableau visualization, it was found that there was a misalignment in salaries and performance in the state of Texas when compared to other states. 

## Dataset Information
The dataset was found on Kaggle at the link below. The dataset contains the following variables:

| Variable Name | Description |
|-------------|-------------|
| Employee_ID | Unique synthetic ID (e.g., EMP1001) |
| First_Name, Last_Name | Randomly generated personal names |
| Name | Full name (may be redundant with first/last) |
| Age | Includes missing values |
| Department_Region | Compound column (e.g., "HR-Florida") |
| Status | Employee status (Active, Inactive, Pending) |
| Join_Date | Inconsistent format (YYYY/MM/DD) |
| Salary | Includes invalid entries (e.g., "N/A") |
| Email, Phone | Synthetic contact information |
| Performance_Score | Categorical performance rating |
| Remote_Work | Boolean flag (True/False) |

Several of these variables contain mising, inconsistent, or combined values. As such, it is important that these values be cleaned before any additional analysis is done. 
### Data Source Link: https://www.kaggle.com/datasets/desolution01/messy-employee-dataset?resource=download

## Data Cleaning
