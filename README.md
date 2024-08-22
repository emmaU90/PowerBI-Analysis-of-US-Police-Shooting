# PowerBI-Analysis-of-US-Police-Shootings

# Tittle: US Police Shootings

![US-police-shootings-Anaysis](assets/images/shooting.png)

# Table of contents

- [Objective](#objective)
- [Stages](#stages)
- [Data cleaning](#data-cleaning)
- [Visualization](#visualization)
- [Analysis](#analysis)
 - [Findings](#findings)
 - [Discovery](#discovery)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

# Objective

- What is the key main point?

This analysis aims to explore recent US police killings, a hot topic that came into being, "Racism". This data has been gathered to take out some insights and analyze the story around racism in America.  The dataset contains basic data about people like their name, age, gender, and race. 

Along with it, is the shooting/killing information, like the date of the event, where it happened? How they were shot? Did they attack? Were they holding weapons? Did they show any mental illness? Was the policeman wearing a camera? was the incident recorded? Did the suspect flee? Apart from that, a category column of which weapons were used by the suspect.

- What is the ideal solution?

To create a dashboard that provides insights into the analysis.

# Stages

- Download the .pbix file together with the dataset from this repository.
- Open the file in Power BI Desktop.
- (Optional) If using a different data source, connect your data to the existing model using Power Query Editor.
- Explore the report pages to gain insights into police shootings.
- 
# Data cleaning

- What do we expect the clean data to look like?
- What should it contain?
- What limitations should we apply to it?

The aim is to refine our dataset to ensure it is structured and ready for analysis.

The cleaned data should meet the following criteria and constraints:

- Only relevant columns should be retained.
- All data types should be appropriate for the contents of each column.
- No column should contain null values, indicating complete data for all records.


# Visualization

## Results
- What does the dashboard look like?
  
![Visualization](assets/images/Dashboard.PNG)

# Analysis

## Findings
- What did we find?
For this analysis, we’re going to focus on the questions below to get the information we need for the analysis.

Here are the key questions we need to answer:

- What is the distribution of incidents by race?
- What are the trends or patterns of shooting over a period of years?
- What is the correlation between gender and mental illness?
- Is there a correlation between recorded incidents and the number of those who flee under the incidents?
- What method of killing was used more during the incident?


### 1. What is the distribution of incidents by race?
![Visualization](assets/images/race.PNG)

### 2. What are the trends or patterns of shooting over a period of years?
![Visualization](assets/images/Trend.PNG)

### 3. What is the correlation between gender and mental illness?
![Visualization](assets/images/Mental-illness.PNG)

### 4. Is there a correlation between recorded incidents and the number of those who flee under the incidents?
![Visualization](assets/images/Recorded.PNG)

### 5. What method of killing was used more during the incident?
![Visualization](assets/images/5.PNG)


# Discovery

- What did we learn?

We discovered that

1. With the distribution of incidents by race, it was found that the race with the highest distribution of incidents was the white race with a manner of death (shooting or tasered) of about 2476, followed by Black, Hispanic, Asian, Native, and Others with the lowest incidents of about 48.
  
2. Upon analyzing the dataset, the trends or patterns of shooting over a period of years, indicated a highest spike in the year 2015 as more incidents were recorded in that year with a count of 965, and the lowest year was 2020 with a count of 374.
   
3. According to the findings, the relationship between gender and mental illness indicates that when mental illness was false, males had a percentage of about 95.79 compared to females, who had a percentage of about 4.0, and when mental illness was true, males still had the highest number with 93.74% compared to females with 6.26%. In summary, we can conclude that, with regard to the incident, there were more males than females.
   
4. The pie chart in the power BI report shows the relationship between the body camera and the count of flee individuals. There is a noticeable fact that the count of flee was high, with a percentage of 88.19 when the body camera was false and 11.81% when the body camera was true. In summary, we can conclude that more individuals fled when the body camera was off compared to the individuals who fled when the body camera was on. This can indicate trust issues on the side of the policy.

5. With regard to the method of killing, we can conclude that shooting was used more in the incident with a percentage of 95.71, compared to shooting and tasering, which was 4.29%.


# Conclusion

Base on the findings and analysis of the coffee sale dashcoard, we can conclude that the project showcases the effectiveness of exploratory data analysis in providing useful insights in dataset that involved the customers, products and the orders.

