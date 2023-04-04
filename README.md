# Yeast
This dataset contains information about the localization site of proteins in yeast cells. The dataset includes 1484 instances and 9 attributes. The attributes include information on sequence name, signal sequence recognition, membrane spanning region prediction, amino acid content analysis, and the presence of certain substrings that act as signals for retention in different organelles. The dataset has no missing values. The class distribution includes 10 localization sites: cytosolic/cytoskeletal, nuclear, mitochondrial, membrane proteins with no/cleaved/uncleaved signal, extracellular, vacuolar, peroxisomal, and endoplasmic reticulum lumen. The dataset was created by Kenta Nakai and maintained at the Institute of Molecular and Cellular Biology at Osaka University


This code loads the Yeast dataset from the UCI Machine Learning Repository using pandas read_csv() method. The sep parameter is set to delim white_space=True to indicate that the columns are separated by one or more whitespace characters. The header parameter is set to None to indicate that the dataset has no header row.

After loading the dataset, the column names are defined and applied to the dataframe using the columns attribute. Finally, the first five rows of the dataframe are displayed using the head() method.

Then the code loads the dataset, splits it into train and test sets, trains a decision tree classifier, evaluates its accuracy on the test set, and prints the confusion matrix:
