# Projects

## sample company project - 
Real survey data from a telecom company - detailed EDA and visualizations

## WebMd 

### Executive Summary 
WebMD is an online publisher of health and wellness news and information. The site contains an extensive volume of drug-related information and it is one of the most popular healthcare websites in the U.S. Scraped from the WebMD website. our data includes around 0.36 million unique reviews that were updated until March 2020. The dataset also contains user evaluations of individual medications, as well as information on linked ailments, side effects, age, sex, and overall patient satisfaction ratings. In the project, we have utilized the NLTK packages and various types of classifiers such as decision tree, random forest and naive bayes to achieve the desired results.

The project aims to extract advanced understandings and focuses on automating sentiment analysis on drug reviews in WebMD. More particularly, by examining those reviews in great detail, the project provides significant insights into parents' diverse conditions, summarized drug ratings, numerous medications classes, and sentiments from patients, ultimately constructing the most ideal combination of feature representation methods and classifiers that could predict a patient’s satisfaction given a particular drug. 

### Business Goal Analysis
With analyses generated from the WebMD reviews, our goal is not only to establish sentiment ratings but also to predict future ratings by using machine learning algorithms. To automate such a process and significantly improve its efficiency, text analytics plays an imperative role since the majority of our data is heavily textual. Data visualizations are also an inseparable component of our project. More detailedly, the data visualizations include topics of drug ratings, medications classes, and patients' differentiated conditions.  To achieve the business goal, we conducted data preprocessing, data cleaning, data consolidation and management, feature engineering, classification representations, and eventually data mining with different classifiers. 


## Indeed Scraping

### Executive Summary
When it comes to the pursuit of dream jobs, one of the most important things for people to do is to quickly realize what requirements those jobs ask for so that people can reevaluate themselves, figure out whether they are qualified, and what kind of skills they still need to equip themselves with in order to stand out among other candidates. However, job descriptions, even the ones for positions with the same names, vary dramatically from each other, which may leave the job seekers confused about the set of skills that should be prioritized. We believe this problem can be solved by technical methods.
With the help of Indeed, the world’s largest recruitment website, we can gather detailed information on millions of different types of jobs all over the US. Using python, more particularly, with web scraping and programming, a system can be developed to help users all over the US quickly get the top required skills of their dream jobs. With a simple input of their target job’s name and location, users could effectively acquire accurate information on the skill sets needed for that particular job, preparing themselves for their bright future career.
Indeed is a vertical search engine specializing in providing job information. It was founded by Paul Foster and Rony Kahan in 2004 in the United States. In addition, as the largest job search engine in the world, Indeed focuses on improving the online job search experience and provides the most comprehensive and accurate job information for job seekers. It aggregates tens of millions of job listings from thousands of job sites, company websites, and job agencies. Job seekers can simply log in to Indeed to browse all of the information from different channels instead of visiting individual recruitment resources. Indeed also accepts resumes, job seekers can log in to their personal accounts and upload resumes. Currently, Indeed is available in over 60 countries and 28 languages.

### Business Goal Analysis.
Our goal is to use the results of data visualization to clearly and directly show job seekers the various skills and qualities required by each job post, and how those skills and traits are correlated to each position. The result can effectively help the job seekers know whether they have enough ability to qualify for this position while helping users choose the most appropriate target position.
When the candidates do not have enough ability for their target position, our output provides a straightforward demonstration of which skillset or quality they lack. And based on the diverse combinations of skills and qualities, job seekers can easily prioritize the qualities or skill sets they need to improve or acquire.
To achieve this goal, we have to gather detailed information about the job descriptions of all open positions related to the users’ target search. Then we use text analytics techniques including feature engineering and linear regression to process the job description contents and to extract meaningful keywords from all of these descriptions. Following that, we use logistic regression to calculate the coefficient of each skill or quality. Lastly and most importantly, we import visual tools to generate suitable diagrams to display the rank of different skills or qualities in accordance with each job seeker’s target position


## sample claims kaggle 
Drawing from Kaggle's repository of insurance claims data, this project embarked on an extensive journey of data refinement and analysis. Through rigorous feature engineering techniques, including data imputation, scaling for numerical variables, and categorical data encoding, the dataset underwent thorough preparation to ensure its suitability for subsequent modeling endeavors.

Feature selection methodologies, such as variance inflation factor (VIF) analysis and regression statistics, were meticulously applied to discern pivotal predictors and effectively reduce dimensionality. Recognizing the presence of non-linear relationships, polynomial transformations for independent variables and logarithmic transformations for the target variable were implemented prior to modeling, particularly leveraging the Ridge regression approach.

The modeling phase witnessed the deployment of robust nonparametric algorithms, namely the Random Forest Regressor and Gradient Boosting Regressor, with hyperparameter tuning facilitated via Grid Search methodology to optimize predictive accuracy and generalizability. Additionally, logistic regression facilitated the categorization of claims into 'high' and 'low' cost brackets, providing further insights into cost segmentation.

Post-modeling, a robust statistical validation framework was instituted. Hypothesis testing, encompassing assessments of claim cost disparities among employee types and gender segments, was conducted to unveil significant associations. Notably, Fisher's Exact test provided valuable insights into categorical variables' impact on claim costs, revealing noteworthy associations.

Lastly, time series analysis techniques, including Autoregressive Integrated Moving Average (ARIMA) and Seasonal ARIMA (SARIMA), were employed to uncover temporal patterns in claim cases. Complementarily, survival analysis techniques were utilized to assess claims reporting efficiency and identify influential factors impacting the process.

## sample company analytics and visualizations 
Real data from sample company, EDA, analytics, visualizations, and machine learning for strategetic business reccomendations and optimizations 
