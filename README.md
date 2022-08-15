# Neural_Network_Charity_Analysis
Neural Networks, Deep Machine Learning Models, and tensorflow.
## Overview of the analysis: 
In this challenge we are asked to help Bek in the foundation Alphabet soup. They want to predict where they shoud make there investments. With the use of neural networks and deep machine learning models we can apply this to create visuals to determine which would be better.
## Results:
### Data Preprocessing

#### What variable(s) are considered the target(s) for your model?
The target variable would be in the IS_SUCCESSFUL column.

#### What variable(s) are considered to be the features for your model?
The variables that are considered to be the features are application type, affiliation, classification,use_case, organization, status, income_amt, special_considerations, aand sk_am. 

#### What variable(s) are neither targets nor features, and should be removed from the input data?
The variables that should be removed is ein and name.

### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the optimized model for the different layers I did 110,80,40 and 20. So four different layers. I choice these so that there could be a different variety of each layer.
<img width="1440" alt="Screen Shot 2022-08-15 at 10 54 05 AM" src="https://user-images.githubusercontent.com/99035696/184659191-0c95760b-6e0e-41f1-b325-b87fa59f42f8.png">

#### Were you able to achieve the target model performance?
We were tasked to do 75% but my model only preformed at 72% for deliverable 1+2 and 3 for 47%. So no the model did not achieve the goal.
<img width="856" alt="Screen Shot 2022-08-15 at 11 08 48 AM" src="https://user-images.githubusercontent.com/99035696/184662159-d0b346af-0653-4044-8f31-d936c2a23ff1.png">
<img width="856" alt="Screen Shot 2022-08-15 at 11 07 13 AM" src="https://user-images.githubusercontent.com/99035696/184662098-aa787bbb-c70e-4204-a6ca-c79aea46b0d1.png">

#### What steps did you take to try and increase model performance?
We were asked to optimize the data so I reviewed some columns, dropped some columns, and changed the number of neurons.

## Summary: 
The relu and sigmoid activations yielded a 72% accuracy, from the 1 and 2 deliverable.The next model I would reccommend would be to try the random forest classifier this is because it is less influenced by outliers.
