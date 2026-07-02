# MLflow Basics – Experiment Tracking & Model Logging

This repository contains my hands-on practice projects while learning **MLflow**. The objective of these projects is to understand how MLflow helps manage the machine learning lifecycle by tracking experiments, logging parameters and metrics, storing models, and comparing different training runs.

## 📌 Projects Included

### 1. Machine Learning Model with MLflow

A basic machine learning workflow integrated with MLflow.

**Features**

* Data preprocessing
* Model training
* Parameter logging
* Metric logging
* Model logging
* Experiment tracking

**Concepts Covered**

* MLflow Tracking
* Logging parameters
* Logging metrics
* Logging trained models
* Viewing experiments using the MLflow UI

---

### 2. Deep Learning Model with MLflow

A simple deep learning project demonstrating how MLflow can be used with neural networks.

**Features**

* Deep learning model training
* Training metrics logging
* Hyperparameter tracking
* Model artifact storage
* Experiment comparison

**Concepts Covered**

* MLflow with Deep Learning
* Logging loss and accuracy
* Saving trained models
* Managing multiple experiment runs



---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### 2. Create a Virtual Environment

Using Conda:

```bash
conda create -n mlflow-env python=3.12
conda activate mlflow-env
```

Or using `venv`:

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run the desired training script:

```bash
python train.py
```

or execute the notebook if the project is notebook-based.

---

## 📊 Launch MLflow UI

```bash
mlflow ui
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

From the MLflow UI you can:

* View experiment runs
* Compare metrics
* Inspect logged parameters
* Download model artifacts
* Analyze experiment history

---

## 🛠 Technologies Used

* Python
* MLflow
* Scikit-learn
* TensorFlow / PyTorch (for Deep Learning)
* Pandas
* NumPy

---

## 📚 Learning Outcomes

Through these projects, I learned how to:

* Track machine learning experiments
* Log parameters, metrics, and artifacts
* Save and manage trained models
* Compare different experiment runs
* Integrate MLflow into both traditional ML and deep learning workflows

---

---

## 🤝 Contributions

This repository is primarily for learning purposes. Suggestions and improvements are always welcome.

---

## 📄 License

This project is intended for educational purposes.
