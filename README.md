# Terry-Traffic-Stops-Project
## Overview
This project is aimed at finding out if unreasonable search and seizure of an individual by a police officer is justified. This will be done by finding out if each Terry Traffic Stop (the unreasonable search or seizure) recorded in Seattle led to an arrest. This will be done by looking at the individual's features provided in the data and how they contribute to their arrest.

## Business and Data Understanding
Stakeholder Requirement and Problem
Our stakeholder is the Supreme Court of Ohio. This is to help them understand if the Terry V. Ohio case was ruled accordingly and to ensure that such cases presented to them do not violed the Fourth Amendment that states;

The right of the people to be secure in their persons, houses, papers, and effects, against unreasonable searches and seizures, shall not be violated, and no warrants shall issue, but upon probable cause, supported by oath or affirmation, and particularly describing the place to be searched, and the persons or things to be seized.

The inspiration to conduct this project was stemed from the event that caused Terry and his three friends to face 3 years imprisonment due to unreasonable searches and seizures and above all the need to protect the officer's safety incident to the investigation by the state.
 









# Conclusion
With the 4 matrices, we would prefer using a Random Forest Model as it has better performance matrix on test data while Decision Trees Model has better performance metrix on train data which shows high Variance
Therefore, when using the Random Forest model, we can accurately determine whether or not a Terry Stop ended in an arrest 72% of the time. The most influential features when using the Random Forest model are related to the precinct and if there was an arrest flag. 
The top 5 features are: 
    1. Arrest Flag 
    2. Missing precint 
    3. West Precinct 
    5. Frisk Flag given
    

# Recommendations

Train officers on when is an appropriate time to arrest someone during the terry stop vs. when it is appropriate to wait until later as this is another key indicator of arrests.
Try to capture the officer's precinct for all terry stops to have a better opportunity to predict if an arrest will occur.
Train officers on when is an appropriate time to 'frisk' someone as this is another key indicator of arrests.

While 72% is decently accurate, there still is room for improvement. Moving forward, I would like to look into further tuning our model, either through cleaning up the data more or through adjusting the model inputs. Additionally, looking into other types of classification models, specifically deep learning models, could also help generate a more accurate model.

