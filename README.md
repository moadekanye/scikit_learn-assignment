# scikit_learn-assignment
The Support Vector Classifier (SVC) and the Random Forest Classifier both performed very well and had similar results. The SVC had a slightly higher score for finding true positive cases, meaning it was better at correctly identifying patients who actually have cancer. This is important in healthcare.

On the other hand, Logistic Regression did a little worse overall, but it is easier to understand and faster to use, which can be helpful when you need quick results or clear explanations.

If you need to choose the best model, the SVC is a good option because it is better at finding true positive cases. But if you need something quick and easy to explain, you might prefer Logistic Regression, even if it’s not quite as accurate.

This project focuses on building and comparing machine learning models to classify breast cancer using Scikit-Learn's built-in dataset. We evaluate three models: Logistic Regression, Support Vector Classifier (SVC), and Random Forest Classifier, to see which one is best at predicting whether tumors are malignant or benign. The BreastCancerClassifier class handles loading and preparing the data, training the models, and evaluating their performance with metrics like accuracy, precision, recall, and F1 score. Key attributes include X (features), y (labels), and models (the classifiers). A limitation is the small dataset, so results might vary with different splits.
