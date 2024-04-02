# Feature-Engineering

One hot encoding is a technique of converting categorical variables into numerical variable that can be efficiently utilized by a Machine Learning model!

During One hot encoding each label from a categorical variable is converted to a column with binary values representing the presence (1) or absence (0) of that label in that particular row item.

While this is easily doable for cases with limited number of labels per categorical variable but how do we handle cases where there are multiple categorical variables with large and varying number of variables?

In such cases, One hot encoding can be limited for, say, top 10 most frequent variables. Here, top 10 can be top 15 or 20 depending upon the data available and the domain knowledge.

## Advantages:

Straightforward to implement
Prevents from spending hours on variable exploration
Does not massively expand the feature space

## Disadvantages:

Does not add any information to the data that makes the variable more predictive
Does not retain the information of the ignored variables

