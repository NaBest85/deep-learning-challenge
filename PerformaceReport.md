
# Analysis Overview

The purpose of this analysis was to create a model to evaluate the data created for Alphabet Soup Charity.  This model was created to determine or predict if applicants would be funded, this model would help determine the probability of the applicants using certain data.



## Results

## Data Preprocessing

*Which variables serve as the target(s) for yout model? The variables corresponding to the IS_SUCCESFUL column,

*Which variables function as the features for your model?  All columns provided in the dataset after removing "EIN and "NAME".

*What variable(s) should be removed from the input data because they are neither targets nor features?  Variables that were removed were columns "EIN", "NAME", and at the end "IS_SUCCESFUL.  However for the final model "NAME" was kept and obtained a higher percentage rating.

## Compiling, Training, and Evaluating the Model

*How many neurons, layers, and activation functions did you select for your neural network model, and why?  Initially I used 70 for hidden nodes layer 1 and 40 for hidden nodes layer 2, these numbers were simply used to gather information to reshape the model to be more optimal.

*Were you able to achieve the target model performance?  On the fourth model I was able to reach the target model performance which was above 75%, the model rendered a 79% Accuracy.

*What steps did you take in your attempts to increase model performance? By leaving the column "Name" and adding a third layer along with changing the hidden nodes to 
9 (1), 18(2), and 20(3).


## Summary

    By only removing 2 columns total from the database and setting a third hidden nodes layer along with keeping the layers paramters closer together, especially layers 2 and 3 the model was able to render a higher percentage rate.
