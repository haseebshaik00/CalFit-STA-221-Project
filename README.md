# CalFit-STA-221-Project

> STA 221: Big Data & High Dimensional Statistical Computing

CalFit: Physiology-Aware Gradient Boosting with Conformal Intervals for Reliable Calorie Prediction

## Step-1: Initial Setup
This step is optional, but recommended for reproducibility.

```bash
conda create -n calfit-env python=3.10 -y
conda activate calfit-env
pip install -r requirements.txt
```

> If you are **not** using Conda, ensure you are on **Python 3.10+**, then run:

```bash
pip install -r requirements.txt
```

## Step-2: Verify Data Folder

Make sure while downloading the project from git, you have 2 csv files `calories.csv` and `exercise.csv` in the data folder, or else download and import the dataset into the data folder from the following link: [Calories Burnt Dataset | Kaggle](https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos/data)


## Step-3: EDA & Research Questions
`1-calfir-analysis-EDA-RQ.ipynb`: This file contains the script which was used to import, load and preprocess the dataset and perform EDA over it. It also contains the analysis of our 3 main research questions.

> To run on local, make sure you have the .ipynb file/notebook, and then run each cell via VS Code.

## Step-4: Post-Discussion Analysis
`2-post-discussion-analysis.ipynb`: This file contains follow-up analysis based on Prof. Nicolai Amann’s feedback from the presentation on **Nov 25, 2026**. The analysis is on the questions:

- Why we did not consider **LASSO-Poly** models?
- Given a strong \(R^2\), how we checked for potential **overfitting**?

> To run on local, make sure you have the .ipynb file/notebook, and then run each cell via VS Code.

---

**Disclaimer:**  
This research and its findings are intended solely for academic and study purposes. The content is shared publicly to promote open knowledge and may be reused, referenced, or extended by others with appropriate credit. 

Contributions, feedback, and collaborations are welcome!