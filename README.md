# Yandex Practicum Data Science Projects

Repository containing portfolio of **Data Analytics** | **Data Science** with **Machine Learning** projects completed during the training courses at **Yandex.Practicum**

[![certificate](https://img.shields.io/badge/сertificate-Data%20Scientist%20ENG-8abd80)](https://github.com/imeleges/YPDS_Projects/tree/main/certificates/сertificate_yandex_data_scientist_ENG.png)  


## Projects list:  
- [![PROJ_01](https://img.shields.io/badge/🔗%20PROJ-01-success)](#bank-data-analysis-borrower-reliability-research) "Bank Data Analysis: Borrower reliability research"  
- [![PROJ_02](https://img.shields.io/badge/🔗%20PROJ-02-success)](#real-estate-market-analysis-apartments-for-sale-in-st-petersburg) "Real Estate Market Analysis: Apartments for sale in St. Petersburg"  
- [![PROJ_02](https://img.shields.io/badge/🔗%20PROJ-03-success)](#telecom-company-pt-1-statistical-data-analysis-determination-of-a-profitable-plan) "Telecom Company Pt 1: Statistical Data Analysis. Determination of a profitable plan"
- [![PROJ_04](https://img.shields.io/badge/🔗%20PROJ-04-success)](#gamedev-studying-the-patterns-that-determine-the-success-of-game-platforms) "Gamedev: Studying the patterns that determine the success of game platforms."
- [![PROJ_05](https://img.shields.io/badge/🔗%20PROJ-05-success)](#telecom-company-pt-2-building-a-model-to-determine-a-suitable-tariff) "Telecom Company Pt 2: Building a model to determine a suitable tariff" 
- [![PROJ_06](https://img.shields.io/badge/🔗%20PROJ-06-success)](#bank-customer-churn-modeling) "Bank customer churn modeling"
- [![PROJ_07](https://img.shields.io/badge/🔗%20PROJ-07-success)](#choosing-a-region-for-the-development-of-new-oil-fields) "Choosing a region for the development of new oil fields"
- [![PROJ_08](https://img.shields.io/badge/🔗%20PROJ-08-success)](#building-machine-learning-algorithm-for-a-metalworking-enterprise) "Building machine learning algorithm for a metalworking enterprise"
- [![PROJ_09](https://img.shields.io/badge/🔗%20PROJ-09-success)](#insurance-company-development-of-an-algorithm-to-protect-customer-data) "Insurance Company: Development of an algorithm to protect customer data"
- [![PROJ_10](https://img.shields.io/badge/🔗%20PROJ-10-success)](#car-price-prediction-model) "Car price prediction model"
- [![PROJ_11](https://img.shields.io/badge/🔗%20PROJ-11-success)](#ride-hailing-company-predicting-the-number-of-taxi-orders) "Ride-hailing Company: Predicting the number of taxi orders"
- [![PROJ_12](https://img.shields.io/badge/🔗%20PROJ-12-success)](#natural-language-processing-classifying-comments) "Natural Language Processing: Classifying comments"
- [![PROJ_13](https://img.shields.io/badge/🔗%20PROJ-13-success)](#optimization-of-electricity-consumption-in-industry) "Optimization of electricity consumption in industry"

***

[![PROJ_01](https://img.shields.io/badge/go%20to%20PROJ-01-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_01)  
## "Connection between loan borrower's features and chances of him paying back"  

### Task
Based on bank clients' statistics related to returning the loans, investigate whether marital status or number of children affect the repayment probability of the loan on time

### Description 
Bank credit department has data on the solvency of their customers.  
This project required cleaning data from outliers, processing missing values and duplicates, as well as data types conversion. Categorization of clients is done using lemmatization.
A credit scoring model is built to evaluate the ability of a potential borrower to repay a loan to a bank.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![PyMystem3](https://img.shields.io/static/v1?label=tool&message=PyMystem3&color=cd6133)](#)  

[![Lemmatization](https://img.shields.io/static/v1?label=skill&message=Lemmatization&color=1B9CFC)](#)
[![Data preprocessing](https://img.shields.io/static/v1?label=skill&message=Data%20Preprocessing&color=B33771)](#)

***

[![PROJ_02](https://img.shields.io/badge/go%20to%20PROJ-02-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_02) 
## "Fraud prevention in Real Estate listings"  
 
### Task  
Based on data from a real estate service for St. Petersburg, Russia, determine the cost of listings based on their parameters to delect fraudulent ones

### Description
Conducted research analysis and data preprocessing for a dataset with apartments listed for sale.
To determine anomalies that might indicate fraud flat features explored: distance from the city center, area in square meters, ceiling height, number of rooms, district, publishing date and price.
Market value of real estate objects was determined uwing Yandex Real Estate Service platform data.
Feature engineering, histograms, boxplots, scatterplots to explore features affecting the price.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)  

[![Data visualization](https://img.shields.io/static/v1?label=skill&message=Data%20visualization&color=F97F51)](#)
[![Exploratory data analysis](https://img.shields.io/static/v1?label=skill&message=Exploratory%20Data%20Analysis&color=82589F)](#)
[![Data preprocessing](https://img.shields.io/static/v1?label=skill&message=Data%20Preprocessing&color=B33771)](#)

***

[![PROJ_03](https://img.shields.io/badge/go%20to%20PROJ-03-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_03) 
## "Telecom Company Part 1: Statistical Data Analysis. Determination of a profitable tariff plan"

### Task  
Based on a mobile network provider's customer behavior data, recommend the tariff that brings most profit

### Description
A telecom operator clients use outdated tariffs.
Sample customers' tariff plan usage analysis helped to find suitable plan recommendations for users.
A/B-test results showed statistically significant revenue difference between two tariffs. Another hypothesis checked with A/B-test - higher revenue from Moscow clients and other regions combined.
To adjust the advertisement budget a more profitable tariff plan has been determined and advised to the marrketing team.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![SciPy](https://img.shields.io/static/v1?label=tool&message=SciPy&color=34ace0)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=Seaborn&color=ff5252)](#)  

[![Descriptive statistics](https://img.shields.io/static/v1?label=skill&message=Descriptive%20statistics&color=58B19F)](#)
[![Statistical hypothesis testing](https://img.shields.io/static/v1?label=skill&message=Statistical%20hypothesis%20testing&color=3B3B98)](#)

***

[![PROJ_04](https://img.shields.io/badge/go%20to%20PROJ-04-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_04)
## "Gamedev: Studying the patterns that determine videogame platform success"

### Task  
Using historical user and expert ratings date, genres and number of copied sold for various platforms, identify patterns that contribute success of a game

### Description
An online computer games store has customers worldwide. Historical data about games from open sources is available to identify a potentially popular product. This helps to plan advertising campaigns.
Games that are the best bet for being popular and bring most sales are selected. Customer preferences for various regions of the world are noted.
A/B-test results revealed that average user ratings between platforms Xbox One and PC do not have statistically significant difference.
Another A/B-test showed that average user ratings between genres Action and Sports are different.
T-test for independent samples.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![SciPy](https://img.shields.io/static/v1?label=tool&message=SciPy&color=34ace0)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=Seaborn&color=ff5252)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)  

[![Descriptive statistics](https://img.shields.io/static/v1?label=skill&message=Descriptive%20statistics&color=58B19F)](#)
[![Statistical hypothesis testing](https://img.shields.io/static/v1?label=skill&message=Statistical%20hypothesis%20testing&color=3B3B98)](#)
[![Data preprocessing](https://img.shields.io/static/v1?label=skill&message=Data%20Preprocessing&color=B33771)](#)
[![Exploratory data analysis](https://img.shields.io/static/v1?label=skill&message=Exploratory%20Data%20Analysis&color=82589F)](#)

***

[![PROJ_05](https://img.shields.io/badge/go%20to%20PROJ-05-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_05)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Telecom Company Part 2: A tariff recommendation model "  

### Task  
Based on the previous data study, build the Machine Learning model for the classification problem, which finds a suitable tariff

### Description
A system recommending users a more suitable tariff based on their data usage, amount of calls and sms.
A classification model with the highest accuracy value is built to select the tariff to be suggested to the user.
Correct ratio answers raised to 0.75. Accuracy tested on the test sample.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_06](https://img.shields.io/badge/go%20to%20PROJ-06-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_06)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Bank customer churn modeling"  

### Task  
Analyse data of clients terminating their contract with the bank and to choose strategy of retainung them or attracting new clients

### Description
More clients leave the bank every month. 
A model is build using unbalanced data to predict the probability of a client leaving the bank in near future.
High F1 sroce was reached with subsequent verification on a test sample. Additionally AUC-ROC score was measured, correlated with F1 score. 

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_07](https://img.shields.io/badge/go%20to%20PROJ-07-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_07)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Choosing a region for the development of new oil fields"  

### Task  
Selecting the most profitable regions for oil extraction. Building a machine learning model helping determine the area where drilling will bring the most profit with the least risk of loss.

### Description
An oil company needs to make decion on developing the next well location.
The existing data is oil samples' characteristics for varoius wells. Data contains oil quality parametres and oil reserves information in three regions. Characteristics of each well in the region are already known.

A machine learning model forecasts oil reserves in new wells.
The model assists in picking the region with most profitable set of wells to be drilled.

Part of the research is potential profit and risk assessment using `Bootstrap` methodology.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)
[![Bootstrap](https://img.shields.io/static/v1?label=tool&message=Bootstrap&color=ffb142)](#)
[![SciPy](https://img.shields.io/static/v1?label=tool&message=SciPy&color=34ace0)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_08](https://img.shields.io/badge/go%20to%20PROJ-08-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_08)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Building machine learning algorithm for a metalworking enterprise"  

### Task  
Building a model predicting recovery rate for gold from gold ore

### Description
A gold mining company needs a solution to perfect its efficiency.
A model forecasting gold recovery rate is created using ore extraction and refinement parametres data.
The model is developed to help optimize production by assessing ore quality to avoid financial losses on ineffective operations.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=Seaborn&color=ff5252)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_09](https://img.shields.io/badge/go%20to%20PROJ-09-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_09)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Insurance Company: Development of an algorithm to protect customer data"  

### Task  
Data transformation method for the insurance company clients' personal information protection

### Description
An insurance company needs to protect its customers information using data transformation methods. This helps to prevent sensitive data from being decrypted. 
This project required data preprocessing. The linear regression model algorythm was validated by multiplying the results on an invertible matrix. Conversely, multiplication on an inverse matrix of the invertible matrix proved the model works correctly. R2 score for linear regression model was measured on indentical data: initial data first, then data multiplied on invertible matrix (size of the features count). Metrics matched perfectly which means the algorythm works.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_10](https://img.shields.io/badge/go%20to%20PROJ-10-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_10)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Car price prediction model"  

### Task  
Train the model to determine the market value of the car based on its parametres

### Description
A company selling used cars is developing an app. One of the features attracting new clients is functionality of estimating a car's worth based on its features and characteristics. A car cost forcasting model was created using historical data.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_11](https://img.shields.io/badge/go%20to%20PROJ-11-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_11)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Ride-hailing Company: Predicting the number of taxi orders"  

### Task  
Train a model to predict taxi ride demand for the next hour

### Description
A taxi hailing services company has historical data of rides ordered from the airport area. Model was built to forecast taxi demand for the next hour. This is to help balance amount of cars around the airport and have the right amount of drivers in the area for peak and off peak hours.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_12](https://img.shields.io/badge/go%20to%20PROJ-12-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_12)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "Natural Language Processing: Classifying comments"  

### Task  
Speeding up the moderation of product desctiption commentaries on an ecommerce website by automating their tone assessment. Training the model to classify comments as positive or negative

### Description
An online retail store launched a new feature: product description edit can now suggested by website users similar to wiki communities. Other users comment on proposed changes. A model developed to detect 'toxic' commentaries to be moderated.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![NLP](https://img.shields.io/static/v1?label=tool&message=NLP&color=218c74)](#)
[![nltk](https://img.shields.io/static/v1?label=tool&message=nltk&color=474787)](#)
[![tf-idf](https://img.shields.io/static/v1?label=tool&message=tf-idf&color=227093)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_13](https://img.shields.io/badge/go%20to%20PROJ-13-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_13)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)
## "A plant electricity consumption optimization"  

### Task  
Metallurgical plant production costs optimization by reducing energy consumption during steel processing

### Description
To adjust production costs the smeltery management needs to reduce electricity consumption during the steel processing.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***


All work in this repository are my project created as study cases during the online bootcamp  **Data Science** by **Yandex.Practicum**.
All code was validated by a code reviewer whose commentaries were deleted to keep the projects neat.  

Each case study was done in the `Jupyter Notebook` environment and is a `.ipynb` notebook. Every project has a detailed tasks description, skills and tools used.