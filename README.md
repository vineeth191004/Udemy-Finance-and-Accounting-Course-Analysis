## Finance & Accounting Courses Analysis on Udemy**

---

### 🧩 **Overview**

This project analyzes data from Udemy’s Finance & Accounting courses to uncover insights about course popularity, pricing, and ratings. It also builds a **machine learning model** to predict the number of subscribers based on various course attributes such as rating, reviews, and price.

---

### 📊 **Objectives**

* Perform exploratory data analysis (EDA) on Udemy course data
* Clean and preprocess raw data for consistency
* Visualize top courses by rating, subscribers, and discount
* Engineer new features like discount percentage and course category
* Train a regression model to predict **number of subscribers**

---

### ⚙️ **Technologies Used**

* **Python**
* **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Plotly**
* **Scikit-learn** (for ML)
* **Jupyter Notebook**

---

### 🧠 **Key Steps**

1. **Data Loading & Cleaning**

   * Removed unnecessary columns and handled missing values
   * Converted currencies and timestamps
   * Cleaned course titles

2. **Feature Engineering**

   * Added `Discount_Percentage` and `Category` features
   * Encoded categorical columns

3. **Exploratory Data Analysis (EDA)**

   * Visualized course ratings, prices, and discounts
   * Identified top 10 courses by rating and subscribers

4. **Model Building**

   * Used **Random Forest Regressor** to predict subscribers
   * Evaluated model with **MSE** and **R² score**

---

### 📈 **Results**

| Metric                 | Value       | Interpretation                           |
| ---------------------- | ----------- | ---------------------------------------- |
| **Mean Squared Error** | ~37,621,552 | Acceptable due to large subscriber range |
| **R² Score**           | 0.69        | Model explains ~69% of data variance     |

---

### 📂 **Output Files**

* `Cleaned_Finance_Udemy.csv` — cleaned dataset after preprocessing
* Visual plots — top-rated courses, top subscribers, discounts, etc.

