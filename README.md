# Kaggle \-Course \- Exercises

A summary of everything I learned across multiple ML courses on Kaggle — from foundational concepts to deep learning and model explainability.

## Table of Contents

- [Intro to Machine Learning](#intro-to-machine-learning)  
- [Intermediate Machine Learning](#intermediate-machine-learning)  
- [Feature Engineering](#feature-engineering)  
- [Intro to Deep Learning](#intro-to-deep-learning)  
- [Computer Vision](#computer-vision)  
- [Machine Learning Explainability](#machine-learning-explainability)

## Intro to Machine Learning

Got an overview of how machine learning models work. Solved several exercises to understand the core concepts and their implementation.

- Used **pandas** to load datasets into a DataFrame and explore its structure  
- Identified the **target column** and separated it from the **feature columns**  
- Built my first model using **scikit-learn** — fitting, predicting, and evaluating accuracy  
- Learned to **split data** into training and testing sets  
- Understood **overfitting** (perfect on training data, poor on new data) and **underfitting** (fails to capture patterns)  
- Discovered that **RandomForest** achieves significantly higher predictive accuracy than a single **DecisionTree**

## Intermediate Machine Learning

Tackled real-world data challenges — messy data, preprocessing, and advanced modelling techniques.

- **Missing Values** — Three approaches:  
    
  1. Drop the column (simple, but loses information)  
  2. **Imputation** — fill with mean/median or flag missing values in a new column  
  3. Extended imputation with indicator columns


- **Categorical Variables** — Three approaches:  
    
  1. Drop the column  
  2. **Ordinal Encoding** — assign unique integers to categories  
  3. **One-Hot Encoding** — create new binary columns for each category


- **Pipelines** — Organised preprocessing and modelling steps cleanly; also used `ColumnTransformer` to bundle different preprocessing steps  
    
- **Cross-Validation** — Used to handle small datasets by creating multiple folds and evaluating each, reducing the effect of randomness  
    
- **XGBoost** — A powerful gradient boosting method for high-performance modelling  
    
- **Data Leakage** — When training data contains information about the target that won't be available at prediction time:  
    
  - *Target leakage* — predictors updated after the target is known  
  - *Train-test contamination* — preprocessing applied before the train/test split

## Feature Engineering

Learned one of the most impactful steps in building great ML models — creating and transforming features to boost model performance.

- **Mutual Information** — Measures the relationship between two quantities; quantifies how much one feature reduces uncertainty about the target  
    
- **Feature Creation** — Creating new columns through:  
    
  - Mathematical transformations  
  - Concatenating existing columns  
  - Group transformations (aggregations)


- **K-Means Clustering** — Groups similar data points by placing **centroids** in the feature space and measuring similarity using straight-line (Euclidean) distance  
    
- **Target Encoding** — For categorical features with **high cardinality**, replaces category labels with a number derived from the target variable

## Intro to Deep Learning

### Deep Learning with Keras & TensorFlow

Completed Kaggle's Intro to Deep Learning course — all 6 lessons and exercises on building and training neural networks from scratch.

**Key learnings:**

- How a single neuron works — linear units, weights, and bias  
- Stacking hidden layers to model complex, non-linear patterns  
- Training with **Stochastic Gradient Descent (SGD)** using Keras & TensorFlow  
- Preventing overfitting with **early stopping** and **dropout**  
- **Batch normalization** to stabilize and speed up training  
- Building a binary classifier end-to-end

**Stack:** `Python` · `TensorFlow` · `Keras`

**Takeaway:** Now comfortable building and tuning neural networks, diagnosing overfitting, and applying deep learning to classification problems.

## Computer Vision

### Computer Vision with Keras & TensorFlow

Completed Kaggle's Computer Vision course — all 6 lessons and exercises on how CNNs work and how to build image classifiers from scratch.

**Key learnings:**

- How **convolutional classifiers** are structured in Keras  
- What **convolution \+ ReLU** actually do to an image  
- **Max pooling** for spatial feature extraction  
- How **stride** and **padding** affect convolution output  
- Designing custom **ConvNet architectures**  
- **Data augmentation** to make models more robust to variation

**Stack:** `Python` · `TensorFlow` · `Keras`

**Takeaway:** Now comfortable building CNNs for image tasks, understanding what happens inside each layer, and using data augmentation to improve results.

## Machine Learning Explainability

### ML Explainability — Kaggle Course

Completed Kaggle's ML Explainability course — focused on understanding *why* a model makes its predictions, not just whether it performs well.

**Key learnings:**

- When and why model insights matter in real-world projects  
- **Permutation Importance** — identify which features matter most to the model  
- **Partial Dependence Plots (PDPs)** — visualise how a feature affects predictions  
- **SHAP Values** — explain individual predictions with game-theoretic attribution  
- Advanced SHAP techniques for deeper global model understanding

**Stack:** `Python` · `SHAP` · `scikit-learn` · `Pandas`

**Takeaway:** Now able to explain model decisions clearly — useful for debugging, stakeholder communication, and building models people can actually trust.

---

 *All courses completed on [Kaggle](https://www.kaggle.com/learn).*  
