# Project: Student Mental Health Survey

## Overall
### Project title: Identifying Key Stressors Affecting University Students' Mental Health
### Purpose and Outcome
  #### Purpose: 
  Focusing on these key stressors and using a combination of quantitative and qualitative methods, to gain a comprehensive understanding of the factors affecting university students' mental health
  #### Outcome: 
  The expected outcome—a detailed report with actionable recommendations—will support universities in enhancing student well-being, addressing critical issues such as academic pressure, financial concern, level of depression,anxiety and isolation.

## Dataset overview
The Student Mental Health Survey dataset contains detailed information on the mental health and well-being of students, covering various aspects of their academic and personal lives.

- **Survey Participants**: The survey includes responses from 87 students across 5 universities, representing 4 different majors.
- **Demographic Information**: Gender, age, university, degree level, and major provide context on the student's background and academic environment.
  >> Column: | gender | age | university | degree_level | degree_major |
  
- **Academic Performance**: Details such as current CGPA, academic year, and satisfaction with their field of study help illustrate the academic pressures faced by students. The dataset also includes the students' perceptions of academic workload and pressure.
  >> Column: | cgpa | academic_year | study_satisfaction | academic_workload | academic_pressure |
  
- **Residential Status and Campus Experience**: The dataset captures students living condition and whether they have experienced discrimination.
  >> Column: | residential_status | campus_discrimination |

- **Lifestyle Factors**: Information about sports engagement and average sleep hours per night gives insights into the students' physical health and habits.
  >> Column: | sports_engagement | average_sleep |
  
- **Mental Health and Well-being**: The dataset captures how often students experience depression, anxiety, etc... These critical factors highlight the mental health difficulties students encounter throughout their academic path.
  >> Column: | depression | anxiety | isolation | future_insecurity |

- **Financial and Social Factors**: The dataset also includes students' financial worries and the strength of their social connections, offering a comprehensive perspective on elements that could impact their overall well-being.
  >> Column: | financial_concerns | social_relationships | 

- **Stress Relief Activities**: Lastly, the dataset explores the activities students engage in to manage stress.
  >> Column: | stress_relief_activities |

## 0. Using tools and platform
### Tools: Python
- Model:
    - Ordinal Model-Ordinal Logistic Regression: It is a regression model designed to predict the probability that an observation falls into a specific level of an ordinal dependent variable, based on independent variables.
    - Kruskal-Wallis: support statistical analysis
    - Mann-Whitney U test: It is a non-parametric statistical method used to compare the differences between two independent groups
    - Chart (pỉe chart, Box Plot, Bar Plot, ..)
- Platform: Colab
## 1. Data processing (in English)
- 1.1 Import liberies
- 1.2 Where is data come from and what are they contained?
- 1.3 What do we have for data overview?
## 2. Exploratory Data Analysis - EDA (in English)
- 2.1 Demographics: Who are the students in this study?
- 2.2 Academic Profile: What do they study, how do they study, and how do they feel about studying?
- 2.3 Mental Health: What mental challenges are affecting them?
- 2.4 Habits and Activities: How do they live and cope with stress?
- 2.5 The relationship between stressors and mental health.
    - Are there differences between male and female students when it comes to facing anxiety?
    - Does academic pressure impact depression?
    - The relationship between stressors and mental health
## 3. Focusing on these key stressors to gain a comprehensive understanding of the factors affecting university students' mental health (in Vietnamese)
- What is the relationship between categorical factors and depression/anxiety?
- How does academic pressure and financial_concerns affect anxiety and depression?
## 4. Hypothetical Scenario (in Vietnamese)
## 5. Conclusion and Recommendation (in Vietnamese)
- Conclusion
- Recommendation
