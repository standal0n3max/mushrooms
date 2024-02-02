*Если падение сов — это совпадение, то вращение сов – это совращение. Если человеку 30 лет, то ему и 30 зим. Слабый мужчина ищет оправдание, настоящий мужчина подготовит их заранее. Настоящая женщина должна спилить дерево, разрушить дом и вырастить дочь. Споры


# Mushroom Classification Analysis

## Introduction

In this analysis, I explore the UCI Mushroom Classification dataset with the goal of differentiating between edible (e) and poisonous (p) mushrooms. The objective is to identify key features using various machine learning models to achieve optimal accuracy and precision. The dataset is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/73/mushroom).

## Python Libraries

The following Python libraries are utilized for this analysis:
- Numpy
- Pandas
- Seaborn
- Matplotlib
- Graphviz
- Scikit-Learn

These libraries cover tasks ranging from data processing and visualization to machine learning model implementation.

## Model Selection and Encoding Choice

In the context of differentiating between edible and poisonous mushrooms, the choice of machine learning models is driven by accuracy, interpretability, and effective handling of categorical features.

### Model Choices:

1. **Random Forest:**
   - Ensemble learning for high accuracy and robustness.
   - Well-suited for handling categorical features.

2. **Support Vector Classifier:**
   - Effective in both linear and non-linear classification.
   - Suitable for distinguishing between edible and poisonous mushrooms.

3. **Decision Tree:**
   - Simple and interpretable, providing insights into key features.
   - Aids in highlighting discriminative features.

4. **CatBoost:**
   - Specifically chosen for handling categorical features without extensive preprocessing.
   - Aligns with the focus on effective encoding and modeling of categorical variables.

### Encoding Choice: One-Hot Encoding

Given the categorical nature of the features, one-hot encoding is chosen to preserve information within categorical variables and complement the selected models.

## Exploratory Data Analysis: Violin Plot Analysis and Data Balance

Violin plots are used to gain insights into the distribution of classification characteristics. The dataset is balanced, and unique features for an even split are identified.

## Feature Selection

Feature importance is crucial for understanding model predictions, aiding in feature selection, model interpretability, debugging, business decision-making, and improving model performance.

## Heatmap for Selected Features

Significant associations with edibility and similar information are identified through a heatmap, providing insights into feature correlations.

## t-SNE (t-Distributed Stochastic Neighbor Embedding)

The t-SNE analysis reveals hierarchical complexity, distinct central clusters, spatial relationships, dynamic cluster transitions, diverse poisonous mushroom subtypes, and potential anomalies within the dataset.

## Decision Tree Interpretation

The Decision Tree analysis highlights features crucial for classification, emphasizing the importance of absence of odor, foul odor, absence of bruises, narrow gill size, and spore print colors.

## Feature Classification Groups

Features are classified into groups based on their importance, indicating their association with either edible or poisonous mushrooms.

## Conclusion

The combination of machine learning models, correlation analyses, and visualizations provides a robust understanding of mushroom safety. The research enhances knowledge of key features and emphasizes the importance of diverse analytical approaches for a comprehensive evaluation.
