# IBM-Project-49729-1660837038
Web Phishing Detection
# PROJECT OBJECTVE
We'll be able to understand the problem to classify if it is a regression or a classification kind of problem. We will be able to know how to pre-process/clean the data using different data pre-processing techniques. Applying different algorithms according to the dataset We will be able to know how to find the accuracy of the model. We will be able to build web applications using the Flask framework.

# INTRODUCTION
There are a number of users who purchase products online and make payments through e-banking. There are e-banking websites that ask users to provide sensitive data such as username, password & credit card details, etc., often for malicious reasons. This type of e-banking website is known as a phishing website. Web service is one of the key communications software services for the Internet. Web phishing is one of many security threats to web services on the Internet

# DATA COLLECTION & ANALYSIS
The given data contains both phishing and benign URLs of websites with various website content-based features. The above mentioned dataset is uploaded to the 'final deliverables/data' folder of this repository. From data distribution graph and correlation matrix, we can conclude that the 16 of the given features do not have much impact on the result. So they are removed from further processing. The final set of features that are used to build the model are shown in the figure below.






# MODELS &TRAINING
Before stating the ML model training, the data is split into 80-20 i.e., 8844 training samples & 2211 testing samples. From the dataset, it is clear that this is a supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression.

This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are:
        *Decision Tree 
        *Random Forest 
        *XGBoost
        *Support Vector Machines
        All these models are trained on the dataset and evaluation of the model is done with the test dataset. The elaborate details of the models & its training are              mentioned in
               