<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Predictive Employee Turnover

*Ana André, Data Squad 21 <br />
Lisbon, 11.10.2019*


## Content
- [1. Project Description](#project-description)
- [2. Motivation](#motivation)
- [3. Dataset](#dataset)
- [4. Workflow](#workflow)
- [5. Questions](#questions)
- [6. Wrangling and cleaning](#cleaning)
- [7. Exploratory data analysis](#analysis)
- [8. Model Training and Evaluation](#model-training-and-evaluation)
- [9. Conclusion](#conclusion)
- [10. Future Work (ongoing..)](#future-work)
- [11. Links](#links)


<a name="project-description"></a>
## 1. Project Description

The scope of this project was to understand the causes of employee turnover in a big company and predict which employees are most likely to leave.

The project was divided into 3 stages:
- profile the employees who left the company,
- understand the reasons that led them to leave the company,
- predict which employees are most likely to leave.

For the first and second stages, I used python both to analyze (Pandas, Numpy and Statsmodels libraries) and visualize the data (Matplotlib and Seaborn libraries). For data viz and dashboards, I also used Tableau.

For the third stage, I used python's Scikit-Learn library to create the supervised machine learning prediction model.

This was my final project as an Ironhack's data analytics bootcamp student. The aim of the project was to choose a topic and perform an end-to-end analysis using what we've learned throughout the course. For more details about the context and/or the requirements to meet, please check folder [0_Context](https://github.com/Ana-Andre/Predictive-Emplyee-Turnover/tree/master/0_Context).

I used Trello as a project management tool with Kanban methodologies.


<a name="motivation"></a>
## 2. Motivation

Employee turnover refers to the workers who leave an organization and are replaced by new employees. It can have a harsh impact in a company mainly because:
- it's very costly to replace an employee (first the separation and then the recruitment, replacement and training of the new employee)
- it affects produtivity: voids in the workforce mean overwork and stress for the ones staying and it destabilizes both the team and the mood
- it affects business as it can deteriorate client's satisfaction due to regular changes in consultants which can lead to loss of business with clients.

Predictive analysis in human resoures (HR) is a game changer in the industry, either because it can help organizations to take steps and improve the employer-employee relationship before it even becomes a problem (preventing turnover), or as way to measure the business impact of people policies.

By taking unprocessed data and extract actionable insights which can then be applied to everday processes and improve engagement strategies, HR analytics holds enormous values for companies.


<a name="dataset"></a>
## 3. Dataset

I got the dataset from [Kaggle](https://www.kaggle.com/ludobenistant/hr-analytics).
The data has 14 999 samples and 10 features, whose description is given below:
- satisfaction_level (numeric): employees level of satisfaction (scores from 0 to 1, 0 for totally unsatisfied and 1 for totally satisfied)
- last_evaluation (numeric): employee's last performance evaluation score (scores from 0 to 1, 0 for null performance and 1 for excelent performance)
- number_project (numeric): number of projects assigned to the employee
- average_montly_hours (numeric): average monthly hours at workplace
- time_spend_company (numeric): years as a companie's employee
- Work_accident (numeric): whether the employee had a workplace accident (1 for yes or 0 for no)
- left (numeric): whether the employee left the workplace or not (1 for yes or 0 for no)
- promotion_last_5years - whether the employee was promoted in the last five years (1 for yes or 0 for no)
- sales (categorical): department the employee works for
- salary (categorical): relative level of salary (low, medium, high).


<a name="workflow"></a>
## 4. Workflow

In a general way, the worflow for this project was:
1. choose the topic and find the data
2. ask the questions
3. clean the data
4. exploratory data analysis
5. create dashboards with Tableau
6. build the predictive modelling (model training and evaluation).


<a name="questions"></a>
## 5. Questions

As already mentioned, the 3 main questions for this project were:
- What's the profile of the workers who left the company?
- Why did they leave the company?
- Who are the ones most likely to leave?


<a name="cleaning"></a>
## 6. Data wrangling and cleaning

Describe your full process of data wrangling and cleaning. Document why you chose to fill missing values, extract outliers, or create the variables you did as well as your reasoning behind the process.


<a name="analysis"></a>
## 7. Exploratory data analysis

* Overview the general steps you went through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Include charts to demonstrate the effect of your work.
* If you used Machine Learning in your final project, describe your feature selection process.


<a name="model-training-and-evaluation"></a>
## 8. Model Training and Evaluation

*Include this section only if you chose to include ML in your project.*
* Describe how you trained your model, the results you obtained, and how you evaluated those results.


<a name="conclusion"></a>
## 9. Conclusion

* Summarize your results. What do they mean?
* What can you say about your hypotheses?
* Interpret your findings in terms of the questions you try to answer.


<a name="future-work"></a>
## 10. Future Work (ongoing..)

Address any questions you were unable to answer, or any next steps or future extensions to your project.


<a name="links"></a>
## 11. Links

[Dataset](https://www.kaggle.com/ludobenistant/hr-analytics)
[Repository](https://github.com/Ana-Andre/Predictive-Emplyee-Turnover)  
[Presentation](https://bit.ly/2r4yBUR)
[Tableau Dashboards]() 