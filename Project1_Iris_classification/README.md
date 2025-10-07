# 🌸 Iris Flower Classification (with Noise Analysis)

**Goal:**  
Classify iris flowers into species (Setosa, Versicolor, Virginica) using machine learning models,  
and analyze how model performance changes when artificial noise is introduced into the dataset.

---

## 📊 Dataset
Built-in [Iris dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html) from scikit-learn.

- **Samples:** 150  
- **Features:** Sepal length, Sepal width, Petal length, Petal width  
- **Classes:** 3 species (Setosa, Versicolor, Virginica)

---

## ⚙️ Methods
### Models Trained
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Each model was trained and evaluated using **5-fold cross-validation**.

### Noise Experiment
To simulate real-world data imperfections, Gaussian noise was added:
```python
X_noisy = X + np.random.normal(0, 0.5, X.shape)
