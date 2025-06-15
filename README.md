# Iris-Classification
# Iris Flower Classification Project

## Overview
This project demonstrates a complete machine learning workflow for classifying iris flower species using Scikit-learn's Decision Tree classifier. The model achieves perfect classification (100% accuracy) on the famous Iris dataset.

## Key Features
- **Data Exploration**: Visual analysis of feature distributions
- **Decision Tree Modeling**: Interpretable machine learning approach
- **Performance Evaluation**: Comprehensive metrics including accuracy, precision, recall
- **Visualizations**: Professional confusion matrix and decision tree diagrams

## Results
- **100% Accuracy** on test set
- Perfect classification for all three species:
  - Setosa
  - Versicolor
  - Virginica

![Confusion Matrix](Figures/iris_confusion_matrix.png)

## Files Included
| File | Description |
|------|-------------|
| `iris_classification.ipynb` | Main Jupyter Notebook |
| `Figures/iris_confusion_matrix.png` | Confusion matrix visualization |
| `Figures/iris_feature_distribution.png` | Feature distribution by species |
| `Figures/iris_decision_tree.png` | Decision tree structure visualization |
| `Figures/iris_classification_explanation.mp4` | Video Explanation |

## Requirements
```python
Python 3.8+
scikit-learn==1.2.2
pandas==1.5.3
numpy==1.24.3
matplotlib==3.7.1
seaborn==0.12.2
```
# How to Run

## Clone Repository

```bash
git clone https://github.com/N-Segecha/iris-classification.git
cd iris-classification
```
## Create virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

## Install dependencies:

pip install -r requirements.txt

## Launch Jupyter Notebook:

jupyter notebook iris_classification.ipynb

# Execute all cells:

Go to Kernel > Restart & Run All in Jupyter

# 🎥 Video Explanation (45 seconds)
[🎥 Iris Classification Explained (video)](Figures/iris_classification_explanation.mp4)

✅ Dataset overview and feature distributions

✅ Model training process

✅ Performance evaluation results

✅ Confusion matrix interpretation

# Contributors
Nelly Maritim: Scikit-learn Iris Classification Implementation
