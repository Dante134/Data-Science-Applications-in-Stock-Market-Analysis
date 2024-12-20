# Stock Market Analysis and Investment Strategies

This repository contains Python scripts for analyzing stock market data, including hypothesis testing, goodness-of-fit analysis, and investment strategy recommendations. The project utilizes data from ICICI Bank and Nifty indices over several financial years.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Scripts Overview](#scripts-overview)
6. [Requirements](#requirements)
7. [License](#license)

---

## Introduction

Stock market analysis is crucial for making informed investment decisions. This project uses statistical techniques to analyze historical stock data and provide insights into trends and potential strategies.

### Objectives:
- Conduct hypothesis testing (Chi-squared and KS tests) to understand data distribution and patterns.
- Recommend investment strategies based on turnover trends.
- Analyze opening and closing prices of stocks to derive actionable insights.

---

## Features

- **Chi-Squared Test**: Analyze categorical distributions of stock prices.
- **Kolmogorov-Smirnov Test**: Assess the goodness-of-fit of stock price distributions against standard models.
- **Investment Strategy Recommendation**: Generate suggestions based on average turnover trends.
- **Data Preprocessing**: Automated handling of multiple CSV files with data cleaning.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-analysis.git
   cd stock-analysis
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the data files are placed in the appropriate directory:
   - ICICI Bank Data: `/path/to/rtut/`
   - Nifty Data: `/path/to/nifty/`

---

## Usage

### Run Individual Scripts:
1. **Chi-Squared Test**:
   ```bash
   python chi-squared.py
   ```
2. **Kolmogorov-Smirnov Test**:
   ```bash
   python kstest.py
   ```
3. **Investment Strategy**:
   ```bash
   python invst.py
   ```

### Output:
- Each script prints results to the console.
- Statistical summaries and recommendations are displayed based on the analysis.

---

## Scripts Overview

### **1. Chi-Squared Test Script (`chi_squared_test.py`)**
- Performs chi-squared tests on ICICI Bank opening and closing prices.
- Identifies significant patterns in categorical distributions.
  
### **2. KS Test Script (`kstest.py`)**
- Compares opening and closing prices against standard distributions (`normal`, `lognormal`, etc.).
- Provides p-values and test statistics for each distribution.

### **3. Investment Strategy Script (`invst.py`)**
- Analyzes Nifty turnover data to recommend daily or monthly investment strategies.
- Calculates average turnover per day and month.

---

## Requirements

- Python 3.8 or later
- Required libraries:
  - `pandas`
  - `numpy`
  - `scipy`

### Example `requirements.txt`:
```plaintext
pandas>=1.3.0
numpy>=1.21.0
scipy>=1.7.0
```

---

## Data Files

Ensure you have the following CSV files in the `/path/to/rtut/` directory:

### ICICI Bank Data:
- `2018-2019_ICICI.csv`
- `2019-2020_ICICI.csv`
- `2020-2021_ICICI.csv`
- `2021-2022_ICICI.csv`
- `2022-2023_ICICI.csv`

### Nifty Data:
- `Nifty1.csv`
- `Nifty2.csv`
- `Nifty3.csv`
- `Nifty4.csv`
- `Nifty5.csv`

---

## Contributions

Contributions are welcome! Please follow these steps:
1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Feature description"
   ```
4. Push to your branch and open a pull request.

---

## Contact

For any queries or feedback, feel free to contact:
**Ayush Mishra**  
[GitHub Profile](https://github.com/yourusername)  
Email: [ayush.mishra@example.com](mailto:ayush.mishra@example.com)

---

Let me know if you'd like adjustments or additional sections!
