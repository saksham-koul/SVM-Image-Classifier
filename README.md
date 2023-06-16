# SVM-Image-Classifier

- Support Vector Machines (SVM) is a popular machine learning algorithm used for classification and regression purposes. The algorithm is able to distinguish between points in a data set containing 2 different types of classes, using a hyperplane in multidimensional space. Hence, it is a binary classifier.
- However, this project is an attempt to use the SVM classification algorithm to classify data into more than 2 classes. To achieve this, the general SVM objective had to be tweaked a bit, so that data containing more than 2 classes could be classified.
- This has been done using some mathematical derivations, which eventually help to achieve the above-mentioned objective.

### Dataset
- The dataset used for this project is a set of around 200 different images each of three different kinds of animal species - dogs, cats and pandas. The dataset was taken from [Kaggle](https://www.kaggle.com/ashishsaxena2209/animal-image-datasetdog-cat-and-panda).

### Results
The SVM model created in this project runs at an accuracy comparable to the built-in SVM classifier in the scikit-learn Python module.
