# Text Classification Using Traditional ML Models

This assignment was part of the Text Analytics Course of the M.Sc in Data Science program of the Athens University of Economics and Business.
It was a group assignment with the two other group members being my classmates Despoina Angelonidi and Eirini Mylona.

We decided to use the [movie review dataset](https://www.cs.cornell.edu/people/pabo/movie-review-data/) which is released by the Cornell University.

For the models we used for the classification of these reviews, we went with a variety of models, all part of the `scikit-learn` package. These
models were:
- Logistic Regression
- SVM
- K-NN
- MLP
- Naive Bayes

For each of the models we run a Grid Search on a number of the model-specific parameters, in order to find the best combination of said parameters.

Lastly, we present the learning curves of these models, as well as the Precision-Recall Curves for both the `positive` and the `negative` classes.