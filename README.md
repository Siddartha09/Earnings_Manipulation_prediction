# Earnings_Manipulation_prediction

This project is based on the case study "PREDICTING EARNING MANIPULATION BY INDIAN FIRMS USING MACHINE LEARNING ALGORITHMS" written by U Dinesh Kumar,  Tousif Ahmed Inayath and Suresh Ganeshan for IIM Bangalore.

**Summary of the case study:**   
MCA Technology Solutions Private Limited was founded in Bangalore in 2015 with the goal of fusing business with technology and analytics. Customer intelligence, forecasting, optimization, risk assessment, web analytics, text mining, and cloud solutions are the areas where MCA Technology Solutions assisted its clients. MCA technology solutions' risk assessment sector focused on issues including credit scoring and fraud detection. A commercial bank asked Sachin Kumar, Director at MCA Technology Solutions to help them identify earnings manipulators among the bank's customers. The bank provided business loans to small and medium enterprises and the value of loan ranged from INR 10 million to 500 million. The bank had a suspicion that some of its clients were engaging in earnings manipulation to improve their chances of getting a loan. Saurabh Rishi, the chief data scientist at MCA Technologies was assigned the task of developing a use case for predicting earnings manipulations. He was aware of models for anticipating earnings manipulations, such as Benford's law and the Beneish model, but he was unsure of how well they performed, particularly in the context of India. Using the data downloaded from the Prowess database maintained by the Centre of Monitoring Indian Economy(CMIE), Saurabh made the decision to create his own model for predicting earnings manipulations. Daniel obtained data on income manipulators from the Lexis Nexis database and the Securities Exchange Board of India (SEBI). To create the model, data on more than 1200 companies was gathered. In comparison to other traditional models like the Beneish model, which is used to anticipate earnings manipulation, MCA Technology believed that machine learning algorithms may provide greater accuracy.

** *Our project tries to answer the following questions and suggest a model that predicts which companies manipulate there earnings out of 1239 companies in the dataset.* **

(1) Do you think the Beneish model developed in 1999 will still be relevant to Indian data?

(2) The number of manipulators is usually much less than non-manipulators (in the accompanying spreadsheet, the percentage of manipulators is less than 4% in the complete data). What kind of modeling problems can one expect when cases in one class are much lower than the other class in a binary classification problem? How can one handle these problems?

(3) Use a sample data (220 cases including 39 manipulators) and develop a logistic regression model that can be used by MCA Technologies Private Limited for predicting probability of earnings manipulation.

(4) What measure do you use to evaluate the performance of your logistic regression model? How does your model perform on the training and test datasets?

(5) What is the best probability threshold that can be used to assign instances to different classes? Write two functions that receive the output of the ROC performance function and return the best probability thresholds using the distance to (0,1) and Youden’s approach respectively.

(6) Based on the models developed in questions 4 and 5, suggest a M-score (Manipulator score) that can be used by regulators to identify potential manipulators.

(7) Develop a decision tree model. What insights do you obtain from the tree model?

(8) Develop a logistic regression model using the complete data set (1200 non-manipulators and 39 manipulators), compare the results with the previous logistic  regression model and comment on differences.

