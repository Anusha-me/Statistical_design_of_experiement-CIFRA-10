# 🧠 CNN Hyperparameter Optimization using DOE – CIFAR-10

This project applies **Design of Experiments (DOE)** to optimize hyperparameters in a **Convolutional Neural Network (CNN)** for image classification using the CIFAR-10 dataset.

---

## 🎯 Objective

Improve CNN accuracy by:
- Identifying significant hyperparameters
- Using fractional factorial design to minimize experimental runs
- Creating a regression model to predict validation accuracy
- Validating predictions with actual CNN training

---

## ⚙️ Hyperparameters Analyzed

- Kernel Size (Conv2D)
- Number of Convolutional Layers
- Number of Filters
- Number of Neurons
- Learning Rate
- Epochs
- Batch Size
- Momentum

---

## 📊 Results

- R² of **99.83%**
- Fractional factorial design identified A, B, C, D, E, and their interactions (e.g., AB, AC) as significant
- Third assumption gave best model validation

---

## 📁 Files Included

📄 Report_file.pdf
    Full report detailing methodology, fractional factorial design, data analysis, regression modeling, and conclusions.

📊 SDM_project_file.xlsx
    Spreadsheet containing experimental results, coded values, regression outputs, and validation accuracy comparisons.

📦 requirements.txt
    List of Python libraries used in the project (e.g., TensorFlow, NumPy, Pandas, Scikit-learn).

🧠 model_summary.txt
    Description of the CNN model structure, training configuration, and hyperparameter ranges.
