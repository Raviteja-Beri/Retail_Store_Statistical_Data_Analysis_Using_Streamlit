# 🛍️ Retail Store Sales Data Analysis using Streamlit

This is an interactive web application built with **Streamlit** for performing statistical and visual analysis on retail store sales data. It allows users to gain insights into product performance, category trends, and conduct basic inferential statistics without writing code.

---

## 🚀 Features

- **Synthetic Data Generation**  
  Automatically generates sample retail sales data for 20 products across different categories (Electronics, Clothing, Home, Sports).

- **Interactive Data Display**  
  View and explore the sales dataset directly in the app.

- **Descriptive Statistics**  
  - Mean, Median, Mode
  - Summary statistics of units sold
  - Category-wise total, average, and standard deviation

- **Inferential Statistics**
  - 95% Confidence Interval for the mean units sold
  - One-sample t-test to compare sample mean against a benchmark value (20 units)

- **Data Visualizations**
  - Histogram with mean, median, and mode markers
  - Boxplot showing units sold by category
  - Bar chart of total units sold per category

---

## 📊 Technologies Used

- Python 3.x  
- [Streamlit](https://streamlit.io/)  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [SciPy](https://www.scipy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)

---

## 🖥️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Raviteja-Beri/Retail_Store_Statistical_Data_Analysis_Using_Streamlit.git
cd Retail_Store_Statistical_Data_Analysis_Using_Streamlit
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install manually:

```bash
pip install streamlit pandas numpy scipy matplotlib seaborn
```

### 3. Run the App
```bash
streamlit run app.py
```
### 🙌 Acknowledgments
Thanks to the open-source community and Streamlit for making data apps accessible and easy to build.
