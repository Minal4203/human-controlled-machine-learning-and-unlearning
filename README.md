# Human-Controlled Machine Learning with Learning and Unlearning Mechanisms

## Overview
This project demonstrates a **Human-in-the-Loop Machine Learning (HITL-ML)** system where humans can control the training behavior of a machine learning model. The system allows enabling or disabling learning during training and supports **machine unlearning**, where specific data points can be removed and the model can be retrained accordingly.

The goal is to show how **human oversight** can improve the reliability, transparency, and ethical behavior of machine learning systems.

---

## Key Features

### 1. Human-Controlled Learning
A toggle mechanism allows a human to:
- Enable model learning
- Disable model learning (freeze the model)

This ensures that the model only updates when human approval is given.

### 2. Machine Unlearning
The system includes a simulated **advanced unlearning mechanism** that removes influential samples from the training dataset and retrains the model.

This is useful in cases such as:
- Removing biased data
- Correcting harmful training samples
- Ensuring compliance with data privacy regulations.

### 3. Exploratory Data Analysis (EDA)
The project performs comprehensive data analysis including:

- Class distribution visualization
- Age vs income analysis
- Hours-per-week vs income
- Correlation heatmaps
- Gender vs income distribution
- Education level analysis

### 4. Model Training and Evaluation
The system uses **Random Forest Classification** to predict income levels based on census data.

Evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 5. Research Experiment Pipeline
The system performs multiple experiments:

1. Baseline Training
2. Training with Learning Disabled
3. Training with Learning Enabled
4. Machine Unlearning Experiment

Results are compared using performance visualizations.

---

## Dataset

The project uses the **UCI Adult Census Income Dataset**.

Dataset Source:
https://archive.ics.uci.edu/

This dataset predicts whether a person's income exceeds \$50K per year based on demographic and employment attributes.

Example features:
- Age
- Education
- Workclass
- Occupation
- Marital Status
- Hours per week
- Capital gain/loss

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Python Script

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Project

### Option 1: Run in Jupyter Notebook

```
jupyter notebook
```

Open:

```
human_controlled_ml.ipynb
```

### Option 2: Run as Python Script

```
python human_controlled_ml.py
```

---

## Experimental Results

The experiments demonstrate:

- Human control can **freeze model learning**
- Model performance changes when learning resumes
- Machine unlearning can remove influential data samples
- Performance metrics help evaluate the impact of these operations

Visualization includes:

- Performance comparison graphs
- Confusion matrices
- Feature importance charts
- Training progress plots

---

## Research Applications

Human-controlled machine learning can be useful in:

- AI governance
- Ethical AI systems
- Data privacy compliance (GDPR)
- Bias mitigation
- Explainable AI systems
- Safety-critical AI systems

---

## Future Improvements

Possible extensions for this project include:

- Real influence-function based unlearning
- Deep learning model integration
- Active learning with human feedback
- Reinforcement learning based human supervision
- Deployment using web interfaces

---

## Conclusion

This project demonstrates a **human-supervised machine learning pipeline** with the ability to control learning behavior and remove unwanted training data. It highlights the importance of **human oversight in modern AI systems** to improve transparency, fairness, and reliability.

---

## Author

Minal Agrawal  
B.Tech CSE (AI & ML)

---

