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

Several of these variables contain mising, inconsistent, or combined values. As such, it is important that these values be cleaned before any additional analysis is done. The link to the original Kaggle page where the dataset was found can be seen below. 
### Data Source Link: https://www.kaggle.com/datasets/desolution01/messy-employee-dataset?resource=download

## Data Cleaning
Data Cleaning was performed in Python and consisted of several steps. The first was initial exploration, which showed that the dataset include 11 variables and 1020 rows. Additionally, exploration revealed that there were no duplicate values within the dataset. It was also found that several of the variables inlcuded missing values. As such, the next step was to fill these missing values. Additional issues that were encountered were incorrect data types and merged data in cells. As such, these issues were fixed, starting with the data types. By the end of cleaning, there were no more missing/null values and no variables contained strange data. You can see some of the procees through the images below:

<img width="1433" height="670" alt="image" src="https://github.com/user-attachments/assets/f6d0c44f-dd48-4e88-9968-7e8e359b6ab7" />
<img width="1399" height="648" alt="image" src="https://github.com/user-attachments/assets/2344f59d-5989-4051-bb5d-802fdd4ff1b3" />
<img width="1354" height="587" alt="image" src="https://github.com/user-attachments/assets/cfd4a7fb-c34f-4bf0-849c-92d67271179b" />

At the end of cleaning, the cleaned version of the dataset was stored and uploaded to this repository.

## Data Visualization
Data Visualization was originally performed in Python. All data was visualized using the cleaned dataset created early. The first thing that was done was map the Peformance Scores to numbers. Next, several bar charts and boxplots were created in Python, as shown below:

<img width="1384" height="626" alt="image" src="https://github.com/user-attachments/assets/b831c2f5-31e5-443c-9061-c86c1424495a" />
<img width="1401" height="720" alt="image" src="https://github.com/user-attachments/assets/991b10de-9669-4d9e-80dc-b129f3efa689" />

For additional visualization, the work was shifted over to Tableau. Within Tableau, a new variable was created that would find the difference between the salaries of each performance group within a state and the average state salary. Within Tableau, it was found that low-performers in Texas received higher salaries for their state in comparison to other states, where the effect was the opposite. This displays a current misalignment among performane incentives, as those with high scores should receive higher salaries. As such, further digging into the Texas office is necessary in order to help explain strange trend. You can see a picture of the visualization down below: 

<img width="1524" height="746" alt="image" src="https://github.com/user-attachments/assets/07aea559-1617-498e-bd2f-d4d8eeca5622" />

For further information in regards to the cleaning process, please look at the Messy Employee Dataset Cleaning.ipnyb File: https://github.com/SPineco/Messy-Employee-Data-Cleaning-and-Visualization/tree/main

For further information on the Tableau visualizations, please look at the Messy_Employee_Tableau.twbx file: https://github.com/SPineco/Messy-Employee-Data-Cleaning-and-Visualization/tree/main



