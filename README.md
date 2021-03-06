# Machine-Learning-Python
Basics of machine learning using an approachable, and well-known, programming language. Concepts like Supervised vs Unsupervised Learning, look into how Statistical Modeling relates to Machine Learning, and do a comparison of each. Real-life examples of Machine learning in Python 

## 1. Regression
- **Simple Linear Regression**:  Used 'ENGINESIZE' to predict Co2 Emission

- **Multiple Linear Regression**:  Used 'ENGINESIZE', 'CYLINDERS', 'FUELCONSUMPTION_HWY' & 'FUELCONSUMPTION_CITY' to predict Co2 Emission

- **Non-Linear Regression**:  Used 'China GDP from 1960 to 2014'

## 2. Classification
- **K-Nearest Neighbors**: Imagine a telecommunications provider has segmented its customer base by service usage patterns, categorizing the customers into four groups. It is a classification problem. That is, given the dataset, with predefined labels, we need to build a model to be used to predict class of a new or unknown case. The example focuses on using demographic data, such as region, age, and marital, to predict usage patterns. The target field, called custcat, has four possible values that correspond to the four customer groups, as follows: 1- Basic Service 2- E-Service 3- Plus Service 4- Total Service Our objective is to build a classifier, to predict the class of unknown cases. We will use a specific type of classification called K nearest neighbour.

- **Decision Trees**: Imagine that you are a medical researcher compiling data for a study. You have collected data about a set of patients, all of whom suffered from the same illness. During their course of treatment, each patient responded to one of 5 medications, Drug A, Drug B, Drug c, Drug x and y. The feature sets of this dataset are Age, Sex, Blood Pressure, and Cholesterol of patients, and the target is the drug that each patient responded to. It is a sample of binary classifier, and you can use the training part of the dataset to build a decision tree, and then use it to predict the class of a unknown patient, or to prescribe it to a new patient.

- **Support Vector Machines**:  The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics. The ID field contains the patient identifiers. The characteristics of the cell samples from each patient are contained in fields Clump to Mit. The values are graded from 1 to 10, with 1 being the closest to benign. The Class field contains the diagnosis, as confirmed by separate medical procedures, as to whether the samples are benign (value = 2) or malignant (value = 4).

- **Logistic Regression**: We will use a telecommunications dataset for predicting customer churn. This is a historical customer dataset where each row represents one customer.This data set provides information to help you predict what behavior will help you to retain customers. You can analyze all relevant customer data and develop focused customer retention programs. The dataset includes information about: Customers who left within the last month – the column is called Churn. Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies. Customer account information – how long they had been a customer, contract, payment method, paperless billing, monthly charges, and total charges. Demographic info about customers – gender, age range, and if they have partners and dependents


## 3. Clustering
- **K-Means**: Imagine that you have a customer dataset, and you need to apply customer segmentation on this historical data. Customer segmentation is the practice of partitioning a customer base into groups of individuals that have similar characteristics. It is a significant strategy as a business can target these specific groups of customers and effectively allocate marketing resources. For example, one group might contain customers who are high-profit and low-risk, that is, more likely to purchase products, or subscribe for a service. A business task is to retaining those customers. Another group might include customers from non-profit organizations. And so on.

- **Agglomerative Hierarchical Clustering**: Imagine that an automobile manufacturer has developed prototypes for a new vehicle. Before introducing the new model into its range, the manufacturer wants to determine which existing vehicles on the market are most like the prototypes--that is, how vehicles can be grouped, which group is the most similar with the model, and therefore which models they will be competing against. Our objective here, is to use clustering methods, to find the most distinctive clusters of vehicles. It will summarize the existing vehicles and help manufacturers to make decision about the supply of new models.

- **Density-Based Clustering**: DBSCAN is specially very good for tasks like class identification on a spatial context. The wonderful attribute of DBSCAN algorithm is that it can find out any arbitrary shape cluster without getting affected by noise. For example, this following example cluster the location of weather stations in Canada. DBSCAN can be used here, for instance, to find the group of stations which show the same weather condition. As you can see, it not only finds different arbitrary shaped clusters, can find the denser part of data-centered samples by ignoring less-dense areas or noises. More Information on data: https://ibb.co/YNKVsqd


## 4. Recommender System
- **Content-Based Filtering**: Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user. These systems have become ubiquitous, and can be commonly seen in online stores, movies databases and job finders. I have explored Content-based recommendation systems and implemented a simple version of one using Python and the Pandas library.

- **Collabrative Filtering**: This technique uses other users to recommend items to the input user. It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. There are several methods of finding similar users (Even some making use of Machine Learning), and the one we will be using here is going to be based on the Pearson Correlation Function.
