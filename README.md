# 🛒 E-Commerce User Segmentation using K-Means Clustering

## 📌 Objective
To segment users based on their behavior in an e-commerce platform and identify meaningful customer groups for better business decision-making.

---

## 📊 Dataset
The dataset contains user activity logs with the following columns:
- user_id
- session_id
- timestamp
- event_type (click, purchase, login, etc.)
- amount
- outcome

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Cleaned and prepared raw event-based data
- Handled missing values

### 2. Feature Engineering
- Converted event-level data into user-level features using pivot table
- Aggregated user activities (clicks, purchases, etc.)
- Calculated total spending (amount) per user

### 3. Feature Scaling
- Applied StandardScaler to normalize features

### 4. Optimal Cluster Selection
- Used Elbow Method (WCSS) to determine optimal number of clusters

### 5. Model Building
- Applied K-Means clustering to segment users

### 6. Cluster Analysis
- Grouped users by cluster and analyzed average behavior

---

## 📈 Results & Insights

The model successfully segmented users into different behavioral groups:

- 🔵 High Value Users → High purchase frequency and high spending
- 🟡 Medium Users → Moderate activity and spending
- 🔴 Low Activity Users → Minimal interaction

These segments can help in:
- Targeted marketing
- Customer retention strategies
- Improving conversion rates

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🚀 Conclusion
K-Means clustering helped identify distinct user segments from raw behavioral data, enabling better understanding of customer patterns and supporting data-driven business decisions.
