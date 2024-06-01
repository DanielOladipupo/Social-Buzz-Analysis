# Social Buzz Analysis
The project help to understand the client and business problem at hand, Identify the requirements that need to be delivered for this project, and also Identify which tasks to be focus on as a Data Analyst.
### Problem Statement

Over the past 5 years, Social Buzz has reached over 500 million active users each month.
They have scaled quicker than anticipated and need the help of an advisory firm to oversee
their scaling process effectively.
Due to their rapid growth and digital nature of their core product, the amount of data that they
create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging
from text, images, videos and GIFs are posted. All of this data is highly unstructured and
requires extremely sophisticated and expensive technology to manage and maintain. Out of the
250 people working at Social Buzz, 200 of them are technical staff working on maintaining this
highly complex technology.
Up until this point, they have not relied on any third party firms to help them get to where
they are. However there are 3 main reasons why they are now looking at bringing in external
expertise:
- They are looking to complete an IPO by the end of next year and need guidance to
ensure that this goes smoothly.
- They are still a small company and do not have the resources to manage the scale that
they are currently at. They could hire more people, but they want an experienced
practice to help instead.
- They want to learn data best practices from a large corporation. Due to the nature of
their busines sunderstanding how the world's biggest companies manage the challenges of big
data.

### Objectives
The project help to understand the client and business problem at hand, Identify the requirements that need to be delivered for this project, and also Identify which tasks to be focus on as a Data Analyst.
However, the project will also focus on creating a user-friendly dashboard for Social Buzz. The envisioned dashboard aims to provide insights into the Top 5 category, peformance of each content types, distribution by category, and timely trend of content types by month for the year 2011, fostering informed decision-making and propelling Social Buzz towards sustainable growth. The entirety of this project will be done using Microsoft Excel.

### The Data
The dataset for this project was provided by [Forage](https://www.theforage.com/virtual-experience/hzmoNKtzvAzXsEqx8/accenture-north-america/data-analytics-mmlb/project-understanding) of which were 3 datasets which includes the Reaction Types, Reactions, and Content. It contains 2,627 rows and 7 columns after proper cleaning with the following information:

1. Content ID
2. Reaction Type
3. DateTime
4. Content Type
5. Category
6. Sentiment
7. Score

![Screenshot (407)](https://github.com/DanielOladipupo/Social-Buzz-Analysis/assets/155446588/4127ffa8-b3c8-42e4-920b-e1393e944aff)


### Data Cleaning and Preparation
Once I downloaded and imported the data into Excel, I proceeded to clean and prepare it for analysis. As such, the following steps were created:
- Removing rows that have values which are missing,
- Changing the data type of some values within a column
- Removing columns which are not relevant to this task.
- Data modelling by merging three tables together

### Exploratory Data Analysis

The project answer to the following questions:
- What are the Top 5 Categories by aggregate popularity score?
- What are the performance of each content type?
- What are the distribution of each categories?
- Which of the months have the highest Content?

### Data Aanlysis
This include a formular code used in this project to derive the aggregations of values base on condition

```Excel
=SUMIF('Social Buzz Cleaned Data'!F:F,'Popular Categories'!B16,'Social Buzz Cleaned Data'!H:H)
```

### Insights
1. Top 5 Category:
  
