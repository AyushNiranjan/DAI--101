# **Car Price Analysis & Insights**

## **Project Overview**
This project aims to analyze a dataset of **10,000 used car listings** to identify key insights into pricing trends, mileage distribution, and other factors influencing car prices. The analysis includes **univariate, bivariate, and multivariate exploration**, with visualizations to support data-driven conclusions.

## **Dataset Description**
The dataset consists of **10 columns**, providing details on used cars, including:

| Column         | Description |
|---------------|-------------|
| **Brand**         | Car manufacturer (e.g., Ford, Kia, Audi) |
| **Model**         | Specific car model |
| **Year**          | Manufacturing year (2000 - 2023) |
| **Engine_Size**   | Engine capacity in liters (1.0 - 5.0) |
| **Fuel_Type**     | Type of fuel (Petrol, Diesel, Electric, Hybrid) |
| **Transmission**  | Gear type (Manual, Automatic, Semi-Automatic) |
| **Mileage**       | Distance traveled (range: 25 - 299,947 km) |
| **Doors**         | Number of doors (2 - 5) |
| **Owner_Count**   | Number of previous owners (1 - 5) |
| **Price**         | Selling price (range: $2,000 - $18,301) |

## **Data Analysis Steps**
1. **Univariate Analysis:**
   - Distribution of car prices, mileage, and engine sizes.
   - Identifying outliers and common trends.

2. **Bivariate & Multivariate Analysis:**
   - Relationship between price and key factors like mileage, year, and brand.
   - Correlation analysis to find the strongest price influencers.

3. **Data Visualization:**
   - Histograms, box plots, and scatter plots to showcase insights.
   - Price trends across brands and fuel types.

## **Results & Insights**
- Most used cars are **affordable (below $10,000)** and have **high mileage (~149,239 km)**.
- **Car price is right-skewed**, meaning a few high-end models significantly raise the upper price limit.
- Mileage and age have a **negative correlation** with price (older, high-mileage cars are cheaper).
- **Electric cars and premium brands** tend to have higher prices on average.

## **Technologies Used**
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** for data analysis & visualization.
- **Jupyter Notebook** for running and documenting analysis.
- **GitHub** for version control and project collaboration.

## **Next Steps**
- Perform **predictive modeling** (price prediction using regression models).
- Develop an **interactive dashboard** for better data visualization.
- Expand the dataset to include more car features (safety ratings, insurance costs, etc.).

## **How to Use This Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-price-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook for analysis.

## **Contributions & Contact**
Feel free to fork this repo, suggest improvements, or raise issues! You can reach out via GitHub or email.

---

