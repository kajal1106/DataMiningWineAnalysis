# DataMiningWineAnalysis
 Comprehensive analysis and modeling of white wine data using various data mining techniques. This repository includes regression analysis to predict wine quality, decision tree analysis for classification, and kNN analysis for further insights. Explore visualizations, models, and key takeaways to enhance your understanding of the complex relationships within the world of white wine.

 ## Key Features
- Regression Analysis: Linear and polynomial regression models to predict white wine quality.
- Decision Tree Analysis: Classification of wines into quality classes with insights into decision boundaries.
- kNN Analysis: Classifying wines using kNN and Random Forest classifiers with visualized decision boundaries.

## Folder Structure
/DataMiningWineAnalysis
    /data
        - white_wine_quality.csv
        - wine_classification_data.csv
    /doc
        - DataMiningReport.pdf
    /plots
        /knn
            - knn_plot_1.png
            - ...
        /regression
            - regression_plot_1.png
            - ...
        /decision-tree
            - decision_tree_plot_1.png
            - ...
    /python
        - notebook_regression.ipynb
        - notebook_knn.ipynb
        - notebook_decision_trees.ipynb

- `notebook_regression.ipynb`: Exploratory Data Analysis, model implementations, and visualizations.
- `notebook_decision_trees.ipynb`: EDA, Decision Tree model implementations, and visualization files.
- `notebook_knn.ipynb`: Data preparation, kNN and Random Forest implementations, and visualizations.

## Results and Insights

- Polynomial regression outperformed linear regression, suggesting a nonlinear relationship between features and wine quality.
- Decision Tree models achieved a high accuracy of 94%, providing detailed insights into feature importance.
- kNN and Random Forest classifiers demonstrated reasonable accuracy, with visualized decision boundaries enhancing interpretability.

## References

- [White Wine Quality Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality.zip)
- [Wine Classification Dataset](https://archive.ics.uci.edu/dataset/109/wine)