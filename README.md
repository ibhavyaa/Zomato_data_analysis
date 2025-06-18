
# 🍽️ Zomato Restaurant Data Analysis

This project is an end-to-end data analysis of restaurant data from Zomato. It includes data cleaning, exploratory data analysis (EDA), and an interactive dashboard created in Tableau. The goal is to gain actionable insights into restaurant trends, customer preferences, and pricing variations.

## 📁 Project Structure

```
Zomato-Data-Analysis/
│
├── ZomatoDataCleaning.ipynb        # Jupyter Notebook for data cleaning and EDA
├── zomatoanalysis.twbx             # Tableau dashboard
└── README.md                       # Project documentation
```

## 📊 Dashboard Overview

The Tableau dashboard includes:
- **Total Restaurants Analyzed**: 8,705
- **Average Rating**: 4.0
- **Total Votes**: 14,544,458
- **Total Table Booking Restaurants**: 6,422

### Key Visuals:
- **Restaurant Category Breakdown**: Count of customers by restaurant type (e.g., Delivery, Dine-out).
- **Variation in Prices**: Max & Min cost per person by restaurant type.
- **Number of Online Orders**: Pie chart showing online ordering distribution.
- **Best Rated Restaurants**: Top restaurants based on user ratings.
- **Most Rated Restaurants**: Restaurants with the highest number of votes.

## 📌 Objectives

- Clean and preprocess raw Zomato data.
- Identify trends in customer preferences and restaurant services.
- Analyze cost variation across different types of restaurants.
- Visualize key insights using Tableau.

## 🧪 Technologies Used

- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Jupyter Notebook**
- **Tableau**
- **CSV (for data input)**

## 🔍 Key Insights from EDA

- **Delivery** services dominate with over 25K customer entries.
- **Dine-out** is the second most popular, followed by **Desserts** and **Cafes**.
- **Buffets** and **Drinks & Nightlife** are costlier per person on average.
- A high number of customers prefer restaurants that accept **online orders**.
- **Asia Kitchen By Mainland China** and **Byg Brewski Brewing Company** are among the highest-rated.
- **Onesta**, **Truffles**, and **Empire Restaurant** are the most voted restaurants.

## 📂 How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ibhavyaa/Zomato_data_analysis.git
   cd Zomato_data_analysis
   ```

2. **Run the Notebook**
   - Open `ZomatoDataCleaning.ipynb` using Jupyter Notebook or JupyterLab.
   - Execute each cell to reproduce the data cleaning and EDA.

3. **View the Dashboard**
   - Open the Tableau dashboard from the `zomatoanalysis.twbx` file.

## 📌 Next Steps (Optional)

- Deploy Tableau dashboard to Tableau Public for wider accessibility.
- Add interactive filters for city-wise or cuisine-based analysis.
- Perform machine learning tasks like restaurant rating prediction.

## 📬 Contact

For any questions or feedback, feel free to reach out:

- **Name**: Bhavya Agarwal
- **Email**: bhavya1547@gmail.com
