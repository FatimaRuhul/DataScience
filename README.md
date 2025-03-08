
### **📌 Data Science - Customer Segmentation**  
📂 **Repository Name:** `FatimaRuhul - DataScience`  
👩‍💻 **Author:** Ruhul Fatima Abdi  
📅 **Last Updated:** 01/02/2025 


## **📌 Overview**
I implemented **Customer Segmentation** using **K-Means Clustering**. The project includes **Exploratory Data Analysis (EDA)**, **Lookalike Modeling**, and **Clustering Optimization**.

The dataset contains customer transactions and product details, and the analysis aims to provide **business insights** by segmenting customers based on their purchasing behavior.


## **📌 Project Structure**
```
📦 DataScience
 ┣ 📜 Customers.csv                        # Customer dataset
 ┣ 📜 Products.csv                         # Product dataset
 ┣ 📜 Transactions.csv                     # Transaction dataset
 ┣ 📜 Data Science Intern _ Assignment.pdf # Assignment instructions
 ┣ 📜 README.md                            # Project documentation
 ┣ 📜 Ruhul_Abdi_EDA.ipynb                 # Exploratory Data Analysis (EDA)
 ┣ 📜 Ruhul_Abdi_EDA.pdf                   # EDA Report
 ┣ 📜 Ruhul_Abdi_Lookalike.ipynb           # Lookalike Modeling Notebook
 ┣ 📜 Ruhul_Abdi_Lookalike.csv             # Lookalike Model Results
 ┣ 📜 Ruhul_Abdi_Clustering.ipynb          # Customer Segmentation Notebook
 ┣ 📜 Ruhul_Abdi_Clustering.csv            # Clustered Customer Data
 ┣ 📜 Ruhul_Abdi_Clustering.pdf            # Clustering Report
 ┣ 📜 Ruhul_Abdi_Optimized_Clustering.csv  # Optimized Cluster Assignments
```


## **📌 Key Tasks & Methods**
### **1️⃣ Exploratory Data Analysis (EDA)**
- **Dataset Inspection:** Checked missing values, distributions, and outliers.
- **Feature Engineering:** Created new features for better segmentation.
- **Visualization:** Used **Matplotlib & Seaborn** to analyze trends.

### **2️⃣ Lookalike Modeling**
- Built a **lookalike model** to identify potential high-value customers.
- Applied **scaling & transformation** to improve model performance.

### **3️⃣ Customer Segmentation (K-Means Clustering)**
- **Cluster Optimization:** Tested **K values (2-10)** to find the best segmentation.
- **Metrics Used:**  
  ✅ **Davies-Bouldin Index (DBI)** *(Lower = Better)*  
  ✅ **Silhouette Score** *(Higher = Better)*  
  ✅ **Calinski-Harabasz Index** *(Higher = Better)*  
- **Final Selection:** `K=2` was the best choice with **DBI = 0.734**.


## **📌 Results & Business Insights**
- **Segment 1:** Low-spending, infrequent customers → **Needs engagement strategies**.
- **Segment 2:** High-spending, frequent customers → **VIP customers, need retention plans**.
- **Actionable Insights:** Discounts, loyalty programs, and personalized marketing.



## **📌 Tools & Technologies**
- **Programming Language:** Python 🐍
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
- **Environment:** Jupyter Notebook (`.ipynb`)



## **📌 How to Use**
1. Clone this repository:  
   ```
   git clone https://github.com/FatimaRuhul/DataScience.git
   cd DataScience
   ```
2. Open Jupyter Notebook and run:
   ```
   jupyter notebook
   ```
3. Open `Ruhul_Abdi_Clustering.ipynb` and execute the cells to analyze customer segments.



## **📌 Contact**
For any queries, feel free to reach out:  
📩 Email: **[ruhulabdi123@gmail.com]**  
📌 LinkedIn: **[https://www.linkedin.com/in/ruhul-fatima-abdi-7694481b6]**

