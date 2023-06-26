
# Random Forest for Music Genre Classification

1. Music Genre Dataset: The code is designed to work with a music genre dataset, which can be found on the GitHub repository with the username "kumargauravsingh14". 

2. Libraries/Modules: The code imports several libraries and modules that are commonly used in data analysis and machine learning tasks:

- pandas: Used for data manipulation and analysis, providing data structures and functions to work with structured data.
- numpy: A fundamental library for numerical computations, particularly for working with arrays and mathematical operations.
- matplotlib: A data visualization library in Python, used here for creating plots and charts.
- sklearn (scikit-learn): A popular machine learning library that provides various algorithms, evaluation metrics, and tools for data preprocessing.
3. Preprocess MinMax Scaling: The code applies MinMax scaling to the dataset. MinMax scaling is a preprocessing technique that scales the features to a specific range (usually between 0 and 1) by subtracting the minimum value and dividing by the range of the feature. This ensures that all features have a consistent scale and helps in preventing certain features from dominating the learning algorithm.

4. 10 Fold CV: The code performs 10-fold cross-validation. Cross-validation is a technique used to assess the performance and generalization ability of a machine learning model. In 10-fold cross-validation, the dataset is divided into 10 equal-sized folds, and the model is trained and evaluated 10 times, with each fold serving as the test set once while the remaining folds are used as the training set.

5. Random Forest Classifier: The code utilizes the Random Forest Classifier algorithm for classification. Random Forest is an ensemble learning method that combines multiple decision trees to make predictions. It is commonly used for classification tasks due to its robustness and ability to handle large feature sets.

6. Confusion Matrix: The code likely generates a confusion matrix. A confusion matrix is a table that shows the performance of a classification model by comparing the predicted labels with the true labels. It provides valuable insights into the model's accuracy, precision, recall, and other evaluation metrics.
## Used

- Music Genre Dataset [Github kumargauravsingh14](https://github.com/kumargauravsingh14/music-genre-classification/blob/master/data.csv)
- Libraries/Modules (pandas, numpy, matplotlib, sklearn)
- Preprocess MinMax Scalling
- 10 Fold CV
- Random Forest Classifier
- Confusion Matrix



## Reference

[Wahyudi., 2020. Implementasi Metode Random Forest Untuk Klasifikasi Genre
Music. Skripsi S-1, FMIPA ULM, Banjarbaru.](http://digilib.ulm.ac.id/archive/digital/detailed.php?code=13291)


## Authors

- [@eddy01wijaya](https://github.com/eddy01wijaya)

