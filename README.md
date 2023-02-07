This repository aims to collect datasets for trustworthy machine learning.

##### Credit Card Default Data Set

This data set contains 20,000 individuals described by 23 attributes (e.g., gender, age). We have removed individuals with missing attributes and reduced the sample size to 20,000 from 30,000.

The true label is Default Payment (1:yes; 0:no).

The sensitive feature is Education Degree. We have binarized the original value (1:graduate school; 2:university; 3:high school; 4:others) into (1:lower education) if it is <=3 and (0:higher education) otherwise (as done in [paper](http://papers.nips.cc/paper/8294-the-price-of-fair-pca-one-extra-dimension.pdf))

creditcarddefault.csv is the data set; each row is an individual; the 24th column is the true label; the 3rd column is the sensitive feature.

creditdefault_index.csv contains 50 random shuffles of individual indices; each row is a random shuffle.

 [Data Source](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

##### Communities and Crime Data Set

This data set contains 1,993 communities described by 101 attributes (e.g., population, household size).

Label is Crime Rate (1:high; 0:low).

The sensitive feature is the Percentage of African American Residents. We have binarized the original value into (1:high) if it is >=50% and (0:low) otherwise.

crimecommunity.csv is the data set; each row is a community; the 101st column is the true label; the 1st column is the sensitive feature.

crimecommunity_index.csv contains 50 random shuffles of community indices.

[Data Source](http://archive.ics.uci.edu/ml/datasets/communities+and+crime)

##### COMPAS Data Set

This data set contains 16,000 defendants described by 16 attributes (e.g., sex, ethnicity).

The label is Risk of Recidivism (1:high; 0:low).

Sensitive feature is Race (1:black; 0:white).

compas.csv is the data set; each row is a defendant; the 16th column is the true label; the 15th column is the sensitive feature.

compas_index.csv contains 50 random shuffles of defendant indices.

[Data Source](https://www.kaggle.com/danofer/compass)

#### Graph Data Sets

##### Cora Dataset

The Cora dataset consists of 2,708 scientific publications classified into one of seven classes. The citation network consists of 5,429 links. Each publication in the dataset is
described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1,433 unique words.

[Data Source](https://www.kaggle.com/datasets/mrkmakr/cora-dataset)

##### CiteSeer Dataset

The CiteSeer dataset consists of 3,312 scientific publications classified into one of six classes. The citation network consists of 4,732 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 3,703 unique words.

[Data Source](https://www.kaggle.com/datasets/shichenyang/citeseer)

##### PubMed Dataset

The Pubmed Diabetes dataset consists of 19,717 scientific publications from the PubMed database pertaining to diabetes classified into one of three classes. The citation network consists of 44,338 links. Each publication in the dataset is described by a TF/IDF weighted word vector from a dictionary which consists of 500 unique words.

[Data Source](https://relational.fit.cvut.cz/dataset/PubMed_Diabetes)

##### Pokec-z & Pokec-n Datasets

The Pokec-z dataset consists of 67,796 users and each user is described by 275 attributes. The Pokec-n dataset includes 66,569 users and each user is associated with 264 attributes. Region is treated as the sensitive attribute, and users’ working field is the target label.

[Data Source](https://github.com/HuiHu1/Privacy-Preserving-Graph-Convolutional-Network/tree/main/datasets)

##### German Credit Dataset

The German credit dataset contains 1,000 users and each user is described by 27 attributes. The sensitive attribute in this dataset is users’ gender, and the target label is good or bad credit risks.

[Data Source](https://github.com/HuiHu1/Privacy-Preserving-Graph-Convolutional-Network/tree/main/datasets)

##### Recidivism Dataset

The Recidivism dataset contains 18,876 defendants who got released on bail at the U.S. state courts during 1990-2009. Each defendant is associated with 18 attributes. Race is treated as the sensitive attribute, and the target label is whether the defendant is likely to commit a violent crime or not.

[Data Source](https://github.com/HuiHu1/Privacy-Preserving-Graph-Convolutional-Network/tree/main/datasets)

##### Credit Defaulter Dataset
The Credit Defaulter dataset includes 30,000 individuals connected based on the similarity of their spending and payment patterns. Age is treated as the sensitive attribute, and the target label is whether an individual will default on the credit card payment or not.

[Data Source](https://github.com/HuiHu1/Privacy-Preserving-Graph-Convolutional-Network/tree/main/datasets)


##### Rochester38 Dataset

The Rochester38 dataset includes 4,563 users, users' gender is considered the sensitive attribute, and the utility label is the class year, i.e., the year when students enroll in school. The edges among users denote their friendship relationships.

[Data Source](https://networkrepository.com/socfb-Rochester38.php)


##### Yale4 Dataset

The Yale4 dataset contains 8,578 users. We treat the class year as the sensitive attribute, and the students' status flag is the utility label. The edges among users denote their friendship relationships.

[Data Source](https://networkrepository.com/socfb-Yale4.php)
