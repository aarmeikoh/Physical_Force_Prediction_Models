# Physical Force Prediction Models
 
Although the New York Police Department’s (NYPD) controversial stop and frisk has been found unconstitutional, stops and frisks occur all the time. Many daily encounters between police officers end in a stop and frisk. Even when an encounter is not classified as a stop and a frisk does not occur there are hundreds of interactions between police officers and suspects every day. Officers can be trained in techniques in how to conduct themselves during these interactions to ensure that they are resolved in the safest outcome possible.
## Problem Statement
 Many encounters involve the use of force by a police officer. Avoiding the use of excessive force during an encounter can benefit the safety of all involved. If an officer can be made aware of the level of risk of an encounter before entering a confrontation, steps can be implemented to proceed with the necessary tools to ensure a safe resolution for all involved.  This includes providing the officer with a profile of individuals likely to act in ways that would typically require the use of force as well as situations that are likely to result in the officer using force.
 ## Models
 The best performing model found in this study is a decision tree-based ensemble, using gradient boosting. The model improves accuracy and accurately predicts high levels of cases that include the use of force. The model provides the ability of reaching 80% of cases that involve the use force in just 40% of stops. If costly procedures are needed to reduce the use of force, it can be limited to less than half of stops and still affect 80% of cases that involve use of force. 
 Other models attempted include Naive Bayes and Logistic Regression.
## Data
The data for this project has been retrieved from [Publications, Reports - NYPD (nyc.gov)](https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page)
