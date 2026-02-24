# K-Nearest Neighbors (KNN) Classification

Machine learning project using KNN to predict a target class, with hyperparameter tuning to find the optimal K value.

## Overview

Python project implementing K-Nearest Neighbors for classification. Features include data scaling with StandardScaler, model training with various K values, and error rate analysis to identify the optimal K.

## Approach

1. **Feature Scaling** - StandardScaler to normalize features
2. **Initial Model** - KNN with default K value
3. **K Optimization** - Tested K values from 1 to 40
4. **Error Analysis** - Plotted error rates vs K values
5. **Final Model** - Re-trained with the K value producing the lowest error rate

## Tech Stack

- **Language:** Python (Jupyter Notebook)
- **Libraries:** Scikit-learn (KNeighborsClassifier, StandardScaler), Pandas, NumPy, Matplotlib, Seaborn

## Getting Started

```bash
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

## Author

**Jonas** - Data Engineer | St. Louis, MO
