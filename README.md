
#### Datasets-for-Machine-Learning 

##### Credit Card Default Data Set

This data set contains 20,000 individuals described by 23 attributes (e.g., gender, age). We have removed individuals with missing attributes and reduced sample size to 20,000 from 30,000.

Label is Default Payment (1:yes; 0:no).

Sensitive feature is Education Degree. We have binarized the original value (1:graduate school; 2:university; 3:high school; 4:others) into (1:lower education) if it is <=3 and (0:higher education) otherwise (as done in [paper](http://papers.nips.cc/paper/8294-the-price-of-fair-pca-one-extra-dimension.pdf))

creditcarddefault.csv is the data set; each row is an individual; the 24th column is label; the 3th column is sensitive feature.

creditdefault_index.csv contains 50 random shuffles of individual indicies; each row is a random shuffle. 

 [Data Source](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

##### Communities and Crime Data Set

This data set contains 1,993 communities described by 101 attributes (e.g., population, household size).

Label is Crime Rate (1:high; 0:low).

Sensitive feature is Percentage of African American Residents. We have binarized the original value into (1:high) if it is >=50% and (0:low) otherwise.

crimecommunity.csv is the data set; each row is a community; the 101th column is label; the 1th column is sensitive feature.

crimecommunity_index.csv contains 50 random shuffles of community indicies.

[Data Source](http://archive.ics.uci.edu/ml/datasets/communities+and+crime)

##### COMPAS Data Set

This data set contains 16,000 defendents described by 16 attributes (e.g., sex, ethnic).

Label is Risk of Recidivism (1:high; 0:low).

Sensitive feature is Race (1:black; 0:white).

compas.csv is the data set; each row is a defendant; the 16th column is label; the 15th column is sensitive feature.

compas_index.csv contains 50 random shuffles of defendant indicies.

[Data Source](https://www.kaggle.com/danofer/compass)

##### Graph Data Sets

##### Cora Dataset

The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication in the dataset is
described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1433 unique words.

[Data Source](https://linqs.soe.ucsc.edu/data)

##### CiteSeer Dataset

The CiteSeer dataset consists of 3312 scientific publications classified into one of six classes. The citation network consists of 4732 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 3703 unique words.

[Data Source](https://linqs.soe.ucsc.edu/data)

##### PubMed Dataset

The Pubmed Diabetes dataset consists of 19717 scientific publications from PubMed database pertaining to diabetes classified into one of three classes. The citation network consists of 44338 links. Each publication in the dataset is described by a TF/IDF weighted word vector from a dictionary which consists of 500 unique words. 

[Data Source](https://linqs.soe.ucsc.edu/data)
