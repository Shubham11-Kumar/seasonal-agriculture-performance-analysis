# seasonal-agriculture-performance-analysis
Python-based agricultural data analysis project exploring crop productivity, seasonal performance, irrigation methods, environmental factors, resource utilization, profitability, and regional agricultural performance using Pandas, NumPy, Matplotlib and Seaborn.
# 🌾 Seasonal Agriculture Performance Analysis

A Python-based exploratory data analysis project focused on understanding agricultural productivity, production, resource utilization, environmental conditions, and economic performance across different crops, seasons, irrigation methods, states, and districts.

## 📌 Project Overview

Agricultural performance is influenced by multiple factors including seasonal conditions, farming practices, resource utilization, environmental variables, crop selection, and market conditions.

This project analyzes an agricultural dataset containing **4,000 records and 28 variables** to identify meaningful patterns and relationships in agricultural productivity and profitability.

The analysis was performed using Python and focuses on:

* Crop-wise performance
* Season-wise performance
* Irrigation methods
* Environmental factors
* Water usage and efficiency
* Fertilizer and seed quality
* Revenue and profitability
* Market prices
* State-wise performance
* District-wise performance
* Correlation analysis

## 🎯 Objectives

* Analyze agricultural productivity across different crops and seasons.
* Identify high-performing and low-performing crops.
* Compare irrigation methods based on average yield.
* Study relationships between production, yield, revenue, and resource usage.
* Analyze the effect of environmental and farming-related variables.
* Compare agricultural performance across states and districts.
* Identify important insights that can support data-driven agricultural decision-making.

## 📊 Dataset

The dataset contains **4,000 agricultural records and 28 variables**.

The variables cover areas such as:

* Farm characteristics
* Crop information
* Season
* State and district
* Rainfall
* Temperature
* Humidity
* Soil and farming factors
* Irrigation
* Fertilizer usage
* Seed quality
* Water usage
* Yield
* Production
* Market price
* Revenue
* Cost
* Profit
* Disease and pest risk

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔍 Analysis Performed

### 1. Seasonal Analysis

Agricultural performance was compared across Kharif, Rabi, and Zaid seasons.

Kharif recorded the highest average revenue and profit among the three seasons.

### 2. Crop-wise Analysis

Crop performance was analyzed using average yield, production, revenue, and profit.

**Sugarcane** recorded the highest average yield, production, and profit in the analyzed dataset.

* Average Yield: **46.64 tonnes/hectare**
* Average Production: **392.41 tonnes**
* Average Profit: **₹817,188**

### 3. Irrigation Analysis

Average yield was compared across irrigation methods.

| Irrigation Method |  Average Yield |
| ----------------- | -------------: |
| Drip              | 6.58 tonnes/ha |
| Sprinkler         | 5.16 tonnes/ha |
| Flood             | 4.86 tonnes/ha |
| Rainfed           | 4.60 tonnes/ha |

Drip irrigation recorded the highest average yield among the analyzed methods.

### 4. Economic Analysis

Kharif recorded the highest average revenue:

**₹710,719**

followed by:

* Rabi: **₹601,526**
* Zaid: **₹519,172**

### 5. Correlation Analysis

The relationship between important agricultural variables was studied using correlation analysis.

The strongest relationship identified was:

**Production vs Yield → 0.883**

Other important relationships include:

* Water Usage vs Production → **0.516**
* Production vs Revenue → **0.564**
* Market Price vs Revenue → **0.182**

Environmental variables such as rainfall, temperature, and humidity showed very weak linear relationships with yield in this dataset.

### 6. State-wise Analysis

State-level agricultural performance was compared using yield, production, revenue, and profit.

**Punjab** recorded the highest average yield and production among the analyzed states and also showed the highest average profit.

### 7. District-wise Analysis

District-level performance was analyzed to identify regional differences.

**Rajkot** recorded the highest average yield and production, while **Warangal** recorded the highest average revenue and profit among the analyzed districts.

## 📈 Key Findings

* 🌾 **Sugarcane** is the highest-performing crop in terms of average yield, production, and profit.
* 🌧️ **Kharif** shows the strongest overall seasonal economic performance.
* 💧 **Drip irrigation** has the highest average yield among the analyzed irrigation methods.
* 📊 **Production and yield** have a strong positive correlation of approximately **0.883**.
* 💰 Production has a moderate positive relationship with revenue.
* 🌦️ Rainfall, temperature, and humidity show very weak linear relationships with yield.
* 🗺️ Agricultural performance varies across states and districts.
* ⚠️ Some crops show negative average profitability and require further cost and revenue analysis.

## 💡 Recommendations

* Evaluate expansion opportunities for high-performing crops such as Sugarcane and Chilli where resource and economic conditions permit.
* Review production costs and profitability of crops showing negative average profit.
* Give greater attention to disease and pest management during Kharif.
* Consider both water consumption and water-use efficiency when planning agricultural activities.
* Use state-wise and district-wise analysis for region-specific agricultural planning.
* Extend the analysis using machine learning and advanced statistical techniques to identify non-linear relationships.

## 🚀 Future Scope

The project can be extended by:

* Developing crop yield prediction models.
* Building crop recommendation systems.
* Integrating real-time weather and market-price data.
* Creating interactive dashboards using Power BI.
* Applying regression and machine learning models.
* Developing region-specific agricultural decision-support systems.

## 📂 Project Structure

```text
seasonal-agriculture-performance-analysis/
│
├── notebook/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── dataset/
│   └── agriculture_dataset.csv
│
├── presentation/
│   └── Seasonal_Agriculture_Performance_Analysis.pptx
│
├── images/
│   └── project_visualizations
│
├── requirements.txt
└── README.md
```

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/seasonal-agriculture-performance-analysis.git
```

Open the project folder:

```bash
cd seasonal-agriculture-performance-analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook:

```text
notebook/Seasonal_Agriculture_Performance_Analysis.ipynb
```

## 📚 Project Files

* **Jupyter Notebook:** Complete Python analysis and visualizations
* **Dataset:** Agricultural dataset used for analysis
* **Presentation:** Project presentation
* **README:** Project documentation

## 👨‍💻 Author

**Shubham Kumar** 

Data Analytics | Python | SQL | Power BI | Data Visualization

---

⭐ If you find this project useful, consider giving the repository a star!
