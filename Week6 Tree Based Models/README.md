# Week6 Tree Based Models

## Overview
Last week you built your first models (Linear and Logistic Regression). This week you learned a different family of models: **trees**. A decision tree asks simple yes/no questions to reach an answer, and a random forest combines many trees so they vote. You also learned the standard ways to measure a classification model properly, beyond a single accuracy number, and finished by comparing three models fairly on the same data.

## What We Covered

**Day 1 - Decision Trees**
How a tree makes a prediction by asking a chain of yes/no questions, how to read a tree diagram (question, gini, samples, value, class), and how to train one with Scikit-learn. Covered overfitting (memorizing the training data) and how `max_depth` keeps a tree simple.

**Day 2 - Random Forests**
Why many trees voting together is steadier than one tree, how to train a `RandomForestClassifier`, what `n_estimators` means, and how to read feature importance to see which columns the model relied on. Also covered why feature importance is a rough guide, not exact truth.

**Day 3 - Evaluation Metrics**
The confusion matrix (TP, TN, FP, FN), and the main metrics built from it: accuracy, precision, recall, and F1. Also ROC-AUC, and the accuracy trap: a lazy model can score 95% accuracy and still catch nothing when one group is rare.

**Day 4 - Model Comparison + Week 6 Mini Challenge**
The fair-test rules for comparing models (same training data, same test data, same metrics, judged on test data). Completed a mini challenge training Logistic Regression, a Decision Tree, and a Random Forest, putting every metric in one table, and writing a conclusion in plain English.

## Files in This Folder
- `Day1 Decision Trees.pdf` / `Day1 Decision Trees.ipynb`
- `Day2 Random Forests.pdf` / `Day2 Random Forests.ipynb`
- `Day3 Evaluation Metrics.pdf` / `Day3 Evaluation Metrics.ipynb`
- `Day 4model Comparison Mini Challenge.pdf` / `Day4 Model Comparison Mini Challenge.ipynb`
- `Images/` - the diagrams used in the PDFs (decision tree, feature importance, confusion matrix, model comparison)

## Note on This Week's Materials
Every practice question is fully solved, with simple code and comments, using made-up student data (hours studied, attendance, sleep -> pass/fail), so everything runs right away with no upload. Each notebook was run from top to bottom to confirm it works. The diagrams are drawn from the real model results in the notebooks.

One honest result to remember: in this dataset Logistic Regression scored as well as or slightly better than the tree and the forest. With only 60 test students the gaps are about 1 to 2 students, so treat the models as roughly tied, and pick the simplest one. A fancier model does not always win.

## Week 6 Checklist

- [X] Day 1 - Decision Trees (questions, reading a tree, overfitting, max_depth)
- [X] Day 2 - Random Forests (many trees voting, feature importance)
- [X] Day 3 - Evaluation Metrics (confusion matrix, precision, recall, F1, ROC-AUC)
- [X] Day 4 - Model Comparison + Mini Challenge (three models, one fair test)

## Skills Gained This Week
- Able to explain how a decision tree makes a decision, and read a tree diagram
- Able to spot overfitting by comparing training and test scores
- Able to train a random forest and read its feature importance
- Able to read a confusion matrix and calculate accuracy, precision, recall, and F1
- Understand ROC-AUC and why accuracy alone can fool you
- Able to compare several models fairly and choose one with a clear reason

**Next up: Week 7 - Model Optimization (cross-validation, hyperparameter tuning, regularization)**
