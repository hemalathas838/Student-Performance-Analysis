\# Student Performance Analysis



\## Project Overview



This project analyzes student performance data to understand factors associated with academic scores, identify at-risk students, and provide actionable recommendations for improving student outcomes.



The analysis uses the \*\*Students Performance in Exams\*\* dataset containing 1,000 student records.



\## Objectives



\* Explore and understand the student performance dataset

\* Clean and prepare the data for analysis

\* Analyze factors associated with student performance

\* Compare student performance across different groups

\* Identify students who may be at academic risk

\* Create meaningful visualizations

\* Provide actionable recommendations



\## Tools and Technologies



\* Python

\* Jupyter Notebook

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn



\## Dataset



The dataset contains information about:



\* Gender

\* Race/Ethnicity

\* Parental Level of Education

\* Lunch

\* Test Preparation Course

\* Math Score

\* Reading Score

\* Writing Score



\### Dataset Summary



\* Total Students: 1,000

\* Original Columns: 8

\* Missing Values: None



\## Analysis Performed



The project answers the following questions:



1\. Does parental education level affect student scores?

2\. Do students who complete the test preparation course score higher?

3\. What is the correlation between reading, writing, and mathematics scores?

4\. Which gender performs better in each subject?

5\. What is the distribution of total student scores?



\## Visualizations



The project includes the following visualizations:



1\. Total scores by parental education level

2\. Average total score by test preparation course

3\. Correlation heatmap of subject scores

4\. Average subject scores by gender

5\. Distribution of total student scores

6\. Reading score vs mathematics score

7\. Students scoring below 50 by subject



\## At-Risk Student Analysis



A student is classified as \*\*at-risk\*\* if their score is below 50 in at least one subject.



\### Results



| Status      | Number of Students | Percentage |

| ----------- | -----------------: | ---------: |

| At-Risk     |                188 |      18.8% |

| Not At-Risk |                812 |      81.2% |



\### Subject Risk



| Subject     | Students Below 50 | Percentage |

| ----------- | ----------------: | ---------: |

| Mathematics |               135 |      13.5% |

| Reading     |                90 |       9.0% |

| Writing     |               114 |      11.4% |



\### Test Preparation and At-Risk Percentage



| Test Preparation | At-Risk Percentage |

| ---------------- | -----------------: |

| Completed        |             10.06% |

| None             |             23.68% |



\### Parental Education and At-Risk Percentage



| Parental Education | At-Risk Percentage |

| ------------------ | -----------------: |

| Some High School   |             25.70% |

| High School        |             25.00% |

| Some College       |             16.81% |

| Associate's Degree |             14.86% |

| Bachelor's Degree  |             13.56% |

| Master's Degree    |             10.17% |



\## Key Findings



\* 188 students (18.8%) were identified as at-risk.

\* Students who completed test preparation had a lower observed at-risk percentage than students who did not complete it.

\* At-risk percentages varied across parental education groups.

\* Mathematics had the highest percentage of students scoring below 50.

\* The observed at-risk percentage differed between male and female students.



These findings describe associations in the dataset and do not by themselves establish cause and effect.



\## Recommendations



\### 1. Strengthen Mathematics Support



Provide targeted mathematics support sessions, additional practice exercises, and regular assessments for students who need additional help.



\### 2. Expand Test Preparation Support



Provide structured test-preparation sessions, practice tests, revision materials, and study guidance.



\### 3. Introduce Early Academic Monitoring



Identify students who fall below the academic threshold early and provide tutoring, mentoring, and appropriate learning resources.



\## Project Structure



```text

Student-Performance-Analysis/

│

├── dataset/

│   └── StudentsPerformance.csv

│

├── visualizations/

│   ├── parental\_education.png

│   ├── test\_preparation.png

│   ├── correlation\_heatmap.png

│   ├── gender\_subject.png

│   ├── total\_score\_distribution.png

│   ├── reading\_math\_scatter.png

│   └── subject\_risk.png

│

├── Student\_Performance\_Analysis.ipynb

│

└── README.md

```



\## Conclusion



The analysis provides an overview of student academic performance and identifies groups that may benefit from additional academic support. The results can help the school focus on mathematics support, test preparation, and early monitoring of students who may be at risk.



