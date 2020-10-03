# Introduction: 
Problem is to find out the severity of the accident and the probability of occurrence of accident based on the factors like weather, Road condition, Light condition, Address type(Intersection, Block, Alley). Depending upon the severity and the probability, the recommended speeds could be tuned to perfection and suggested to the drivers. This could be used to suggest the max speed that could be achieved with keeping the probability and the severity at minimum.

# Data:
The accident dataset which has been provided in the last week, is being used here. The features being used in this model are: ’SEVERITYCODE','WEATHER','ROADCOND','LIGHTCOND','ADDRTYPE'

Head of the training data:
![](dta.png)
This data would be encoded using one hot encoding, for classification and a separate column would be created for each category in every independent column.
