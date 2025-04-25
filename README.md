# <ins>Exploring-LinkedIn-Engagement-A-Behavioral-and-Time-Based-Study-of-a-21-Day-Posting-Challenge</ins>

#### For 21 days, I participated in a challenge which was organized by Abimbola Arowolo. I and other participants consistently posted on LinkedIn. My posts focused on 5 different types on content: Motivation, Data Insights, Humor, Learning and Growth, and Engagement/poll.  Thus, this project is an Excel and Power Bi project which shows a complete analysis of my engagement and growth on LinkedIn all through the period of the challenge.

### <ins>OVERVIEW</ins>

This data analysis project aims to explore my growth rate during the period of this challenge, it also provides insights into how I engaged on posts and how others engaged on my posts as well as the overall insights into how the challenge went, so as to know how others participated as well. The dashboard has three pages: 
1) Overview: This page provides a general knowledge of when the challenge began, when it ended, how many people participated, how many were active and lots more about the challenge in general. 
2) Audience Reaction: This page shows how others engaged on my post, and how my LinkedIn profile performed throughout this period.
3) My Reaction to Posts: Here, the analysis of how I engaged on posts. I was able to engage on posts made by fellow participants of the challenge as well as other posts on LinkedIn.
Generally, this helped me to know what type of posts got the highest engagement as well as the best ti me to post and many other insights which we will unravel in this documentation.

### <ins>INTRODUCTION</ins>

By analyzing the dataset of my 21-day LinkedIn challenge, I was able to know:
1.	The total number of people who registered for the challenge and the number of people who were actually active
2.	The day with the highest post as well as the trend of participation throughout the challenge.
3.	The relationship between my engagement on posts and engagement on my post (That is if engaging more on people`s posts meant that I will get more engagements.)
4.	How impressions on my posts correlates with engagements and connection growth.
5.	How many impressions it takes to get a single engagement on my post.
6.	The contents with the highest engagement.
7.	How I engaged on posts and the days with the least and highest engagements,
8.	My total engagements and the best time for engagement.

In the course of this analysis, I was able get deeper insights not exhausted by the list above. 

I was able to carry out the following Analysis:

**Time Series Analysis:**
I tracked and analyzed data over a continuous 21-day period, focusing on trends over time (e.g., engagement patterns, participant drop-off, daily post performance).

**Descriptive Analytics:**
I explored and summarized what happened during the challenge (e.g., number of posts, types of content, engagement totals).

**Behavioral Analysis:**
I examined user behavior—both mine and my audience's—to understand how engagement changes based on content type, time of day, and day of the week.

**Social Media Analytics:**
I made use of LinkedIn-specific metrics like impressions, comments, likes, profile views, and connection growth to evaluate my visibility and content performance.

**Exploratory Data Analysis (EDA):**
I investigated multiple variables to uncover patterns, correlations, and outliers without starting with a specific hypothesis.

#### I demonstrated the following skills in this project:
- Data cleaning
- Dax
- Modelling
- Buttons
- Page navigation
- Data visualization,
- Measures,
- Filters
- Tooltips,
- Critical thinking,
- Problem solving.

### <ins>DATA COLLECTION AND SOURCE</ins>

I manually collected the data and entered it into an excel sheet. At 12: am everyday all through the time of the challenge, I manually counted the number of likes, comments, impressions, new connections, reposts, time of post, profile views, days, content type . Since all those who participated in the challenge, belonged to a group WhatsApp group, it was also easier to calculate the number of people in the group each day, which served as the number of participant. Each participant posted a link to their LinkedIn post each day, so it was also easier to get the number of people who posted each day, hence, it was much easier to know how many participants were active. I also manually counted the number of posts I engaged in; how many likes and comments I made on posts (Posts made by fellow participants and other random posts). These was the data I collected to form 2 tables which I used for my analysis.

After creating my tables, I imported it into power Bi desktop and further created extra columns and 2 more tables to aid proper analysis.


### <ins>DATA TRANSFORMATION/CLEANING</ins>

Since I collected the data manually and even entered it myself, I made sure to be very meticulous from the beginning and paid close attention not to enter the wrong the data, as such the dataset didn`t require much cleaning. I only made sure I formatted each column properly to its actual data type.

### <ins>DATA MODELLING</ins>

I worked with four tables:
**Inbound Engagement:** Help information about the engagements, profile views on my post and every information surrounding my post and LinkedIn profile.
**Outbound Engagement:** Contained information about my activities on posts made by others.
**Date Table:** Contains information about the date and days throughout the challenge
**Challengers Posts:** This holds information about how many participants were active, how many posts were made each day, how many persons were inactive and the number of people in the WhatsApp group.
To ensure that I modelled the data rightly, I joined the **Inbound Engagement table** to the **Date table** using the **Date column**, the **Date table** to the **Outbound Engagement table** also using the **Date column** and finally, the **Outbound Engagement table** to the **Challengers` Posts table** using the **date column** as well.

<img width="823" alt="Data Modelling" src="https://github.com/user-attachments/assets/44db2f2e-b35a-42de-8685-ea8fb93cba28" />


#### The Key Performance Indicators (KPIs) for the analysis are:

- Total Participants
- Active Participants
- Inactive Participants
- First Day of Challenge
- Last Day of Challenge
- Total Posts made by me
- Connection Growth
- Content Category
- Profile views
- Total Impressions on my post
- Total Engagements
- Total posts by Fellow Participants
- My engagements on posts
- Least Engaged Day
- Highest Engagement day

### <INS>ANALYSIS PROPER</INS>
**With this, we are set to explaining every page and the insights contained therein.**

[Click here to interact with the dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDk3ZmE0YzctMzc3Mi00ZTM1LTgxMWEtZjhjMGE2MDY3ZTg1IiwidCI6ImY4NzNhMzA5LTg2ZjgtNDg4OS05OTcxLTEzMDQwNDM0NjZmNCJ9)

#### The Overview Page

This page provides insights into how the challenge went generally, how many individuals participated, what percentage was active and how many were inactive and many more.

<img width="600" alt="Overview Page" src="https://github.com/user-attachments/assets/46f42174-a56c-4ecc-8cc1-d91f3e267b35" />


As seen, the challenge started on the **3rd of March 2025** and ended on the **23rd of March 2025**.  A total of **226** registered to participate in the challenge, but on average only **22.98%** were active, that means only **52** persons were active and the rest **77.02%** that is **174** were inactive. 

<img width="227" alt="Active and Inactive" src="https://github.com/user-attachments/assets/ed1dc6cd-ec2c-4e83-9c74-fa4b9de8c6c6" />


Moving deeper, we could find the actual number who participated in the challenge each day. 

<img width="134" alt="Actual vs Expected" src="https://github.com/user-attachments/assets/3346278d-a9bb-47f4-b78f-bb3f1b515024" />


The image above indicates that only **25** persons participated in the challenge on the **23rd of March** as against the **226** persons who should have participated. This means that **88.98%** did not participate. When filtered by the calendar below, we can find out how many participated each day in the challenge.

From here, we can see that the number of inactive members exceeds that of active members. This could be for the following reasons:
- **People joined the challenge without clearly understanding what it was for.**
- **Many lacked content Ideas to put up for the challenge**
- **It was not just the priority for many**
- **Lack of motivation**

Moving on we can see the trend of posts made by participants by day of the week. That is how active the participants were throughout the week. As shown in the image below:

<img width="218" alt="Participants` posts by Day of the week" src="https://github.com/user-attachments/assets/d6b62ff1-0f3a-449b-94f0-04ac4e0a496e" />


We can see that Participants were most active on the first day of the week and it dropped s the days went on till Sunday. That means, participants were more active on Mondays and it dropped drastically till Sunday. 
This could mean that most people are more motivated on Mondays and at the beginning of the week, and begin to lose motivations as the week come to an end or that most people become busier as they progress during the week. 
Whichever way, the result of our analysis shows that it is easier to start than to finish.

Another insight to draw from this page is the trend of active participation throughout the challenge.

<img width="250" alt="Trend of Participation" src="https://github.com/user-attachments/assets/33d58c71-e3cf-4af8-9e69-fed689fed415" />


From the image, we can see that the participation was fluctuating. The day with the highest participation was the third day, **5th March**, with **89** posts made. This is not surprising because it shows that a lot of people heard or learnt of the challenge and participated after it started. To prove this, when we filter the first day of the challenge, we see that the total number of participants were **210** but on the 3rd day, they were already **215**. But this could not be the only reason because on the **24th of March** when the total number of participants rose to **226** and remained unchanged, the total number of participants was just **40**. Even though we cannot deny that the number of people who joined the WhatsApp group affected the activeness of participation, the motivation of participants played a great factor in deciding who remained consistent throughout the challenge. 
Hence, **5th march had the highest post because additional people joined the challenge and that was the early days of the challenge, so the motivation was still high.**

Moving deeper, we can see that the days with the lowest participation in the trends are **9th**, **16th**, and **22nd March** as seen here: 

<img width="249" alt="21 days trend with lowest posts" src="https://github.com/user-attachments/assets/c6026091-0735-462b-9adb-3902f09e3d9e" />



These days are Sunday, Sunday and Saturday respectively. This is still a pointer to the fact that the Sundays get the least participation, either because it is weekend and participants are busy or participants just want to rest.

Moving on, the table below provides an insight into the relationship between my engagement on posts and engagement on my posts. 

<img width="179" alt="My engagement vs engagement on my post" src="https://github.com/user-attachments/assets/f9f1a1bc-caf0-4e61-b8b0-f5823a82801b" />

  
From the image, it can be seen that the day I engage less on posts is on Thursday but funny enough, it is the day I got the highest engagement. 
Through deeper analysis, I was able to find out that it was not just about how well I engaged on post but the type of content I posted. On the day I got the highest engagement, **6th March 2025**, which happens to be a Thursday, I made a funny post which got me my highest engagement 

[Here is the post I made on 6th March](https://www.linkedin.com/posts/emmanuelibetheanalyst_study-data-analysis-in-three-months-and-activity-7303359128905646080-Pj6V)

#### Audience Reaction Page

<img width="601" alt="Audience Reaction Page" src="https://github.com/user-attachments/assets/18943416-699e-45c6-8d0d-93c16c2eb669" />


This page shows the complete analysis of the reactions I got on my posts and page throughout the challenge.


<img width="476" alt="Page 2 kpi" src="https://github.com/user-attachments/assets/10deac58-8029-4cfd-aa33-73d01e709a4a" />

I made a total of **21** posts, which means I remained consistent throughout the challenge for 21 days, and posted **5 different categories of content**: *Motivation*, *Data Insights*, *Humor*, *Learning and Growth*, and *Engagement/poll*. I had an additional **120 connections**, **113 profile views**, **9,347 Impressions**, and **647 engagements.**

A very important point to note is that it takes **14.45 Impressions** to get **1 engagement** on a post as can be seen here: 

<img width="113" alt="Impressions per engagement" src="https://github.com/user-attachments/assets/6c8dd833-8570-414b-95fe-39bd984ba4ed" />

A lot more insights were uncovered in this page.

First, the impressions and connections I got relative to the content type.

<img width="217" alt="Impressions vs conection growth per content" src="https://github.com/user-attachments/assets/d5632a74-fb3a-45f0-bd7c-17fdc94b064c" />


As seen here, I got the highest request for connections, 39 and 35 after posting contents on data insights and motivation. This is an indication that value attracts. This does not mean that other contents are less valuable. It only means that contents that make you appear well informed in your field and strengthens your audience, helps you attract more followers.
The analysis also shows that the more impressions you get, the more likely you are to get new connections. This is true except for the humor content which appears to be an outlier and reason is that since it is humor, it was easily relatable and so got many impressions, but is not enough to get new followers.
**This means, impressions alone are not enough to attract followers, but quality of content is.**

Moving on we can see from the images below that Thursday recorded the highest engagement on my post and the 6th of March which happens to be a Thursday also had the highest engagement. 

<img width="281" alt="page 2 engagement trend" src="https://github.com/user-attachments/assets/4945a8c9-e9ac-484e-8a19-d3956db4b3e5" />


As already seen, the post that was made on this day was a funny one, so it is just normal if it gets more engagement.
However on a general note, posts made under the Data and insights category has the highest engagement while the least engaged post was poll 

<img width="163" alt="Engagement by Content type" src="https://github.com/user-attachments/assets/a843c1eb-6ca7-4e97-b834-bd7727b88aca" />






