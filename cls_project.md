# Introduction to Machine Learning
## Data Classification Project Information
* You can get up to **30** points

* Project are done in groups of 3 students
  * 🎯 **Put your name into a group in which you want to be** in this [Google Sheet](https://docs.google.com/spreadsheets/d/1MBWVYLONwAmUPO5GywCn9Fh7V_TZXgUlVL4jz-7E_Sk/edit?usp=sharing)

* Every project must include description of the dataset features and a brief exploration analysis so you get to know the data you are working with

* Describe your preprocessing pipeline **(5 points)**
  * **📒 Describe what operations you are performing for each of the features**
      * e.g. No operation needed, dropping the feature, Min-Max scaling, One-hot encoding, Categorization (numeric -> categorical) etc.
      * You can even try to experiment with many different preprocession operations and you will see what works the best - this is totally up to you!

* 🔎 What model performance metrics have you decided to use? **(5 points)**
  * e.g. Accuracy, Precision, Recall, F1-score etc.
  * **📒 State which one of the scores is the most important from your point of view given the class balance, task, ... in a Markdown cell!**

* 🎯 Try at least **3** different classification algorithms **(15 points)**
  * 🌳 Decision tree is a mandatory one
  * Other algorithm choices depends solely on you - you can find many different algorithms in the [scikit-learn docs](https://scikit-learn.org/stable/supervised_learning.html)
    * We can recommend the Multi-layer Perceptron (MLP), Random Forest, AdaBoost, k-Nearest Neighbors or Naive Bayes
    * **Check blog posts, book chapters or Youtube videos about the algoritmhs you have chosen so you have a basic knowledge about its key concepts**
      * 💡 You know some of them already from the lectures 🙂

## General Information
**✅ Mandatory part of every project is a summary at the end in which you summarize the most interesting insight obtained**. **(5 points)**
  
Upload a **📝 Jupyter Notebook with descriptions included** or a PDF report + source codes in a *zip* archive.
  * 💡 Please write down your names to the begining of the Jupyter Notebook/Python source codes so there is no information noise
  
💡 Estimated time for the project is 5-10h, this value heavily depends on your skill, but you can use it as a guidance for a project size.

> #### **🎯 Deadline is 08. 12. 2024 ❄️**

**Upload the project to:**

* [Dropbox](https://www.dropbox.com/request/zSEuiw0zhJTD6ZB6rTwl)
  * **💡 Dropbox will ask you for your name - use your group name (e.g. Group 1) please 👍**

# Datasets
## 1 - Credit Card Customers
https://www.kaggle.com/sakshigoyal7/credit-card-customers

> [Dataset](https://homel.vsb.cz/~svo0175/zsu_01_cls_customers.zip)

>  DROP THE LAST 2 COLUMNS - *NAIVE BAYES CLAS...*. 
 
> **Target variable: Attrition_Flag**

You have recently been brought on as a data analyst for BankGuard, a financial services company that has been facing a troubling issue: an increasing number of customers are leaving their credit card services. The bank’s management is concerned, as customer churn has a direct impact on revenue and customer loyalty. The Customer Retention Manager has reached out to you with an urgent request: Help us predict which customers are likely to churn so we can take proactive steps to retain them.

They believe that if they can identify customers at risk of leaving, they can offer personalized incentives, improve services, or address customer concerns before it’s too late.

**Data description:**

 * Client - number - Unique identifier for the customer holding the account

 * Attrition_FlagInternal - event (customer activity) variable - if the account is closed then 1 else 0

 * Customer_AgeDemographic - variable - Customer's Age in Years

 * GenderDemographic - variable - M=Male, F=Female

 * Dependent_count - Demographic variable - Number of dependents

 * Education_Level - Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)

 * Marital_Status - Demographic variable - Married, Single, Divorced, Unknown

 * Income_Category - Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown)

 * Card_Category - Product Variable - Type of Card (Blue, Silver, Gold, Platinum)

 * Months_on_book - Period of relationship with bank

 * Total_Relationship_Count - Total no. of products held by the customer

 * Months_Inactive_12_mon - No. of months inactive in the last 12 months

 * Contacts_Count_12_mon - No. of Contacts in the last 12 months

 * Credit_Limit - Credit Limit on the Credit Card

 * Total_Revolving_Bal - Total Revolving Balance on the Credit Card

 * Avg_Open_To_Buy - Open to Buy Credit Line (Average of last 12 months)

 * Total_Amt_Chng_Q4_Q1 - Change in Transaction Amount (Q4 over Q1)

 * Total_Trans_Amt - Total Transaction Amount (Last 12 months)

 * Total_Trans_Ct - Total Transaction Count (Last 12 months)

 * Total_Ct_Chng_Q4_Q1 - Change in Transaction Count (Q4 over Q1)

 * Avg_Utilization_Ratio - Average Card Utilization Ratio

 * Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1 - Naive Bayes

 * Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2 - Naive Bayes

## 2 - Adult
https://archive.ics.uci.edu/dataset/2/adult

> [Dataset](https://homel.vsb.cz/~svo0175/zsu_02_cls_adult.zip)

> Predict whether income exceeds $50K/yr based on census data.

> The *.data* files are plain CSV/text files

> **Target variable: class; >50K, <=50K.**

You’ve been hired as a data analyst for the National Economic Policy Institute, a research organization focused on understanding income inequality and economic trends. Recently, the institute has been analyzing census data to gain deeper insights into factors that influence an individual’s income level. They are particularly interested in identifying the characteristics that predict whether a person’s annual income exceeds $50,000, which is considered a key threshold for middle-class status in many regions.

The institute believes that by understanding the social, demographic, and economic factors behind income differences, they can provide recommendations to policymakers on how to address inequality and create more opportunities for individuals to move into higher income brackets.

**Data description:**

 * age: continuous.

 * workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

 * fnlwgt: continuous.

 * education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

 * education-num: continuous.

 * marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

 * occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

 * relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

 * race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

 * sex: Female, Male.

 * capital-gain: continuous.

 * capital-loss: continuous.

 * hours-per-week: continuous.

 * native-country: United-States, Cambodia, England, ...

## 3 - Heart Failure Prediction Dataset
https://www.kaggle.com/fedesoriano/heart-failure-prediction

> [Dataset](https://homel.vsb.cz/~svo0175/zsu_03_cls_heart.zip)

> **Target variable:  HeartDisease**

You are part of a team of data scientists working at HealthGuard Analytics, a company dedicated to using data to drive healthcare solutions. Recently, the global health community has been alarmed by the staggering rates of cardiovascular diseases (CVDs), which are the leading cause of death worldwide. With 17.9 million deaths each year attributed to heart attacks and strokes, the stakes are high.

Your company has partnered with medical research institutions to help tackle this problem. They have provided you with a dataset containing information on patients’ health and risk factors, and your task is to develop a machine learning model that can predict the likelihood of heart disease in individuals.

**Data description:**

 * Age: age of the patient (years)

 * Sex: sex of the patient (M: Male, F: Female)

 * ChestPainType: chest pain type (TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic)

 * RestingBP: resting blood pressure (mm Hg)

 * Cholesterol: serum cholesterol (mm/dl)

 * FastingBS: fasting blood sugar (1: if FastingBS > 120 mg/dl, 0: otherwise)

 * RestingECG: resting electrocardiogram results (Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria)

 * MaxHR: maximum heart rate achieved (Numeric value between 60 and 202)

 * ExerciseAngina: exercise-induced angina (Y: Yes, N: No)

 * Oldpeak: oldpeak = ST (Numeric value measured in depression)

 * ST_Slope: the slope of the peak exercise ST segment (Up: upsloping, Flat: flat, Down: downsloping)

 * HeartDisease: output class (1: heart disease, 0: Normal)

## 4 - KDD Cup 99
https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

> [Dataset](https://homel.vsb.cz/~svo0175/zsu_04_cls_kdd99.zip)

> **Target variable: label**

You are a data scientist working with CyberDefend Analytics, a company focused on cybersecurity solutions for government and military networks. With increasing cyberattacks on critical infrastructures, the stakes for network security have never been higher. Your team has been tasked with improving the detection of malicious network activity, as traditional defenses are no longer sufficient to keep up with the rapidly evolving threat landscape.

Recently, you’ve been given access to a dataset from the Third International Knowledge Discovery and Data Mining Tools Competition (KDD-99). This dataset was created to simulate a military network environment, where different types of network connections were audited. Your objective is to use this data to build a network intrusion detection system capable of distinguishing between malicious attacks and normal traffic.

* The features describe TCP/UDP network connections, 
* If you have a basic networking knowledge the feature names are self-describing
* Features are also similar to the *UNSW_NB15* dataset 😉

## 5 - UNSW_NB15
https://www.kaggle.com/mrwellsdavid/unsw-nb15?select=UNSW_NB15_training-set.csv

> [Dataset](https://homel.vsb.cz/~svo0175/zsu_05_cls_unsw.zip)

> Use *UNSW_NB15_training-set.csv* and *UNSW_NB15_testing-set.csv* files.
 
> **Target variable:  label or attack_cat**.
  > * Choose either one and drop the other! Otherwise you would have an information leak!

You have joined the cybersecurity research team at CyberSecure Labs, a cutting-edge organization focused on protecting modern networks from evolving cyber threats. With the rise of sophisticated attacks on everything from government systems to private enterprises, there is an urgent need for better tools to detect and prevent malicious activities.

Recently, your team has been provided access to the UNSW-NB15 dataset, a comprehensive network dataset that combines real-world modern traffic with simulated cyberattacks. The dataset was created using the IXIA PerfectStorm tool at the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS), and it includes nine different types of attack behaviors, captured using the Tcpdump tool. The dataset has 49 features generated by Argus and Bro-IDS tools, with a variety of attacks such as Fuzzers, Backdoors, Denial-of-Service (DoS), Exploits, and Worms.

Your task is to build a model capable of detecting these attacks, helping to develop a robust intrusion detection system (IDS) for identifying both normal and malicious network activities.

* The features describe TCP/UDP network connections created by the IXIA PerfectStorm tool in the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS)
* If you have a basic networking knowledge the feature names are self-describing