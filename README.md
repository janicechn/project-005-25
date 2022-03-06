# project-005-25

# User’s Knowledge Level Based on Exam Performances

#### DSCI100 project-005-25 Group Project Proposal
##### *By Janice Chan, Sarah Hong, Samreen Kaur, and Sota Uehara*

Exams are often used to evaluate one's understanding of content. With knowledge levels "very low," "low," "middle," and "high" classified by Hamdi et al. (2009), could one's exam performance truly reflect their knowledge level? People may have varying exam performances when being tested on goal objectives and related materials.

Thus, our project question is: based on user exam performance for related objects with goal objects (LPR) and user exam performance for goal object (PEG), what is the user’s expected knowledge level? 

We will be using the user knowledge modelling dataset folder to access the provided training and testing data frames of students (users) studying electrical DC machines, containing LPR, PEG, and user knowledge level (UNS) classified by Hamdi et al. (2009).

From our dataset, we will use LPR and PEG as exploratory variables of interest and have UNS as the response variable. Other variables are not of interest to see an effect on UNS. We will conduct our data analysis by classification with the K-nearest neighbors algorithm. Then we can predict UNS for new exam performances based on the K most similar exam performances in the given training set. The process includes finding the closest K points of exam performance visualized data by distance, creating the KNN model, data preprocessing, compiling a workflow to fit, and predicting the classification. We will evaluate the accuracy and tune the classifier to pick the best K value, which involves cross-validation.
