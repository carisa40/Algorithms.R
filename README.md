## Algorithms.R

#### SVM script: 
- Install packages
- load libraries
- Import the dataset
- Explore the data
- Create the SVM model by setting certain parameters
- Create an SVM classification plot
- Predict each species and create confusion matrix
- Calculate misclassification error
- Calculate accuracy rate


#### K Means script:
- Load dataset
- View structure of the dataset
- View statistical summary and top 3 rows of the dataset
- Remove labels from dataset since kmeans is an unpervised learning algorithm
- View top 3 rows of the new dataset
- Normalize the dataset
- Create the model by applying the kmeans algorithm adn specify number of centroids
- View the number of records in each cluster and the value of each centroid
- Create different plots to verify results of the clustering model
- Tabulate clustering results and calculate accuracy rate


#### C50 script: 
- Install packages and load libraries
- Load dataset
- View top 4 results and dataframe structure of dataset
- Load C50 classifier
- Split dataset into training and testing based on species
- Optional data splitting into sequences
- Create data split based on 70/30 split
- Build model using training data and plot model
- Create predictions on test data using model
- Tabulate results and calculate accuracy rate





SVM accuracy: 97.33% 
misclassification rate = 2.67%

K Means accuracy: 6%
misclassification rate = 94%

C50 accuracy: 93.3% 
misclassification rate = 6.7%

Both the SVM and C50 models performed very well by clustering the species with high levels of confidence.

