# The Siyavula Project

The COVID-19 pandemic altered the world’s routines, wreaking havoc on everything from workplace practices to supply chains
to education. In education, it affected an estimated 1.6 billion students worldwide (The World Bank). In Africa, research done by
Human Rights Watch between April and August 2020 found that school closures due to the COVID-19 pandemic compounded
previously existing inequalities, leaving children who were already at risk of being excluded from quality education to be most
affected (Human Rights Watch, 2020).
<br>
To reach students, many countries in Africa hastily employed some form of remote learning as an emergency response. These
educational responses evolved as the pandemic did.
<br>
<br>

## [Siyavula](https://www.siyavula.com/)

**Siyavula is known as a pioneer developer of high-quality free digital and print Math and Science textbooks for South African
schools.**

Alongside developing digital workbooks and teachers' guides, Siyavula has also developed an adaptive practice technology called 
Siyavula Practice, which has a complete set of South African curriculum-aligned open textbooks to create an offering for High 
School Mathematics, Physics, and Chemistry. The Siyavula platform has managed to reach the lowest economic segment 
(Quintile 1 schools) in South Africa. In fact, more than 50% of the learners using Siyavula Practice attend Quintile 1–3 schools, 
that is, no- and low-fee schools.
<br>
<br>

## The Data

Siyavula assisted Gauteng Department of Education (GDE) in 2022 with the creation of a baseline assessment instrument in the form of 
an assignment on the Siyavula platform. The baseline assessment consists of 50 Mathematics curriculum-aligned questions.

**This project focused on analyzing the results of Grade 8 student's performance on the baseline assessment.** 
**It aimed to understand gaps in the syllabus and any behavioral patterns.**
**An ideal outcome was a Power BI dashboard from a 100GB database hosted on AWS containing the learner’s information to outline learner performance pre- and post-COVID-19.**
**This dashboard will be used by the GDE to make data-driven decisions about where and how to intervene to better address learning needs.**
<br>
<br>

## The Purpose and Problem

To prevent learning losses from accumulating once children go back to school, countries need to adopt learning recovery
programs consisting of evidence-based strategies.

In this study, we empirically evaluated the impact of online learning during the pandemic on students’ performance by comparing 
it with that of pre- and post-pandemic cohorts.
<br>
<br>

## Methodology

The data was queried from a PostgreSQL database connected to the Amazon S3 bucket and the data was then loaded into a Jupyter notebook to 
facilitate the running of optimized SQL queries. The resulting dataset was stored in CSV and then loaded into Microsoft Power BI for data 
visualization through the creation of a dashboard.
<br>
<br>

## Dashboard and Findings


![siyavula_project_1](images/siyavula_project_1.PNG)

<br>

Figure 1. Dashboard Home Page showing an overview of the data analysis.

<br>

![siyavula_project_1](images/siyavula_project_2.PNG)

<br>

![siyavula_project_1](images/siyavula_project_3.PNG)

<br>

![siyavula_project_1](images/siyavula_project_4.PNG)

<br>

![siyavula_project_1](images/siyavula_project_5.PNG)

<br>

![siyavula_project_1](images/siyavula_project_6.PNG)

Figure 1, shows that learners’ average baseline performance hovers around 70 percent, with 2022 having the lowest performance.
It can equally be seen that the number of respondents keeps increasing over the years, which indicates that more users keep
interacting with the online learning platform.
Performance comparison by quintile, shown in Figure 2, confirms that the highest economic class, quintile 5, has the highest
average performance in the baseline assessment, while quintile 1 has the lowest average performance in the baseline assessment.
This is an expected divide/difference due to the ease of access to resources (such as teachers with good qualifications) by quintile
5 learners as compared to quintile 1.
<br>
<br>

## Conclusion

The data shows a gap in performance between quantile groups, districts, and baseline items/chapters. The dashboard created will
enable the Department of Education to make the necessary changes and adjustments in order to bridge this gap and give direction 
as to which areas they should focus on for the current and future 8th-grade cohorts.
With the dashboard we have created, the Deputy Director of Curriculum can identify key areas where the learners' performance is
low, as shown in Figures 1 and 2, and equally identify the possible reasons for this low performance.
The dashboard shows the distribution of learners and their performance across many variables, such as schools, districts, subject
sections/topics, subject titles, quintiles, years, and so on. And with this, Siyavula can identify key areas that need improvement.
