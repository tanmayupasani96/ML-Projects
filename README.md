
**Capstone 2**

The capstone 2 project involves classification of stellar bodies into various categories like Star, Galaxy or a Quasar. The project involved data cleaning, filling up missing values with the help of median(if the data was numerical) and mode(if categorical). 
The next step was to find correlation between the categories and reducing it so as to have stable data. 
The next step was to apply encoding to categorical values, one hot encoding was chosen if the data was hierarchical and label encoding was preferred if there was no hierarchy in the data.
The final step was to apply ML model Random-Forest and to judge the performance with evaluation metrics. The testing accuracy stood at **96%** thus proving that the model was well trained. The difference between Traininng and Testing Accuracy was less and thus proving that there was no overfitting.

**Brain Stroke**
This project involves predicting whether a particular patient will suffer from brain stroke given all the different factors. The project follolwed a similar outline where the missing values were treated with median if it was a numerical value and with mode if it was categorical.
The next step was to drop the columns with high correlation.
Encoding was applied to convert the entire data into numerical values for training the model.
Multiple ML models were used and had a varying accuracy. 
