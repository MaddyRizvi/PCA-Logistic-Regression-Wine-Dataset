# Principal Component Analysis (PCA)

This project demonstrates the use of Principal Component Analysis (PCA) for dimensionality reduction followed by classification using Logistic Regression on the Wine dataset.

## 📂 Dataset
- **Source:** `Wine.csv`  
- **Description:** The dataset contains chemical analysis results of wines grown in the same region in Italy but derived from three different cultivars.

## 🧱 Project Structure
```
principal_component_analysis.ipynb
Wine.csv
README.md
CONTRIBUTING.md
```

### ✅ Decision Boundary Visualizations

**Training Set:**

![Image](https://github.com/user-attachments/assets/3ddd9ae0-ab6a-42cf-8347-32b24861b20d)

**Test Set:**

![Image](https://github.com/user-attachments/assets/fd033191-a3e7-425a-90e5-342cee33eb3b)


## 🛠️ Requirements
Install the following dependencies using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## ▶️ How to Run

You can run the notebook using [Google Colab](https://colab.research.google.com/) or Jupyter Notebook:

```bash
jupyter notebook principal_component_analysis.ipynb
```

Ensure the dataset `Wine.csv` is in the same directory as the notebook.

## 📊 Output

- Visualization of PCA-reduced feature space (2D).
- Classification accuracy of the Logistic Regression model on PCA-transformed data.
- Clear separation of classes after dimensionality reduction.

## 🔍 Details

- **Algorithm:** Logistic Regression
- **Preprocessing:** Standardization
- **Dimensionality Reduction:** Principal Component Analysis (PCA)
- **Distance Metric in PCA:** Euclidean (implicitly used in variance computation)
- **Evaluation:** Train-test split, confusion matrix

## 🧠 Understanding

This project helps understand:
- How PCA reduces dimensionality while retaining important variance.
- How classification models perform after PCA transformation.
- Visualization of high-dimensional data in 2D space.

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute, including suggestions to implement alternative classifiers such as SVM, Decision Trees, or Random Forests.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
