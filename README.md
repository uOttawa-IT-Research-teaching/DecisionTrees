# DecisionTrees

This machine learning training explores the dual nature of Decision Trees, demonstrating a fascinating interplay between human intuition and mathematical optimization. The training is supported by various works by D. Kahneman, Busemeyer et al., and researchers at the University of Ottawa. It delves into how decision trees use simple, hierarchical branching based on key features, mirroring how our minds categorize objects using decisive traits. Yet, these trees are also rigorously constructed by calculating metrics like information gain that maximize analytical power. This tutorial will encompass an overview of the learning objectives, a dedicated section detailing the prerequisites for completing the tutorial, and a guide on best practices for Research Data Management (RDM).

The training comprises three notebooks, each focusing on distinct applications of the Decision Tree and its associated Random Forest algorithm.

The first notebook focuses on the Iris flower data, aiming to develop a model capable of predicting the iris flower’s class based on its distinctive features. The second notebook extends to Random Forest models, demonstrating how this ensemble method, comprising multiple decision trees, can enhance prediction accuracy. Both these notebooks utilize Open Data sources to ensure and demonstrate how these machine learning models partition data into groups, facilitating accurate predictions when new data is introduced.  The third notebook delves into the efficacy of Random Forest classifiers in enhancing predictions on noisy datasets. It uses the cleaned dataset from a Linear Regression tutorial as an example, demonstrating the superiority of random forests over linear regression on such datasets. Random forests, an ensemble method, leverage the predictions of multiple decision trees to yield more robust and generalized solutions. By employing the cleaned dataset containing anomalies and missing/incorrect values, learners gain insight into how random forests mitigate the impact of noise and other issues, thereby offering superior predictive performance. Understanding this fusion between intuitive shortcuts and calculated reasoning is key to advancing decision tree capabilities and addressing their ethical and regulated use in AI applications.

View the paper at uO Research: Collection Science informatique et génie électrique - Publications // Electrical Engineering and Computer Science - Publications
[Decision Trees: Modeling with fast intuition and slow, deliberate analysis](https://ruor.uottawa.ca/handle/10393/45456)

| Dataset      | Source    | Licence |
|:-------------|:----------|:--------|
| data2020_cln.csv | [Data cleaning and linear regression](https://github.com/uOttawa-IT-Research-teaching/ML_cleaning_and_regression)      | CC-BY 4.0 |
| iris_flower_feature_measurements.csv | [doi:10.24432/C56C76](https://doi.org/10.24432/C56C76) | CC0: Public Domain |
