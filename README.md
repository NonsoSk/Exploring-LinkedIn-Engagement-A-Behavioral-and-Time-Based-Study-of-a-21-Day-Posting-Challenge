# <ins>Exploring-LinkedIn-Engagement: -A-Behavioral-and-Time-Based-Study-of-a-21-Day-Posting-Challenge</ins>

### For 21 days, I participated in a challenge which was organized by Abimbola Arowolo. I and other participants consistently posted on LinkedIn. My posts focused on 5 different types on content: Motivation, Data Insights, Humor, Learning and Growth, and Engagement/poll.  Thus, this project is an Excel and Power Bi project which shows a complete analysis of my engagement and growth on LinkedIn all through the period of the challenge.

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

### <ins>The Overview Page</ins>

This page provides insights into how the challenge went generally, how many individuals participated, what percentage was active and how many were inactive and many more.

<img width="600" alt="Overview Page" src="https://github.com/user-attachments/assets/46f42174-a56c-4ecc-8cc1-d91f3e267b35" />


As seen, the challenge started on the **3rd of March 2025** and ended on the **23rd of March 2025**.  A total of **226** registered to participate in the challenge, but on average only **22.98%** were active, that means only **52** persons were active and the rest **77.02%** that is **174** were inactive. 

<img width="227" alt="Active and Inactive" src="https://github.com/user-attachments/assets/ed1dc6cd-ec2c-4e83-9c74-fa4b9de8c6c6" />


Moving deeper, we could find the actual number who participated in the challenge each day. 


<img width="115" alt="Screenshot 2025-04-25 141837" src="https://github.com/user-attachments/assets/4864e723-98a6-4c72-b7b0-14f315b2a664" />


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

### <ins>Audience Reaction Page</ins>

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



### <ins>My Reaction to posts</ins>

<img width="607" alt="Page 3" src="https://github.com/user-attachments/assets/d5a0a0fb-a84e-4b70-bbac-79f4714a5523" />


This page provides insights into how I engaged on posts made by other participants as well as other random posts on LinkedIn. 


<img width="475" alt="Page 3 kpi" src="https://github.com/user-attachments/assets/31385d84-d610-4281-b8ec-d9dc1b6a5158" />


First, when we observe the KPIs on this page, we see that a total of **1,064 posts** were made by participants of the challenge (Note that this does not include my own posts), my total engagements on posts are **1,273**. It also shows that on the **11th of March**, I did not engage in any post and on the **4th of March** my engagement on posts summed up to **208**, making it my highest engagement day on post throughout the challenge.
The image below shows a breakdown of my total engagement. A prove that I did not just engage on posts made by those who participated alone, but I also engaged on posts made by others on LinkedIn.

<img width="268" alt="enagement on peoples and participants post" src="https://github.com/user-attachments/assets/ce5e7536-c084-45bd-9e10-b535a63c1fad" />


Further, I also discovered that I commented less on posts compared to how I liked them. This was because since it was a challenge which had people from different fields, I was unable to relate to some posts made by fellow participants and so had nothing to comment, so the best I could do was just to like.
The image here show clearly what I mean:

<img width="174" alt="Likes vs comments " src="https://github.com/user-attachments/assets/09f7c4a1-8cbd-4f3b-ae6c-5d047eb4b1e0" />


Overall, my analysis uncovered that I engaged on posts more in the mornings than afternoon. This is an indication that I am more productive in the morning

<img width="137" alt="Morning Vs Afternoon" src="https://github.com/user-attachments/assets/83f6a361-b750-450e-9f40-93dfc9ffeab9" />


Moving on, we can see how I engaged on posts throughout the week. 

<img width="256" alt="wEEKLY ENGAGEMENT ON POSTS" src="https://github.com/user-attachments/assets/a54b2477-8779-449a-9a5d-e1e8f71b91c3" />


From the image above, it is clear that I engage more on posts on Saturdays than other days. So, while other participants on average show less participation on Saturday and weekend, I find Saturday as the best time to engage on posts. This could mean that my timetable allows me much time on Saturday than the rest of the week. 
The analysis also shows that I have thursday as a day I least engage on posts. This is not surprising since Thursdays happens to be my busiest day of the week.

Finally, we can see my engagement trend throughout the challenge. 

<img width="289" alt="p3 enagement trend" src="https://github.com/user-attachments/assets/bfafdb01-3cf9-4b12-8d4f-75dd71468993" />


Even though I was able to post all through the challenge, the analysis shows that my engagement on posts reduced drastically as the days advanced. This says more about my motivation and all round consistency. That means, while I was consistent in posting, I did not maintain the energy I applied at first in engaging on posts. It is safe to say that the most important thing is not just posting, but engaging in posts also matters

### Below are recommendations with respects to the insights we uncovered.


### <ins>RECOMMENDATIONS</ins> 

### 1) High Drop-off Rate in Participation (Only 22.98% Active)

As we saw earlier, Out of 226 registered participants, only 52 (22.98%) were active. The rest (174 people) were inactive.
To support this, we also saw a sharp decline in participation after the first week. On the final day, only 25 participants remained active (down -88.94% from initial count).

**<ins>Recommendations:</ins>**

- Future challenges should include onboarding sessions to clarify expectations and benefits.
- Create a content calendar and prompt template for participants to reduce content ideation fatigue.
- Incorporate reminder systems and mid-challenge motivational nudges (e.g., automated WhatsApp reminders or milestone rewards).

**A Strategic Solution to this could be:**

- Designing a weekly milestone reward system (shout-outs, mini-prizes) to sustain motivation.
- Include peer accountability groups where participants are grouped and reminded by each other.


### 2) Participation Drops as the Week Progresses

As we saw, participant post rates are highest on Mondays and decrease steadily toward Sundays. This could have been caused by the fact that motivation and energy likely dip as the week progresses; weekends are often personal/family time and as such most participants are always busy.

**<ins>Recommendations:</ins>**

- Optimize challenge structure such that critical posts or tasks are scheduled for Monday–Wednesday.
- Weekend prompts should be lighter or more reflective, e.g., “Share your biggest takeaway this week.”

**A Strategic Solution to this could be:**

- Shortening the challenge to 14 days or making it a 3-post-a-week challenge to improve long-term commitment.
- Introducing a weekly leaderboard to make participation look more fun and to keep momentum up.


### 3) Humor Drives Impressions but Not Connection Growth
As seen in the “Audience Reaction” page, humor got 3,190 impressions (highest) but only 16 new connections. What this means is that, people love engaging with humor, but it may not showcase my professional value enough to earn connections.

**<ins>Recommendation:</ins>**

- I can use humor to attract attention, then follow up with high-value content (like Data Insights) that encourages connections.

**A Strategic Solution to this could be:**
  
- Introducing a content rotation schedule (e.g., Humor > Data Insights > Motivation > Learning).
- Ending humorous posts with subtle CTAs like “If you find this insightful, follow for more data-backed content.

  
### 4) Data Insights & Motivation Contents Attract New Connections
Contents in the Data Insights and Motivation category significantly outperform other content types in growing my network with 39 and 35 connections respectively

**<ins>Recommendations:</ins>**

- Prioritizing value-focused content—Motivational and Professional Insight posts should be the cornerstone of my strategy.

**A Strategic Solution to this could be:**

- Reusing my best-performing posts in different formats (short videos, infographics etc).
- Highlighting my experience or success stories to increase authenticity and engagement.


### 5) Impressions Don’t Always Convert to Engagements
As seen in our analysis, despite having 9,347 impressions, only 647 engagements occurred. To back this up, we also saw that its takes 14.45 impressions to get 1 engagement that is 14.45 impressions per engagement.

**<ins>Recommendations:</ins>**

- Subsequently, I can always focus on crafting call-to-engagement prompts (e.g., “Comment your thoughts,” “Tag someone who agrees”).
- Create carousel posts or polls which tend to improve interaction rates.

**A Strategic Solution to this could be** 

- Using hooks and open-ended questions in the first two lines of my posts.
- Including more appealing visual contents to improve resonance and scroll-stopping power.


### 6) Thursday Is Best for Engagement
The analysis shows that thursday posts received the most engagement—this aligns with your highest engagement post (March 6).

**<ins>Recommendations:</ins>**

- I can schedule my most important or experimental content for Thursdays.
- Use LinkedIn scheduling tools (like Buffer or Later) to automate Thursday posts.

### 7) I Engage More on Saturdays – Against the General Trend
My highest engagement on others` posts was on Saturdays, while others were least active then. This means that I have more free time on Saturdays, which is an opportunity to stand out.

**<ins>Recommendations:</ins>**

- Subsequently, I can capitalize on this timing to become a top engager—my comments will stand out more due to lower post volume. 

**A Strategic Solution to this could be** 

- I can use this time to build strategic relationships with industry influencers by engaging on their content.


### 8) Engagement Drops over Time – Motivation Decline
As observed, I started strong but my engagement on others’ posts declined, despite continued posting.

**<ins>Recommendations:</ins>**

- Introducing personal accountability mechanisms to stay consistent would help a lot (reminders, habit trackers, or accountability partners).
- Using pre-scheduled engagement sessions (e.g., 20 mins every morning) could also help.

**A Strategic Solution to this could be** 

- Using the “5/20 Rule”—engaging with 5 new people or posts every 20 minutes.
- Focusing on high-quality engagement (commenting) over high-volume liking.


### 9) My Engagement is Stronger in the Morning
The analysis shows that I have a total of 808 Engagements in the morning and 465 in the afternoons. What this means is that my productivity and visibility are higher in the morning.

**<ins>Recommendations:</ins>**

- I can schedule my highest-impact tasks (engaging, posting, replying to comments) in the morning.
- Test morning posting times (e.g., 8–10 a.m.) for improved visibility and traction.

Having made the above recommendations to help anyone who wishes to organize a challenge next time and anyone who like me will love to get the best from a challenge of this kind, I will love to identify the limitations of this project to help future analysis.


### <INS>LIMITATIONS OF THE PROJECT</INS> 

While this project helped me gain a lot of insights, there were a few limitations I noticed:
#### 1. Manual Data Collection
I collected and recorded all the data manually. This took time and could have led to small errors. It also made it hard to scale if I want to repeat this challenge or handle more participants in the future.

#### 2. Subjective Content Categories
The way I grouped content types (like “Humor” or “Motivation”) was based on my own understanding. Others might group them differently, which could affect interpretation.

#### 3.	No Information about My Audience
I couldn’t see details like who engaged with my posts — their industry, job title, or location — so it’s hard to know exactly who I’m attracting.

#### 4.	No Context Behind Engagement
While I tracked numbers (likes, comments, etc.), I couldn’t capture the quality of engagement — like what people were saying or who they were.

#### 5.	Why Participants dropped out wasn’t confirmed
I assumed reasons why people stopped participating in the challenge, but I didn’t ask them directly. Getting feedback from them would have helped.

#### 6.	No Way to Compare My Results to Others
I didn’t have LinkedIn average benchmarks to compare my results. If I had them, I could tell whether I did well or needed to improve.

### <ins>WHAT CAN BE IMPROVED</ins>

#### 1.	Automate Data Collection
Instead of recording everything manually, I can use LinkedIn analytics exports or tools that help track data automatically. This would save time and reduce mistakes.

#### 2.	Get Feedback from Participants
I’ll ask others in the challenge to share why they stayed active or dropped out. A short survey can help me understand what worked and what didn’t.

#### 3.	Track Different Post Types Separately
I didn’t separate my posts by format (e.g., text, poll, carousel). Doing that next time will show which types of posts perform best.

#### 4.	Try A/B Testing
I’ll experiment with different ways of writing my posts or using different CTAs (calls to action) to see what gets better engagement.

#### 5.	Compare My Results with Others
Next time, I’ll try to compare my results with average LinkedIn performance. This will help me know if I’m on track, doing better, or need to improve.


### <ins>CONCLUSIONS</ins>

This 21-day LinkedIn challenge was more than just a consistency test—it gave me real insights into what works, what doesn’t, and how I can grow my visibility and impact on LinkedIn. I learned that posting regularly is only one part of the puzzle. The type of content, how I engage with others, the timing, and even how I track progress all matter.
Though there were some limitations, this project has shown me the power of intentional content and data-backed reflection. With a few improvements, future challenges can be more impactful, scalable, and easier to manage—not just for me, but for anyone looking to grow their online presence in a meaningful way.

Thanks for Reading......



