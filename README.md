[![Owner](https://img.shields.io/badge/Owner-stoyanvalchev-emeraldgreen)](https://github.com/stoyanvalchev)
[![Owner](https://img.shields.io/badge/Owner-zarkobeats-emeraldgreen)](https://github.com/zarkobeats)

# Probabilistic Models in Sports Analytics

This project explores the application of **probabilistic graphical models**, specifically **Bayesian networks**, within the realm of **sports analytics**. Using real-world data, it demonstrates an end-to-end workflow for visualizing dependencies and making probabilistic predictions about sports team performance.

---

## 📌 Project Overview

The core of this project is a Jupyter notebook that walks through how to:

- 📥 Import and preprocess sports data
- 🔄 Construct and visualize a **Directed Acyclic Graph (DAG)** to represent variable relationships
- 🎯 Define target teams for performance prediction
- 🔍 Apply **Bayesian networks** to extract insights and forecast outcomes

---

## 📁 File Structure

```
.
├── bayesian_network.ipynb         # Main notebook demonstrating the model
├── requirements.txt               # Python dependencies
├── LICENSE                        # Project license
├── README.md                      # Project documentation
├── data_preparation/              # Notebooks for data cleaning and preparation
│   ├── join.ipynb
│   ├── matches.ipynb
│   └── teams.ipynb
└── new_data/                      # CSV files used in the project
    ├── database_matches.csv
    ├── database_teams.csv
    └── merged_matches.csv
```

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have **Python 3.7+** installed. Then set up the environment by installing the required dependencies:

```bash
pip install -r requirements.txt
```

### ▶️ Running the Notebook

To launch the notebook with predicted results. You can always change teams and dates to check:

```bash
jupyter notebook bayesian_network.ipynb
```

---

## 💡 Use Cases

This project is ideal for:

- 🧠 **Data scientists** exploring applications of probabilistic models in sports
- 🎓 **Academics or students** studying Bayesian networks
- 📊 **Analysts** looking to generate insights into sports team performance

---

## 📃 License

This project is licensed under the terms of the [LICENSE](./LICENSE) file.

---

## 📬 Contact

For questions or contributions, feel free to open an issue or submit a pull request.
