# TEXT MINING EMPLOYER BRAND AND EMPLOYEE SATISFACTION

## Executive Summary

Text Analytics is gaining importance with each passing day and individuals and organizations are exploring ways to use this to their own advantage. We too attempt to leverage the benefits of text analytics and implement it in the area of human resources to gain some meaningful insights useful for both the organizations and candidates looking for jobs. Social media data has been exploited to understand the pulse of general populace for a product or service, but we try to look at the employees view of employers. We extract employee reviews from Glassdoor for textual analysis to understand the employer brand and employee’s satisfaction with their employers.

The organizations we analyze in this study are Microsoft, Amazon, Google and IBM. The reviews are anonymous, and we extract all the reviews from 2008 to 2020. We applied well researched text analytical methods like sentiment analysis and similarity score analysis in this study. We also experiment with different ways of doing the analysis to ensure we use what is suitable for the corpus and task we have at hand.  

We found that the employee satisfaction with all the companies have declined from 2008 and Google and Microsoft are doing better on employee satisfaction metric compared to Amazon and IBM. We also identify the characteristics which are fetching highly positive and highly negative reviews for each of these companies. The results of this study are aggregated into a dashboard for easy reference.

## Problem Definition and Significance

Every organization has a reputation, which includes thoughts attached to its products and services, history and people involved. People, over time develop this reputation and associate certain characteristics with an organization. This becomes the brand of a company. In a similar way, every organization has a secondary brand called Employer brand, which is the emotional reaction people have to the idea of working for an employer. This brand lives in the minds of employees - former, current and future. 

Companies with positive employer brands stand to gain in more than one way. The most significant impact a positive employer brand has on a company is in the area of recruitment. It is noted that companies with positive employer brands can get up to twice as many applicants as companies with negative brands and the costs drop by almost 43%. We don’t have to stress further how important this is, especially in the era when it is getting difficult to hire the right talent. Also, to gauge the significance of employer brand, one can look no further than the costs incurred by companies who fail to invest in their reputation as an employer, which is on an average $5,000 per employee.

In addition, 78% of candidates look at the company’s employer brand before applying for a job and 88% of millennials believe that being part of the right company is of at most importance. We all know how important salary is for job applicants, but a CareerBuilder report found that 67% of candidates are willing accept lower pay to be part of a company that has positive reviews online. It is becoming increasingly important for companies to build a positive employer brand on social media platforms as 79% of candidate pool are likely to use of social media in their job search.

Keeping these details in mind, we set out to explore employer brand and employee satisfaction of four major employers in the U.S. We intend to find the key characteristics of these companies which are fetching high positive and negative reviews and chart out the employee satisfaction from the reviews provided on social media platform Glassdoor. A collective dashboard with these findings will help employers make decisions to either improve or alter employer brand and potential job candidates to identify a preferred employer.

## Prior Literature

The areas of employer branding and employee satisfaction have always dominated analytics domain in Human Resources function and are looked at extensively by many people and organizations. Although there has been lot of research on these topics, there was limited work which looked at Text mining employee reviews on social media to obtain employer brand characteristics and employee satisfaction. 

<i>Employee Satisfaction and Corporate Performance</i> looked at mining employee reviews from Glassdoor to understand the relation between employee satisfaction and organizational performance across industries. The study found that there is a positive correlation between general employee satisfaction and corporate performance along with the categories which correlated positively and negatively with performance. <i>Improving Employee Satisfaction Through Text Analytics</i> explored the employee satisfaction of six technology companies using predictive rule-based model on text portions of the reviews from Glassdoor. The study found the words from text which make the review positive or negative using classification techniques. <i>Text Mining Company Reviews</i> tried to find what employees write the most about their workplace experience and if they viewed the organization positively, negatively or neutrally. The study looked the frequency of single words and two words together to look at what was most talked about and ran sentiment analysis on the reviews to understand the variation of sentiment across the time range of reviews. 

However, these studies did not go on to make a comprehensive analysis on employer brand and were limited to sentiment analysis and extracting the most frequent words. Thus, we try to take inspiration from these works and use them as foundation to provide both organizations and employees a comprehensive analysis on employer characteristics that are viewed favorably and unfavorably along with the variation in employee satisfaction over the years.

## Data Source and Preparation

Social media has had large impact on multiple areas including in the domain of Analytics. The abundant of social media data made the data gathering easier for all types of analysis. One such social media platform is the Glassdoor website. Glassdoor.com was founded by Robert Hohman, Rich Barton and Tim Besse in 2007 (Glassdoor: About Us 2016). It is a website where current and former employees anonymously provide review for their respective companies. Glassdoor covers a diverse user population where users’ profiles are fairly distributed across different sectors such as age, income, education. Glassdoor contains 475,000+ companies with more than 8 million company reviews, company ratings along with salary reports from worldwide locations. 

We used Web crawling technique to get the data from Glassdoor.com. We scraped the reviews for four major employers in US – Microsoft, Google, Amazon and IBM and crawl a total of 100,000+ reviews from 2008 to Mar 2020. Figure 1 below shows the final generated corpus.

![Capture2](https://user-images.githubusercontent.com/46653178/82082900-d2055300-96b6-11ea-92ef-fe4e6916ac65.JPG)
Figure 1: Sample of the data scraped from Glassdoor
