Marketing Insight Report – Website Traffic Data
Introduction
Welcome to my first medium blog post! I’m John, a data analyst currently upskilling and advancing my career. I recently joined the HNG Internship Program, where interns complete industry-specific tasks to prove their expertise. This blog documents my analysis journey in this internship, and I’ll be sharing valuable insights along the way!
This report presents an exploratory analysis of website traffic data, focusing on user engagement and behavior. The dataset includes key metrics such as page views, session duration, bounce rate, traffic sources, time on page, previous visits, and conversion rate. The objective is to uncover traffic trends, user interaction patterns, and optimization opportunities.
Observations
Data Familiarization
The data was loaded in excel.
 The dataset contains 7 rows and 2000 rows.
Variables and data types:
1.	Page Views: The number of pages viewed during a session (numerical).
2.	Session Duration: The total duration of the session in minutes (numerical).
3.	Bounce Rate: The percentage of visitors who navigate away from the site after viewing only one page (numerical).
4.	Traffic Source: The origin of the traffic (e.g., Organic, Social, Paid) (categorical).
5.	Time on Page: The amount of time spent on the specific page (numerical).
6.	Previous Visits: The number of previous visits by the same visitor (numerical).
7.	Conversion Rate: The percentage of visitors who completed a desired action (e.g., making a purchase) (numerical).

Checking for Missing or Unusual Data
 The data did not contain duplicate values.
 The data did not contain missing values.
Using the filter function to go through the data, I did not find any negative or unusual data. From what I found from the data so far, the data is very clean.
Looking for Basic Patterns
I sorted the Page Views column in descending order and found out that the highest page views (i.e. page views between 14 and 9) have a conversion rate of 1, a conversion rate of 1 means that 100% of users in that session completed the desired action, such as making a purchase, signing up, or filling out a form.
 
I sorted the Session Duration column in descending order and found out that the highest session durations (i.e. session durations between 20.29 and 5.436) have a conversion rate of 1.
 
I sorted the Time on Page column in descending order and found out that the highest times on pages (i.e. between 24.796 and 6.184) have a conversion rate of 1.
 
Insights
1. Traffic Distribution by Source
•	The Organic channel had the highest number of sessions (786 out of 2000), making up the largest share of traffic.
•	Paid traffic followed with 428 sessions, while Referral traffic contributed 301 sessions.
•	Direct and Social traffic accounted for 216 and 269 sessions, respectively.
•	This indicates that a significant portion of website visitors arrive via search engines (Organic) rather than paid advertising.
2. Bounce Rate by Traffic Source
•	The lowest bounce rate was observed for Referral traffic (26.63%), suggesting that users arriving from referral links tend to engage more.
•	Organic traffic (28.18%) and Direct traffic (28.46%) had similar bounce rates, indicating moderate user engagement.
•	Paid traffic (29.60%) and social traffic (29.63%) had the highest bounce rates, which may indicate that users from these sources leave quickly without interacting much.
3. Conversion Rate Analysis
•	The overall conversion rate averaged 98.21%, indicating a very high conversion success rate across all channels.
•	Referral traffic had the highest conversion rate (98.77%), meaning users who arrived via referrals were the most likely to complete a desired action.
•	Social (98.27%) and Organic (98.23%) traffic also performed well in terms of conversion.
•	Direct (97.87%) and Paid (97.90%) traffic had slightly lower conversion rates but were still highly effective.

Conclusion
Summary of Observations
1.	Data Quality
o	The dataset is clean, with no duplicates, missing values, or negative/unusual data. This ensures reliability for further analysis.
2.	Conversion Rate Trends
o	Higher engagement leads to higher conversions:
	Sessions with the highest Page Views (9–14) had a 100% conversion rate (Conversion Rate = 1).
	Users with longer Session Durations (5.4–20.3 minutes) were also more likely to complete a conversion.
	Visitors spending the most time on a page (6.2–24.8 minutes) had the highest likelihood of converting.
o	These findings suggest that users who engage deeply with the website are more likely to take the desired action (e.g., making a purchase, signing up, or filling out a form).
3.	Traffic Source Insights
o	Organic traffic is the largest source of visitors, while Referral traffic has the highest engagement and conversion rates.
o	Social and Paid traffic have the highest bounce rates, which may indicate less relevant audience targeting or room for landing page optimization.
Next Steps & Areas for Further Analysis
1.	Investigate Social and Paid Traffic: Identify why users leave quickly and explore ad targeting improvements.
2.	Optimize High-Value User Engagement: Analyze what keeps engaged users on the site and apply these insights to other user segments.
3.	Segment Conversion Actions: Since the overall average conversion rate is very high (98.21%), differentiate between types of conversions (e.g., purchases vs. sign-ups).
4.	Deeper Traffic Analysis: Explore demographics, devices, and session timing to refine marketing strategies.
For more insights on digital marketing strategies, visit the HNG Internship Program.
