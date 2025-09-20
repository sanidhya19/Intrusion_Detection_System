# Intrusion Detection System

## Overview

This project implements an **Intrusion Detection System (IDS)** using machine learning techniques.  
It analyzes network traffic data to identify malicious activities or policy violations.  
The dataset used is the KDD’99 (or relevant) dataset.  

---

## Features

- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature selection & engineering  
- Model training & evaluation  
- Prediction of intrusions using trained models  
- Performance metrics: accuracy, precision, recall, F1-score  

---

## Included Files

- `IDS1.ipynb` — Jupyter notebook containing the full workflow: data processing, modeling, evaluation  
- `KDDTest+.csv` — Test dataset for evaluating model performance  

---

## Technologies Used

- Python  
- Jupyter Notebook  
- Popular ML libraries: scikit-learn, pandas, numpy, matplotlib / seaborn  

---

## Installation & Usage

### Prerequisites

- Python 3.x  
- pip or conda  

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/sanidhya19/Intrusion_Detection_System.git
cd Intrusion_Detection_System
```

2. **Create and Activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

3. **Run the notebook**

```bash
jupyter notebook IDS1.ipynb
```

Use the notebook to follow the pipeline: load data, preprocess, train models, evaluate.

---

## Evaluation

- Use the KDDTest+.csv dataset for testing
- Evaluate using metrics such as Accuracy, Precision, Recall, F1-Score
- Compare different ML algorithms (e.g. Decision Trees, Random Forests, SVM, etc.)


---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a new branch
```bash
git checkout -b feature-name
```

3. Make your changes.

4. Commit your changes

```bash
git commit -am 'Add new feature'
```

5. Push to the branch

```bash  
git push origin feature-name
```

6. Create a new Pull Request.

