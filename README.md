
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

### 🔍 Visual Components

- **Restaurant Category Breakdown**  
  Horizontal bar chart showing customer distribution across categories like Delivery, Dine-out, Cafes, Desserts, etc.

- **Variation in Prices**  
  Dual bar chart comparing Max and Min cost per person across restaurant types.

- **No. of Online Orders**  
  Pie chart illustrating how many restaurants accept online orders.

- **Top Rated vs Most Rated Restaurants**  
  Scatter plot comparing restaurants by average rating and number of votes, color-coded by rating quality (Excellent/Good). Highlights popular names like Truffles, Byg Brewski, The Black Pearl, etc.

- **KPI Summary Panel**  
  Metrics displayed at the top with filters for **Cuisine** and **Location**.

## 📌 Objectives

- Clean and preprocess raw Zomato data.
- Identify trends in customer preferences and restaurant services.
- Analyze cost variation across different types of restaurants.
- Visualize key insights using Tableau.

## 🧪 Technologies Used

- **Python (Pandas, NumPy)**
- **Jupyter Notebook**
- **Tableau**
- **CSV (for data input)**

## 📌 Key Insights

- **Delivery** services are most preferred, with over 25,000 customer records.
- **Dine-out**, **Desserts**, and **Cafes** are also widely chosen options.
- **Buffet** and **Drinks & Nightlife** tend to have the highest maximum cost per person.
- Most customers prefer restaurants that offer **online ordering**.
- Restaurants like **Truffles**, **The Black Pearl**, and **Byg Brewski Brewing Company** rank high in both ratings and total votes.

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
