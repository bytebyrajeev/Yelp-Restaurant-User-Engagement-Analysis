# 🍽️ Yelp Restaurant User Engagement Analysis

## 🧠 Project Overview
This project explores how **user engagement metrics** such as reviews, tips, and check-ins impact **restaurant success** on Yelp.  
By analyzing data from the Yelp dataset, the goal is to identify patterns and correlations between engagement activities and key success metrics like **ratings** and **review counts**.

The project provides data-driven insights to help restaurants enhance their visibility, reputation, and customer satisfaction.

---

## 🎯 Business Problem
In the competitive restaurant industry, understanding what drives user engagement and success is crucial.  
This analysis aims to answer:  
> How do reviews, check-ins, tips, and user sentiment correlate with restaurant ratings and business success?

---

## 🧾 Dataset Description
The dataset is a subset of the **Yelp Open Dataset**, containing information about restaurants across 8 metropolitan areas in the USA and Canada.  
The project utilizes data from five main JSON files:  
- `business.json`
- `review.json`
- `user.json`
- `tip.json`
- `checkin.json`

**Key Attributes:**
- Business information (name, city, state, stars, review count, categories)  
- User engagement (reviews, tips, check-ins, elite status)  
- Sentiment-related fields (useful, funny, cool votes)

---

## 🧩 Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy** – Data manipulation & aggregation  
- **Matplotlib**, **Seaborn** – Data visualization  
- **SQLite** – Database creation and data storage  
- **Statsmodels**, **Scikit-learn** – Statistical analysis & hypothesis testing  
- **Jupyter Notebook**

---

## 📈 Methodology

### 1. Data Preparation & Database Creation
- Imported multiple Yelp JSON files and stored them in a SQLite database for efficient querying.
- Filtered the dataset to include only restaurant-related businesses that are currently open.

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of ratings, reviews, and engagement metrics.
- Compared engagement patterns between **high-rated** and **low-rated** restaurants.

### 3. Correlation & Hypothesis Testing
- Quantified relationships between reviews, tips, and check-ins.
- Tested the hypothesis that higher engagement correlates with higher ratings and review counts.

### 4. Sentiment & User-Level Analysis
- Assessed how “useful,” “funny,” and “cool” review attributes relate to success metrics.
- Investigated the impact of **elite users** on restaurant visibility and engagement.

### 5. Temporal & City-Level Insights
- Identified busiest engagement hours and city-specific performance trends.
- Analyzed engagement consistency over time (trend & seasonality).

---

## 📊 Key Findings
- **Higher engagement = Higher success:** Restaurants with more reviews, tips, and check-ins tend to have higher ratings and visibility.  
- **Elite users drive influence:** Elite users, though fewer, contribute a disproportionate number of reviews, boosting visibility.  
- **Peak activity hours:** User engagement peaks between **4 PM – 1 AM**, suggesting when restaurants should focus promotions.  
- **Top cities:** Philadelphia, Tampa, Indianapolis, and Tucson show the highest overall restaurant success scores.  
- **Seasonality observed:** Engagement trends show periodic fluctuations, with early and late months of the year being most active.

---

## 💡 Business Insights & Recommendations
- Strengthen relationships with **elite users** through targeted engagement and loyalty initiatives.  
- **Optimize promotions and staffing** during peak hours (evenings and weekends).  
- Focus marketing strategies in **high-engagement cities** for expansion opportunities.  
- Encourage customers to leave **useful or funny reviews** to increase visibility.  
- Monitor sentiment trends to identify early indicators of customer satisfaction or dissatisfaction.

---

## 🧰 How to Run the Project

1. **Clone this repository**
   ```bash
   git clone https://github.com/bytebyrajeev/Yelp-Restaurant-User-Engagement-Analysis.git
   ```

2. **Navigate into the project folder**
   ```bash
   cd Yelp-Restaurant-User-Engagement-Analysis
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open Jupyter Notebooks**
   ```bash
   jupyter notebook
   ```
   - `Yelp_Data_Preparation_and_Database_Creation.ipynb` → for data setup  
   - `Yelp_User_Engagement_Analysis.ipynb` → for analysis and visualization  

---

## 📸 Example Visualizations
- Correlation Heatmap of Engagement Metrics  
- City-Wise Success Scores  
- Elite vs Non-Elite User Contribution  
- Hourly Engagement Patterns  
*(Add images in the `visuals/` folder and embed them here.)*

---

## 🚀 Skills Demonstrated
- Data Cleaning and Preparation  
- SQL and Database Management  
- Exploratory Data Analysis (EDA)  
- Statistical Hypothesis Testing  
- Sentiment and Engagement Analysis  
- Data Visualization and Storytelling  

---

## 🧾 Author
**Your Name**  
📧 rajeev108.tech@gmail.com  
🔗 www.linkedin.com/in/rajeev-tech1  
📂 https://github.com/bytebyrajeev

