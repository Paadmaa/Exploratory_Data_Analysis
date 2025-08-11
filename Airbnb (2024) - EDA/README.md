# 🏙️ Airbnb Listings EDA – New York City 2024

![NYC Skyline](https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024/blob/main/New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2.jpg)

## 📌 Overview
This project dives into **Exploratory Data Analysis (EDA)** of Airbnb listings in New York City using Python libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The goal is to uncover patterns in pricing, availability, and host behavior to help both guests and hosts make smarter decisions.

---

## 🎯 Objectives
- Analyze **room types, pricing**, and **availability** across NYC boroughs  
- Understand **host behavior** and listing trends  
- Detect **outliers** in pricing  
- Provide **actionable recommendations** for guests and hosts  

---

## 📊 Dataset Summary
The dataset contains **20,765 listings** with **22 features**, including:

| Feature               | Description                                      |
|----------------------|--------------------------------------------------|
| `id`                 | Unique listing ID                                |
| `name`               | Listing title                                    |
| `host_name`          | Host’s name                                      |
| `neighborhood_group`| Borough (e.g., Manhattan, Brooklyn)              |
| `latitude/longitude`| Geolocation of listing                           |
| `price`              | Nightly rental price                             |
| `room_type`          | Type of accommodation                           |
| `reviews_per_month` | Avg. monthly reviews                             |
| `availability_365`  | Days available per year                          |

---

## 🛠️ Workflow

### 1. 🔍 Data Cleaning
- Handled missing values in `price`, `neighborhood`, and `beds`  
- Converted `last_review` to datetime format  
- Capped extreme prices (> $1,000) to reduce skew  

### 2. 📈 Exploratory Analysis
- **Room Types**: Bar plots show "Entire home/apt" is most common  
- **Neighborhoods**: Manhattan has highest average prices  
- **Availability**: Heatmaps reveal correlations with reviews and price  
- **Price Distribution**: Most listings fall between $50–$300  
- **Host Listings**: Boxplots highlight multi-listing hosts  
- **Review Behavior**: Pair plots show relationships among key metrics  

### 3. 📊 Visualizations
- **Pairplots**: Explore relationships between price, reviews, and availability  
- **Heatmaps**: Correlation matrix of numerical features  
- **Histograms & Boxplots**: Detect price outliers  
- **Bar Charts**: Compare room types and borough distributions  

---

## 🔍 Key Insights

| Insight | Summary |
|--------|---------|
| 💰 Price Trends | Manhattan is most expensive; Brooklyn offers budget options |
| 🏠 Room Types | Entire homes dominate, but private rooms are more affordable |
| ⚠️ Outliers | Listings priced above $10,000 were filtered out |
| 📅 Availability | High availability correlates with lower prices and more reviews |
| 👥 Host Behavior | Some hosts manage multiple listings—professional hosting trend |

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/Paadmaa/Exploratory_Data_Analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Launch the notebook
jupyter notebook day23_airbnb_eda.ipynb
```

---

## 💡 Recommendations

### For Guests:
- Choose listings with high availability and strong reviews  
- Consider **private rooms in Brooklyn** for budget-friendly stays  

### For Hosts:
- Increase availability and responsiveness to boost reviews  
- Optimize pricing to stay competitive within borough markets  

---

## 🔮 Future Enhancements
- Apply **machine learning** to predict prices  
- Perform **sentiment analysis** on guest reviews  
- Build an **interactive dashboard** using Plotly or Tableau  

---

## ✅ Conclusion
This EDA project reveals valuable insights into NYC’s Airbnb market. From pricing trends to host strategies, the findings help both guests and hosts make informed decisions. Future work can expand into predictive modeling and real-time analytics.

---

## 📄 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to fork, modify, and build upon it.

---

## 📬 Contact
- GitHub: [Paadmaa](https://github.com/Paadmaa)  
- LinkedIn: [Padma Ch. Behera](https://www.linkedin.com/in/padmach-behera/)  

---

Let me know when you're ready to optimize the next one! I can also help you turn these into LinkedIn posts or portfolio highlights if you'd like.
