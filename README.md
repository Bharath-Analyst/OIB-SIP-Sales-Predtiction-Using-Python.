# Sales-Predtiction-Using-Python.
Aim

This project aims to forecast sales by leveraging the provided dataset, which includes details about advertising expenditures on various platforms (TV, Radio, and Newspaper) along with the corresponding sales amounts.

**Libraries Used**

The following important libraries were used for this project:

numpy

pandas

matplotlib.pyplot

seaborn

sklearn.model_selection.train_test_split
sklearn.linear_model.LinearRegression.

Dataset.

The dataset was loaded using pandas as a DataFrame from the file "advertising.csv".

**Data Exploration and Preprocessing**

1) The dataset's shape and descriptive statistics were revealed through df.shape and df.describe(), respectively.

2) To explore the relationships between advertising expenditures on TV, Radio, Newspaper, and sales, a pair plot was generated using seaborn.pairplot.

3) The distribution of advertising expenditures on TV, Radio, and Newspaper was visualized using histograms plotted with matplotlib.pyplot.hist.
   
**Correlation Analysis**

A correlation matrix heatmap was plotted to observe the correlation between advertising expenditure on TV, Radio, Newspaper, and sales using seaborn.heatmap.

Model Training

1) The dataset was partitioned into training and testing sets employing the train_test_split method.

2) A linear regression model was trained on the training data using the sklearn.linear_model.LinearRegression module.
   
Model Prediction

1) Sales predictions for the test set were made using the model, with advertising expenditure on TV as input, employing model.predict(X_test) alongside the actual advertising expenditure on TV in the test set.

2) The model's coefficients and intercept were extracted using model.coef_ and model.intercept_.

3) The predictions and actual sales values were visually represented through plots using matplotlib.pyplot.plot and matplotlib.pyplot.scatter.
