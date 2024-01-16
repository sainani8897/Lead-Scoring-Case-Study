# Lead Scoring Model


### Problem Statement:

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

<img src = 'https://cdn.upgrad.com/UpGrad/temp/189f213d-fade-4fe4-b506-865f1840a25a/XNote_201901081613670.jpg'>

There are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating, etc. ) in order to get a higher lead conversion.

X Education wants to select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score h have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.


### Solution:

For this case study we're going to use several classification model to predict whether the lead is going to quantify as a hot lead. The steps involved for this case study are mentioned below:


1) Importing Data
2) Understanding & Cleaning the Data
3) EDA (Exploatory Data Analysis)
4) Univariate Analysis and Bivariate Analysis
5) Data Preparation
6) Feature Selection Using RFE
7) Model Building
8) Model Performance Benchmarking
9) Model Performance Evaluation
10) Cross Validation 
11) Model Diagnosis Using Probability Calibration, ROC AUC Curve, Precision-Recall Curve

### Notebooks:
1) <a href = "https://github.com/mukulsinghal001/lead-scoring-model/blob/main/Lead%20Scoring%20Data%20-%20EDA%20%2B%20Feature%20Engineering%20%2B%20Outlier%20Analysis.ipynb">Exploratory Data Analysis + Feature Engineering + Outlier Analysis Notebook
2) <a href = "https://github.com/mukulsinghal001/lead-scoring-model/blob/main/Lead%20Scoring%20Classification%20Model%20Diagnosis%20with%20%20Probability%20Calibration%20%26%20ROC_AUC%20%2B%20PR%20Plot.ipynb">Lead Scoring Model Diagnosis Notebook
3) <a href = "https://github.com/mukulsinghal001/lead-scoring-model/blob/main/Lead%20Scoring%20Classification%20Model%20with%2092%25%20Accuracy%20using%20RandomForest.ipynb"> Final Lead Scoring Model Notebook
