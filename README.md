# 🔍 Search Queries Anomaly Detection Using Python

This project focuses on detecting **anomalies** in **search query data** using unsupervised machine learning techniques — specifically the **Isolation Forest algorithm**.  
The goal is to automatically identify unusual patterns in search queries, such as sudden spikes or drops in clicks, impressions, CTR (click through ratio), or other metrics.

This project originally published by [The Clever Programmer](https://thecleverprogrammer.com/2023/11/20/search-queries-anomaly-detection-using-python/). All credits for the original idea and workflow go to them. This repository serves as my personal implementation and study.

---
## 📂 Project Structure

- `Search Queries Anomaly Detection using Python.ipynb`: Jupyter Notebook with full code.
- `data/`: Folder to hold your search query dataset (CSV or similar).
- `README.md`: Project overview and guide (this file).

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – for data manipulation
- **Matplotlib** and **Seaborn** – for data visualization
- **Scikit-learn** – for anomaly detection (Isolation Forest)
- **Regex** – for query cleaning and text processing

---

## 📈 Main Steps in the Project

1. **Load and Explore the Data**  
   - Search query dataset with fields like Clicks, Impressions, CTR, Average Position, etc.

2. **Text Cleaning**  
   - Preprocessing search queries using regular expressions.

3. **Feature Selection**  
   - Selecting numerical features relevant for anomaly detection.

4. **Anomaly Detection Model**  
   - Training an **Isolation Forest** model to learn the distribution of "normal" queries.

5. **Prediction and Analysis**  
   - Predicting anomalies and visualizing which queries are flagged as outliers.

6. **Visualization**  
   - Various plots to understand the distributions and anomalies (histograms, pie charts, etc.).

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/OyewoleRasheed/Search-Queries-Anomaly-Detection-using-Python.git
   cd Search-Queries-Anomaly-Detection-using-Python
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   *(Create a `requirements.txt` if you want; otherwise manually install: pandas, matplotlib, seaborn, scikit-learn.)*

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Follow the steps inside the notebook to see results!

---

## 📜 Acknowledgements

This project is based on the amazing tutorial [**Search Queries Anomaly Detection Using Python**](https://thecleverprogrammer.com/2023/11/20/search-queries-anomaly-detection-using-python/) by [The Clever Programmer](https://thecleverprogrammer.com/).  
All credit for the original approach and inspiration goes to them.
