# Health Monitoring System using Machine Learning 🩺📊

This project is a **health condition prediction system** that uses Machine Learning to classify a patient's health status into categories like **Low**, **Medium**, or **High** risk. It leverages physiological data such as **ECG**, **Temperature**, **Pressure**, and **Patient ID** — typically collected using IoT devices.

---

## 🔧 Project Modules

The system is divided into **five core modules**:

### 1. 📥 Dataset Collection
- Patient data is collected using IoT devices.
- Features include:
  - ECG Data
  - Temperature Data
  - Pressure Data
  - Patient ID
- Stored in a structured `.csv` format.

### 2. 🧹 Dataset Preprocessing
- Raw data is cleaned and formatted for model training.
- Missing values handled, data types corrected, and normalization applied.

### 3. 📊 Data Visualization
- Exploratory Data Analysis (EDA) is performed using:
  - Bar Charts
  - Correlation Matrix
  - Histogram Plots
  - Kernel Density Estimation (KDE) plots

### 4. 🤖 Model Implementation
- Machine learning models used:
  - Logistic Regression
  - Naive Bayes
  - Decision Tree
  - Support Vector Machine (SVM)
- Models are trained and evaluated on the processed dataset.

### 5. ✅ Classification and Prediction
- Accuracy scores for each model are displayed.
- Evaluation metrics include:
  - Classification Report (Precision, Recall, F1 Score, Support)
  - Confusion Matrix
  - Performance comparison via graphs
- The system accepts user input as an array and predicts the health condition.

---

## 📁 Files in the Repository

- `IotFile.ipynb` — Jupyter notebook containing the entire implementation
- `dataset.csv` — Collected dataset used for training/testing
- `README.md` — Project overview and documentation

---

## 💡 Future Improvements
- Real-time prediction using live IoT sensor input
- Deploy as a web or mobile application
- Integration with cloud services for remote monitoring

---

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Ishikasrivas/health-monitoring-system.git
