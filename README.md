# Wine Quality Classification — Decision Trees

Hands-On Machine Learning (Géron), Chapter 6: Decision Trees, applied to the UCI Red Wine Quality dataset.

## Task
Binary classification: good wine (`quality >= 6`) vs not good (`quality < 6`).

## Dataset
- `winequality-red.csv` — 1,599 red wines, 11 physicochemical features (`;`-separated)
- Target balance after binarizing: 53.5% good / 46.5% not good
- 240 duplicate rows noted

## Progress
- [x] Data loading and exploration
- [x] Target binarized, stratified 80/20 train/test split
- [ ] Train a DecisionTreeClassifier
- [ ] Visualize the tree
- [ ] Regularization (max_depth, min_samples_leaf) and tuning
- [ ] Evaluation on the test set

## Run
Open `decision_trees_wine_quality.ipynb` in Colab or Jupyter with the CSV in the same folder.
