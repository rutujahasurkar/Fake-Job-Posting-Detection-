# Project Title : Fake vs Real Job Posting Analysis

  With ease of access to technologies, the number of jobs and number of job applicants have been significantly increasing in recent years. With this comes fraudulent techniques which misuses the dire situation of applicants by stealing their data for their malicious uses. We are aiming at developing a model to find fake job postings from groups of job postings. The data is provided by The University of the Aegean. This can help a number of job seekers to avoid the fake job postings which can actually expose their personal details in unsafe hands.

By
Rutuja Hasurkar (014547793)
Sudarshan Aithal (013638703)
Shivan Desai (010279646)
Jasmine Akkal (013773825)


Model Performance Comparision, 

Folder - Dataset  :  Dataset of Fake vs real job postings from The University of the Aegean 

Folder - Report  : Milestone reports

Folder - XGB-RandomForest  :  Performance comparison of XGBoost classifier and Random forest 
                                                                         on factorized, non-descriptive, non-null data

Folder - XGB-TFIDF  : Performance comparison of XGBoost classifier using TF-IDF pipelining and Gensim and XG-Boost Classifier on TF-IDF
                      Vectorized data using NLTK  
                                             on Descriptive, non-null data
                                             
DataPreprocessing_EDA.ipynb  :  Preprocessing of fake_real_data.csv, Analysis of columns, types of data present in columns, diversity of data, finding patterns in data using exploratory data analysis, identifying null values, removal of null values, Pearson's correlation on non null data, Pearson's Chi Square test on non null data

Random_Forest_Classifier.ipynb : Implementation of the Random forest classifier model on the non descriptive attributes to classify the postings with testing accuracy of 96%.

XGBoostV2.ipynb  : Comparison of performance of XGBoost classification on non descriptive, non - null data with atmost 10%, 20% or 30% null valued attributes

XGBoostV3.ipynb  :  Comparison of performance of XGBoost classification on descriptive, non - null data with TF-IDF pipeline and Gensim NLP package on company_profile and job description attributes

Fake_job_posting_Jasmine_NLP_v2.ipynb : Data-preprocessing, Data-visualisation, Data-cleaning, Counter Vectorizer Model classification. 

Fake_job_posting_Jasmine_NLP_v3.ipynb : Data-preprocessing, Data-visualisation, Data-cleaning, Counter Vectorizer and BERT Model classification with efficinecy of 71.8% for BERT and 86.0% for count vectorizer model. 
