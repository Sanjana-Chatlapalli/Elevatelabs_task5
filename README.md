 **Decision Trees and Random Forests**

### Objective
The objective of this task is to learn tree-based machine learning algorithms for classification using Decision Trees and Random Forests.

---

## Dataset

- **Dataset Name:** heart.csv
- **Type:** Heart Disease Dataset
- **Target Column:** target

---

## Files in this Repository

```
Elevatelabs_task5/
│── task5.ipynb          # Jupyter Notebook
│── heart.csv            # Dataset
│── README.md            # Project Documentation
```

---

## Libraries Used

- pandas
- matplotlib
- scikit-learn

## Project Workflow

1. Load the Heart Disease dataset.
2. Explore the dataset.
3. Split the data into training and testing sets.
4. Train a Decision Tree Classifier.
5. Visualize the Decision Tree.
6. Train a Random Forest Classifier.
7. Compare model accuracies.
8. Analyze feature importance.
9. Evaluate the model using Cross Validation.

---

## Machine Learning Models

### Decision Tree Classifier
- Used for classification.
- Controlled tree depth using `max_depth` to reduce overfitting.

### Random Forest Classifier
- Ensemble learning algorithm.
- Uses multiple Decision Trees.
- Provides better accuracy and generalization.

---

## Evaluation Metrics

- Accuracy Score
- Classification Report
- Confusion Matrix
- Cross Validation Score

---

## Feature Importance

Random Forest calculates the importance of each feature, helping identify which features contribute the most to heart disease prediction.

---

## Results

The notebook compares:

- Decision Tree Accuracy
- Random Forest Accuracy
- Feature Importance
- Cross Validation Accuracy

Generally, the Random Forest model performs better than the Decision Tree because it combines predictions from multiple trees, reducing overfitting and improving accuracy.

---

## Conclusion

In this project:

- Built a Decision Tree Classifier.
- Visualized the Decision Tree.
- Built a Random Forest Classifier.
- Compared both models.
- Evaluated performance using Cross Validation.
- Interpreted Feature Importance.

This project demonstrates the effectiveness of ensemble learning techniques for classification tasks.

---
