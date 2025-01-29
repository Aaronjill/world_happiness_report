---

## **📊 Dataset Overview**
The dataset contains information on **happiness scores across different countries worldwide** and their correlation with **economic, health, and social factors**.

## **🛠️ Technologies Used**
✅ Python 🐍  
✅ Pandas (for data manipulation)  
✅ Seaborn & Matplotlib (for visualization)  
✅ NumPy (for numerical operations)  
✅ Jupyter Notebook  

---

## **📊 Key Analysis & Insights**
### **📌 1. Data Cleaning & Preprocessing**
✔️ Handled **missing values** (used mean/median based on skewness).  
✔️ Fixed **string encoding issues (`\xa0`)** and trimmed unwanted spaces.  
✔️ Converted **non-numeric columns to numerical for correlation analysis**.

### **📌 2. Exploratory Data Analysis (EDA)**
✔️ **Descriptive statistics** using `.describe()`, `.info()`.  
✔️ **Checked correlation between happiness score & other factors**.  
✔️ **Identified data distribution & skewness** using histograms.

### **📌 3. Correlation Analysis**
✔️ Found that **GDP per capita (0.80)** and **Social Support (0.75)** are the **strongest predictors of happiness**.  
✔️ Discovered that **higher corruption (-0.40 correlation) lowers happiness levels**.  
✔️ **Freedom to make life choices (0.54 correlation) significantly impacts happiness**.

### **📌 4. Data Visualization**
📊 **Correlation Matrix Heatmap** – Showed strong relationships between variables.  
📉 **Scatter Plot (Happiness Score vs GDP per Capita)** – Showed a positive correlation.  
📈 **Box Plot** – Helped identify outliers in happiness scores.

---

## **📊 Visualizations**
### 📌 **Correlation Matrix Heatmap**
<img src="images/correlation_matrix.png" width="600">

### 📌 **Happiness Score vs GDP per Capita**
<img src="images/happiness_vs_gdp.png" width="600">

---

💡 **Next Steps:**  

- Exploring **interactive dashboards using Tableau/Plotly Dash** 📊.

- Applying **Machine Learning for Happiness Prediction** 🤖.

## **🚀 How to Run the Project**
### **🔹 1. Clone the Repository**
```bash
git clone https://github.com/yourusername/world_happiness_report.git
cd world_happiness_report
