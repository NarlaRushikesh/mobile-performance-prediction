# 📱 Mobile Performance Prediction

## 🔍 Project Overview
This machine learning project aims to predict the **Total Benchmark Score** of smartphones based on their hardware specifications. The benchmark score is an important metric that reflects the performance of a device, which can be useful for comparisons, analytics, or filling in missing benchmark data.

We use a regression-based approach with `Linear Regression` as a baseline model. The project covers data preprocessing, model training, evaluation, and insights into the features impacting mobile performance.

---

## 📦 Dataset

The dataset contains information about various smartphone models, including specifications and performance scores of individual components.

### ✅ Dataset File:
- `mobile_benchmark_dataset.csv`

### 🔑 Feature Descriptions:

| Feature        | Description                                 |
|----------------|---------------------------------------------|
| `Phone Name`   | The name of the phone model                 |
| `RAM (GB)`     | RAM size in gigabytes                       |
| `Storage (GB)` | Internal storage capacity in gigabytes      |
| `Chipset`      | System-on-Chip (SoC) used in the device     |
| `GPU`          | Graphics Processing Unit model              |
| `CPU Score`    | Benchmark score for CPU performance         |
| `GPU Score`    | Benchmark score for GPU performance         |
| `MEM Score`    | Memory performance score                    |
| `UX Score`     | User experience performance score           |
| `Total Score`  | **Target variable** – overall benchmark score |

---

## 🧱 Project Structure


### Folder/File Descriptions:

- **Mobile_Performance_Prediction.ipynb** – The core Jupyter Notebook including data loading, preprocessing, model training, and evaluation.
- **mobile_benchmark_dataset.csv** – The dataset used for training and evaluation.
- **README.md** – Detailed description of the project, setup, and usage.
- **requirements.txt** – A list of Python packages needed to run the notebook (can be generated with `pip freeze`).

---

