# iris_dataset_analysis
Classification Algorithm on Iris Dataset


MINOR PROJECT

SUBJECT: AI – MINOR – JUNE 



PROJECT STATEMENT: TO PERFORM CLASSIFICATION ANALYSIS ON IRIS DATASET. PERFORM ANY TWO CLASSIFICATION ALGORITHMS AND COMPARE THE ACCURACY.
 









SUBMITTED BY: PRIYANSHU SHUKLA 
E-mail: priyanshukla0411@gmail.com


LET US DIG DEEPER ABOUT IRIS DATASET: 

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis. It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus".
The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other.
The use of this data set in cluster analysis however is not common, since the data set only contains two clusters with rather obvious separation. One of the clusters contains Iris setosa, while the other cluster contains both Iris virginica and Iris versicolor and is not separable without the species information Fisher used. This makes the data set a good example to explain the difference between supervised and unsupervised techniques in data mining: Fisher's linear discriminant model can only be obtained when the object species are known: class labels and clusters are not necessarily the same.



k-NN on Iris Dataset
k-Nearest Neighbor(k-NN) is an instance-based supervised learning algorithm which classifies a new instance by comparing it with already stored instances in the memory that have already been seen in training.
We focus on hyper parameter tuning for kNN using the Iris dataset. The optimal hyper parameters are then used to classify the test set instances and compute the final accuracy of the model. The implementation has been done from scratch with no dependencies on existing python data science libraries.
The hyper parameters tuned are:
1.	Distance Metrics: Euclidean, Normalized Euclidean and Cosine Similarity
2.	k-values: 1, 3, 5, and 7
 
DECISION TREE CLASSIFICATION ON IRIS DATASET
Using Scikit-learn to implement a Simple Decision Tree Classifier:

Scikit-learn is library for the development of machine learning models, whether for regression or classification problems, that is as widely used as it is appreciated. Today we will be implementing a simple decision tree model to classify iris plants into three species using the lengths and widths of their petals and sepals, a classic data set in the machine learning community.
The iris samples in question fall into three species: Iris setosa, Iris versicolor, and Iris virginica. At first glance, the three species can look remarkably like each other, and this is especially the case for the latter two. However, thanks to the careful measurements taken and presented by Anderson and Fisher, an individual sample may be classified with a high degree of accuracy via machine learning models if the relevant measurements are taken.
Decision tree models are the simplest form of tree-based models, and are arguably the simplest form of supervised multivariate classification models. A series of logical tests (generally in the form of Boolean comparisons) are applied to the sample entries and their resulting subsets in turn to arrive at a final decision. It is very easy to visualize the decision process in a simple flowchart to trace the rational of every assignment made by a decision tree model, making it among the most interpretable of models.
The following code, strongly derived from scikit-learn's documentation, shows how a simple decision tree model may be applied and visualized.
 
