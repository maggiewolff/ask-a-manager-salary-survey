# ask-a-manager-salary-survey

Every year, the Ask a Manager blog does a [salary survey](https://www.askamanager.org/2023/04/how-much-money-do-you-make-6.html) and shares the raw data with anyone who wants to view it.

I decided to explore the data from the 2023 survey to see what I could learn about Analytics & Data Science salaries, and also how the industry compares to other jobs.

Some of the questions I wanted to answer:

- What were the average salaries of the most common data-related jobs?
- How does the data industry compare to other jobs overall?

The survey goes live in April, and I downloaded the data in August. There were 16,888 submissions at the time of my download. After doing minimal data cleaning (convert to lowercase, remove any leading or trailing spaces, and replace “sr” and “sr.” with “senior), there were 8,739 unique job titles.

**Data Biases**

I know the data from this survey is not a perfect representation of all jobs. It is likely going to skew towards people working in white-collar jobs, and as you’ll see below, women are over 75% of the responses.

Additionally, once I dug into the data based on specific job titles and levels, the number of responses got very small, generally too small to be truly representative.

There are many other sources of salary information out there, I highly recommend consulting multiple sources if you are trying to do research for salary negotiation.


**Exploring Data Salaries**

Data jobs had an average annual base salary of $110,938 whereas non-data jobs had an average annual salary of $101,073. Data jobs paid 9.8% more than non-data jobs.

For total annual compensation, data jobs paid $129,029 and non-data jobs paid $115,362. Data jobs paid 11.8% more.

Within data jobs, I took a look at averages by job family and job level to better understand how their average annual base salaries compared.

In terms of the job family, the most popular and their average base salary:

- Data Analyst: $87,718
- Data Scientist: $149,365
- Analytics: $141,109 — this term was usually used for managerial roles
- Data Engineer: $130,470

And looking further into each job family, reporting salary by levels where there were 5 or more salaries reported:

Data Analyst salaries averaged from $70,000 for entry-level, $80,000 for mid-level, and just over $100,000 for senior.

Data Scientist salaries averaged $125,000 for mid-level, around $170,000 for senior, and $175,000 for lead/staff/principal roles.

Data Engineers averaged $125,000 for mid-level and $135,000 for senior.


When “Analytics” was used, it was usually for a managerial role. However, some companies use the title “Analytics Manager” as a functional, non-people manager role. It’s hard to know for sure based on the title alone. Regardless, salaried averaged around $120,000 for mid-level, $130,000 for manager, $150,000 for senior (possibly senior manager based on the logic of my code), and close to $160,000 for director.

**Other Trends**

The salary survey included non-compensation questions, such as age, gender, education, tenure (in your field and working overall). I was curious how data jobs compared to non-data jobs, and how data job families compared.

Education

- PhD: 12% of those in data jobs, 6% of non-data jobs
- Masters: 37% of those in data jobs, 34% of non-data jobs
- Bachelors: 43% of those in data jobs, 46% non-data jobs

Overall, 92% of respondents working in data jobs reported having at least a bachelor's degree compared to 86% of those in non-data jobs.

Digging into job family:

Data Scientists:

- 45% had a PhD (2% had a JD or MD or similar)
- 27% had a masters
- 27% had a bachelors

Data Engineers:

- 8% had a PhD
- 38% had a masters
- 49% had a bachelors
- 5% had not finished at least a bachelors

Data Analysts:

- 2% had a PhD
- 39% had a masters
- 49% had a bachelors
- 10% had not finished at least a bachelors

Gender

Overall, 77% of the respondents of the survey identified as women, which is likely a bit skewed from reality. Looking at the breakdown of the respondents within data jobs was also skewed compared to reality. Rather than reporting the percentages, looking at trends, Data Analysts had the highest percentage of respondents who identified as women, and Data Scientists had the lowest percentage of women.

**Conclusion**

Overall, the outcome from the salary survey matched other research I’ve done:

- Data jobs pay more than average
- Data Science and Data Engineering roles pay more than Data Analyst
- Data Scientists are more likely to have advanced degrees
