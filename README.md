# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS 

NAME: SANIKA VYAS 

INTERN ID:CT04DN249 

DOMAIN: PYTHON 

DURATION: 4 WEEKS 

MENTOR: NEELA SANTOSH

CODE DESCRIPTION:
This Python program performs a complete machine learning pipeline for classifying Iris flower species using the Logistic Regression model. It begins by importing essential libraries for data handling (pandas, numpy), visualization (matplotlib, seaborn), and machine learning (scikit-learn). The Iris dataset, a classic multiclass classification dataset with features like petal and sepal dimensions, is loaded directly using sklearn.datasets.load_iris(). This data is then converted into a pandas DataFrame to facilitate easier exploration.

The structure and distribution of the data are explored using .head(), .info(), .describe(), and .value_counts() to inspect the first few rows, data types, summary statistics, and class balance. A pair plot using seaborn helps visualize the feature relationships and how well-separated the classes are in 2D projections.

Next, the dataset is preprocessed by separating features and labels, and then applying feature scaling using StandardScaler. This standardization is crucial for models like logistic regression which assume data is centered around zero and on the same scale. The scaled data is split into training and testing sets using train_test_split() to allow the model to be trained and evaluated on separate portions of the data.

A Logistic Regression model is created and trained using the training data. Once trained, the model is used to predict the classes of the test set. The predictions are evaluated using accuracy score, a classification report that includes precision, recall, and F1-score, and a confusion matrix that is visualized using a heatmap. The confusion matrix provides a clear view of how many samples were correctly or incorrectly classified for each class.

This entire workflow showcases a typical supervised learning process. The same structure can be reused for other classification tasks such as customer churn prediction, spam detection, or disease diagnosis—just by changing the dataset. Logistic regression, while simple, is effective for interpretable and baseline models in multiclass classification problems. The visualizations help in understanding data distribution, model performance, and potential improvements like handling imbalanced data or feature selection.

OUTPUT:
