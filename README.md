# Classification of Chronic Kidney Disease Using Machine Learning Classifiers

## 📌 Project Overview

Chronic Kidney Disease (CKD) is a growing health concern worldwide, and often it is detected only in later stages. This project aims to detect CKD earlier by studying medical data and applying machine learning methods. Different classifiers were tested and compared to identify which ones give the most dependable results, with the goal of helping doctors and patients receive clearer, timely insights that support better treatment and care.

## 🎯 Objectives

* Detect CKD at early stages using patient medical records.
* Compare multiple machine learning classifiers for accuracy and reliability.
* Identify important medical features that influence CKD classification.
* Provide a system that can support doctors in making quicker, data-driven decisions.

## 🛠️ Technologies & Tools

* **Programming Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
* **Framework:** Flask (for simple web interface)
* **IDE:** PyCharm
* **Database:** MySQL (for storing records)
* **Dataset:** UCI Machine Learning Repository – CKD Dataset

## 🧪 Methods & Approach

1. **Data Collection & Preprocessing** – handled missing values, normalized features, and prepared data for analysis.
2. **Feature Selection** – identified key features such as age, haemoglobin, and WBC count.
3. **Model Training** – applied multiple classifiers including:

   * Random Forest
   * Support Vector Machine (SVM)
   * Decision Tree
   * K-Nearest Neighbors (KNN)
4. **Evaluation** – compared models on accuracy, sensitivity, and specificity.
5. **Result** – SVM achieved the best performance with **\~86.5% accuracy**.

## 📊 Results

* Support Vector Machine outperformed other classifiers.
* Key features like haemoglobin levels, WBC count, and age had the most impact.
* Feature selection improved classifier accuracy by up to **4.7%**.

## 🚀 Future Enhancements

* Integration with live hospital data for real-time prediction.
* Deploying as a cloud-based application for wider access.
* Extending the model with deep learning techniques.
* Adding visualization dashboards for doctors and patients.

## 📂 Repository Structure

```
ckd-classification-ml/
│-- data/              # Dataset (not uploaded here, use UCI repository)
│-- notebooks/         # Jupyter notebooks for exploration
│-- src/               # Python source code
│   │-- preprocessing.py
│   │-- models.py
│   │-- evaluation.py
│-- app/               # Flask web app
│   │-- templates/
│   │-- static/
│   │-- app.py
│-- results/           # Plots, accuracy scores, comparisons
│-- requirements.txt   # Python dependencies
│-- README.md          # Project documentation
│-- LICENSE            # Project license
│-- .gitignore         # Ignored files/folders
│-- CONTRIBUTING.md    # Contribution guidelines
```

## ⚖️ License

This project is licensed under the **MIT License** – feel free to use, learn, and build upon it.

### LICENSE File (MIT)

```
MIT License

Copyright (c) 2025 Manchala Ramesh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### .gitignore File

```
# Python cache
__pycache__/
*.pyc
*.pyo
*.pyd

# Virtual environments
venv/
.env/

# Jupyter Notebook checkpoints
.ipynb_checkpoints/

# Dataset files
*.csv
*.xlsx
/data/
/dataset/

# Logs
*.log

# IDE settings
.vscode/
.idea/

# OS files
.DS_Store
Thumbs.db
```

### CONTRIBUTING.md

```
# Contributing Guidelines

Thank you for considering contributing to this project! 🎉

## How to Contribute
1. **Fork the repository** – Create your own copy of this project.
2. **Create a new branch** – Use a descriptive branch name (e.g., `feature-model-update`).
3. **Make your changes** – Add code, fix bugs, or improve documentation.
4. **Test your changes** – Ensure everything runs smoothly.
5. **Submit a Pull Request (PR)** – Explain clearly what you changed and why.

## Contribution Ideas
- Improving data preprocessing or feature selection.
- Adding new machine learning classifiers.
- Enhancing evaluation metrics or visualizations.
- Improving documentation and project structure.
- Suggesting and implementing new features.

## Code of Conduct
Be respectful and constructive in all discussions. Treat others with kindness and collaborate in a positive way.

---
Happy contributing! 🚀
```

## 🙏 Acknowledgements

This work was carried out as part of our **final year B.Tech project** under the guidance of **Mr.S.Praveen Kumar ,Assistant Professor, Department of CSE, DR M.G.R Educational and Resesrch Institute,Chennai**. Special thanks to faculty, friends, and family for their support.

---

## 📦 Requirements

Here’s the `requirements.txt` for your project:

```
pandas
numpy
scikit-learn
matplotlib
flask
mysql-connector-python
```
