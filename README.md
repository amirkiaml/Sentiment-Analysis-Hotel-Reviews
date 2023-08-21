# Sentiment-Analysis-Hotel-Reviews
This project involves analyzing hotel review data using Natural Language Processing (NLP) techniques. The project is divided into several steps, starting with Exploratory Data Analysis (EDA) and progressing to data augmentation, modeling, and iterative improvements.

<div align="center">

 ![Reviews](https://drive.google.com/uc?export=view&id=15IkxgtUEjdgmKcciJCGlYYlPPQYgAbUJ)
</div>
 
 Here is a summary of some of the steps taken:

#### Data Exploration and Preparation:
- Examined dataset attributes, structure, and size.
- Transformed review scores into binary sentiment labels.
- Visualized sentiment score distribution and identified potential challenges.

#### Feature Engineering and Transformation:

- Converted non-numeric features for analysis.
- Partitioned data into training and testing sets.
- Utilized text vectorization to convert reviews into numeric format.
- Merged numeric features with vectorized data.

#### Model Selection and Training:

- Implemented logistic regression to predict sentiment.
- Evaluated model accuracy on the test set.
- Extracted significant words using regression coefficients.
- Explored dimensionality reduction via PCA.
- Analyzed dimensions' impact on runtime.
- Employed K-Nearest Neighbors for accuracy assessment.
- Investigated data point variations' effect on runtime.
- Utilized Decision Tree classifier and assessed accuracy.

#### Model Refinement and Optimization:

- Utilized cross-validation to fine-tune hyperparameters.
- Assessed model performance with a confusion matrix.
- Introduced a new feature for enhanced accuracy.
- Justified new feature's significance.
- Reran models with the augmented dataset.
- Re-optimized hyperparameters for superior outcomes.

#### Documentation and Conclusion:
- Compiled annotated Jupyter notebook with code.
- Detailed step-by-step methodology explanation.
- Presented insights from model evaluations.
- Summarized progression from data exploration to refined models.
