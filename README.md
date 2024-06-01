# Social Buzz Analysis
### Table of Contents
- [Problem Statment](#problem-statement)
- [Objectives](#objectives)
- [The Data](#the-data)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Dashboard](#dashboard)
- [Recommendations](#recommendations)
- [Next Steps](#next-steps)
   
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

### Data Analysis
This include a formular code used in this project to derive the aggregations of values base on condition

```Excel
=SUMIF('Social Buzz Cleaned Data'!F:F,'Popular Categories'!B16,'Social Buzz Cleaned Data'!H:H)
```

### Insights
1. **Top 5 Category:** Animals, Science, Healthy Eating, Technology, and Food were the Top 5 Categories, with Animals leading at 74,965 contents.
   
   ![image](https://github.com/DanielOladipupo/Social-Buzz-Analysis/assets/155446588/0df65ac7-d93a-4aa6-8ef3-fc60a3b60ed2)

2. **Performance by Content Type:** Audio, Gif, Photo, and Video were the content type, with photo having the highest performance of 6,589 engagements.

   ![image](https://github.com/DanielOladipupo/Social-Buzz-Analysis/assets/155446588/4accea71-734c-4c67-9387-bc8f0de3c9d1)

3. **Distribution by Category:** Animals ranked the Top in the distribution by category with 1,897 engagement, while the Public Speaking was the least with 1,217 engagements.

   ![image](https://github.com/DanielOladipupo/Social-Buzz-Analysis/assets/155446588/e5c8c2a1-f996-4701-b7d2-800ec5891084)

4. **Content Type by Month:** The trend of Content Type by Month from January to December shows that we have more Content in the month of May with the total of 2,138 engagements while February resulted to be the Month with the least with 1914 engagements.

   ![image](https://github.com/DanielOladipupo/Social-Buzz-Analysis/assets/155446588/5c71c090-09f0-4cfa-a245-a1a3e9668fb6)

### Dashboard 
![Screenshot (408)](https://github.com/DanielOladipupo/Social-Buzz-Analysis/assets/155446588/d1d905a8-6239-4ae8-b433-675723101476)

### **Recommendations** 
1. **Schedule High-Engagement Content for Peak Days:** Focus on posting high-engagement content and review historical engagement data to identify additional optimal posting times.
2. **Analyze Audience Preferences:** Conduct a thorough analysis of which types of images, videos, and articles resonate most with your audience. Use engagement metrics such as likes, shares, comments, and click-through rates to determine what content performs best.
3. **Experiment with GIF Content:** Explore the use of GIFs, particularly those that incorporate humor or trending topics, to see if they boost engagement. Test different GIF styles and themes to understand what resonates most with your audience.
4. **Engage with Trends and Current Events:** Monitor trending topics and current events to create timely and relevant content. Engage with these trends to increase the likelihood of your content being shared and discussed.
5. **Leverage Data-Driven Insights:** Regularly review social media analytics to stay updated on what content is performing well. Adjust your content strategy based on these insights to continually optimize engagement.

### Next Steps
1. Prioritize recommendations based on potential impact.
2. Develop an action plan tasks, timelines, and ownership.
3. Continously monitor user behaviour and adapt strategies based on new data and trends.
4. By harnessing the power of user data and recommendations, social buzz can unlock its full potential, creating a more engaging and personalized user experience to solidify its postion as a leader in the social media land scape.  






  
  
