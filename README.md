# Neural Network Model
I utilized ChatGPT, private tutors, and my instructor to help with this assignment. 

## Analysis
### Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. In the provided CSV it contained more than 34,000 organizations that received funding from Alphabet Soup over the years. 

### Results
**Data Preprocessing**
*What variable(s) are the target(s) for your model?*
- The 'IS_SUCCESSFUL' column from application_df is the target variable, this is what we are trying to predict. This shows if the money was used effectively.
*What variable(s) are the features for your model?*
- The feature variables we used are:
  1. AFFILIATION—Affiliated sector of industry
  2. CLASSIFICATION—Government organization classification
  3. USE_CASE—Use case for funding
  4. ORGANIZATION—Organization type
  5. STATUS—Active status
  6. INCOME_AMT—Income classification
  7. SPECIAL_CONSIDERATIONS—Special considerations for application
  8. ASK_AMT—Funding amount requested

*What variable(s) should be removed from the input data because they are neither targets nor features?*
- Identification columns: The "EIN" and "NAME" columns are identification columns that typically provide unique identifiers for each organization. These columns usually have no direct impact on the target variable and can be dropped without affecting the model's accuracy.

**Compiling, Training, and Evaluating the Model**

*How many neurons, layers, and activation functions did you select for your neural network model, and why?*

*Were you able to achieve the target model performance?*
I was not able to achieve the target model performance of 75%.

*What steps did you take in your attempts to increase model performance?*
I created a defined function 
![image](https://github.com/user-attachments/assets/8b268b4a-63cc-4959-a5b1-ee397c8ca358)

That allowed for the code to be auto-optimization to get the best model and hyperparameters to obtain accuracy higher even though never got to over 75%. The activation function used throughout this model is sigmoid.

### Summary
Even though after changing layers, neurons, and activation function to achieve the target model perfomance of 75%.
