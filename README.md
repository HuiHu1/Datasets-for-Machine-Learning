
#### Datasets-for-Machine-Learning 

#### Credit Card Default Data Set

This data set contains 20,000 individuals described by 23 attributes (e.g., gender, age). We have removed individuals with missing attributes and reduced sample size to 20,000 from 30,000.

Label is Default Payment (1:yes; 0:no).

Sensitive feature is Education Degree. We have binarized the original value (1:graduate school; 2:university; 3:high school; 4:others) into (1:lower education) if it is <=3 and (0:higher education) otherwise (as done in [paper](http://papers.nips.cc/paper/8294-the-price-of-fair-pca-one-extra-dimension.pdf))

creditcarddefault.csv is the data set; each row is an individual; the 24th column is label; the 3th column is sensitive feature.

creditdefault_index.csv contains 50 random shuffles of individual indicies; each row is a random shuffle. 

 [Data Source](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

#### Communities and Crime Data Set

This data set contains 1,993 communities described by 101 attributes (e.g., population, household size).

Label is Crime Rate (1:high; 0:low).

Sensitive feature is Percentage of African American Residents. We have binarized the original value into (1:high) if it is >=50% and (0:low) otherwise.

crimecommunity.csv is the data set; each row is a community; the 101th column is label; the 1th column is sensitive feature.

crimecommunity_index.csv contains 50 random shuffles of community indicies.

[Data Source](http://archive.ics.uci.edu/ml/datasets/communities+and+crime)

#### COMPAS Data Set

This data set contains 16,000 defendents described by 16 attributes (e.g., sex, ethnic).

Label is Risk of Recidivism (1:high; 0:low).

Sensitive feature is Race (1:black; 0:white).

compas.csv is the data set; each row is a defendant; the 16th column is label; the 15th column is sensitive feature.

compas_index.csv contains 50 random shuffles of defendant indicies.

[Data Source](https://www.kaggle.com/danofer/compass)
