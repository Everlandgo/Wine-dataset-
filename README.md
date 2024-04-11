# Wine classifier 
In this project, I deliberately avoided using external libraries and instead developed each component from scratch. I created a customised KNN classifier function, setting hyperparameters such as the choice of distance metric, the dataset and the 'k' value. The values predicted by the classifier were used to evaluate the model's performance against the actual labels and calculate various evaluation metrics.

In addition to the classifier function, I also developed functions for splitting the dataset into a training and a test dataset and for calculating key performance metrics such as accuracy, precision, recall and F1 score. Each of these functions was carefully developed without relying on existing libraries.

I also implemented a cross-validation function to determine the optimal hyperparameters for the KNN classifier. This involved systematically testing different hyperparameter combinations, including various distance metrics such as Euclidean, Manhattan, Minkowski and Chebyshev, as well as different values of 'k' between 0 and 10.

The project concluded with the finding that the combination of the Euclidean distance metric and a 'k' value of 3 was the best hyperparameter configuration for the dataset and the classifier. With this configuration, an accuracy of 97.2% was achieved, signifying a successful completion of the project.

<img width="637" alt="Screenshot 2024-04-11 at 11 39 58 PM" src="https://github.com/Everlandgo/Wine-dataset-/assets/104118335/559c4c47-8a9b-457f-8ceb-3e011b3159d5">

