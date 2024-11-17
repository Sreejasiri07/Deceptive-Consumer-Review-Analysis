# Deceptive Consumer Review Analysis
Minor Project describing the path to creating classifiers which aids in identifying the fake reviews from the real one and also identify the source of the review as either human generated or AI generated using fake reviws dataset and Amazon Dataset.
## Abstract
Online consumer review plays an important role in purchasing online products. Availability of various versions and models of a single product makes it difficult to choose. So, most of the customers rely on reviews to purchase the products. These deceptive reviews are being created majorly in two ways both human-crafted and AI-generated. But in today’s world most of the reviews are being deceptive either to defame the product or to make fake promotions. To solve this issue many organizations started to rely on manual labor which is a time consuming, biased and costly process. To overcome these problems, there is a need for an automatic model to detect deceptive consumer reviews. While creating this model we plan to use various Machine Learning algorithms like SVM, Multinomial Naive Bayes, Logistic Regression, Decision Trees, Random Forests and KNN to ensure the integrity and accuracy of the system. Among the above algorithms used for our models we got to observe that logistic regression seems to produce the best results for fake or real review prediction with highest accuracy (85%) and for the AI generated or human generated model we have got to see that the Support Vector Machine (SVM) produces results with highest accuracy (88%). This further led us to combine the Logistic Regression model for real or fake review detection and SVM for AI/human generated review detection which helps to find whether a review is fake or real, if at all it is fake then whether it is human generated, or AI generated. 
## Info 
IDE: Google Colab

Language: Python

Techniques utilized: Machine Learning and NLP
### Models Utilized
To predict the input review as fake or not the following models have been considered
1. Multinominal Naive Bayes
2. Support Vector Machine
3. Logistic Regression
   
To identify the source of the review whether it is Ai generated or Human generated the following models have been considered
1. Logistic Regression
2. K Nearest Neighbors
3. Decision Tree Classifier
4. Random Forests Classifier
5. Support Vector Machine
6. Multinomial Naive Bayes
