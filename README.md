# Experiment 10: Creating Dataset and Loading Dataset

## 📌 Objective

The objective of this experiment is to understand how to create a dataset and load it into a program for analysis using Python.

---

## 🧰 Tools & Technologies Used

* Python 3.x
* Pandas Library
* NumPy Library
* CSV Dataset

---

## 📂 Project Structure

```
experiment-10-dataset-loading/
│
├── dataset/
│   └── sample_dataset.csv
│
├── src/
│   └── load_dataset.py
│
├── notebook/
│   └── experiment10_dataset.ipynb
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Description

The dataset contains basic student information used for demonstrating dataset creation and loading.

| ID | Name  | Age | Marks |
| -- | ----- | --- | ----- |
| 1  | Amit  | 20  | 85    |
| 2  | Riya  | 21  | 90    |
| 3  | Arjun | 19  | 78    |
| 4  | Neha  | 22  | 88    |
| 5  | Karan | 20  | 76    |

The dataset is stored in **CSV (Comma-Separated Values) format**, which is widely used for
## ⚙️ Steps Performed

Created a dataset in CSV format.

Stored the dataset in the project directory.

Used the Pandas library to load the dataset.

Displayed the dataset using Python.

Retrieved dataset information and summary statistics.

## 💻 Sample Python Code
import pandas as pd

# Load dataset
data = pd.read_csv('dataset/sample_dataset.csv')

# Display dataset
print("Dataset Loaded Successfully:\n")
print(data)

# Display dataset information
print("\nDataset Info:")
print(data.info())

# Display statistical summary
print("\nStatistical Summary:")
print(data.describe())
## ▶️ How to Run the Project

Clone the repository

git clone https://github.com/yourusername/experiment-10-dataset-loading.git

Navigate to the project folder

cd experiment-10-dataset-loading

Install required libraries

pip install -r requirements.txt

Run the Python script

python src/load_dataset.py
## 📈 Expected Output

Dataset successfully loaded

Display of dataset records

Dataset information including data types and memory usage

Statistical summary such as mean, count, minimum, and maximum values

## 📚 Learning Outcome

After completing this experiment, we learned:

How to create a dataset in CSV format

How to load datasets using Pandas

How to analyze dataset structure and statistics

Basic data handling in Python
