# Neural Network Charity Analysis #
## Overview of Analysis ##
Alphabet Soup is a nonprofit organization. They have donated over $10 billion in 20 years to organizations. The csv file, charity_data, contains information on 34,299 organizations that have received funding from Alphabet Soup. It includes identification columns, application type, the affiliated sector of industry, the government organization classification, what they are using the funding for, the organization type, the active status, the approximate income amount of the organization, whether special considerations were added to the application, the funding amount requested, and whether the money was used effectively for each of these instances. 

### Purpose of Analysis ###
The purpose of this analysis is to create a neural network to predict whether a company will use funding successfully if Alphabet Soup donates to their cause. This analysis will determine if a neural network can aid Alphabet Soup in their funding decisions.

## Results ##
- The target is the variable 'IS_SUCCESSFUL' where it was determined whether the funding was used effectively.
- The features of the model include: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and
ASK_AMT.
- EIN and NAME are identification columns and were removed from the input data.
- To begin with, there were two hidden layers, an input layer, and an output layer. The activation functions that were used in the beginning were relu and sigmoid and adjusted from there. Those activation functions are more basic before attempting increased measures. 
- The target of an accuracy of 75% could not be reached.
- The following attempts were made to try to achieve 75% accuracy: the number of hidden layers were changed from 2 to 3, different variables were excluded, epochs were both increased (up to 100) and decreased, income amounts were binned in three different ways, different activation functions were used, and accuracy of the model remained around 50% with each attempt.
<img width="500" alt="acc" src="https://user-images.githubusercontent.com/116980760/227628106-83d09212-c89a-49e9-b5d5-0b2bbcea6e0b.PNG">


## Summary ##
The deep learning model was not successful in predicting loan risk for Alphabet Soup. A different model would be a better fit. Logistic regression might be a good alternative as the company is seeking a binary solution.
