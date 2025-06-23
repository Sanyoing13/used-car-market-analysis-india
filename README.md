# 🚗 Used Car Market Analysis – India
This project explores a real-world dataset of used cars sold across various Indian cities, **offering a detailed analysis of pricing, features, and consumer preferences**. It includes **data cleaning, feature engineering, and exploratory data analysis (EDA)** to uncover key insights into the dynamics of both budget and luxury car segments. The insights generated can help dealerships, financial institutions, and online platforms make informed decisions based on trends in fuel type, transmission, brand preference, and ownership history.


## 📦 Dataset Description

The dataset provides extensive information on used vehicles, including:

- **Location**
- **Kilometers Driven**
- **Fuel Type**
- **Transmission**
- **Owner Type**
- **Mileage**
- **Engine Displacement**
- **Power Output**
- **Seating Capacity**
- **Ex-Showroom Price**
- **Car Brand**
- **Vehicle Age**


## 🧼 Data Preparation Workflow

1. **Handling Missing Values**: Strategically imputed missing data to preserve dataset integrity.
2. **Standardizing Units**: Normalized mileage values by converting `km/l` to `km/kg` wherever required.
3. **Brand Simplification**: Cleaned and shortened extended brand names for consistent classification.
4. **Outlier Detection & Removal**: Identified and excluded extreme values to ensure robust analysis.


## 🔍 Exploratory Data Analysis (EDA)

The EDA phase focused on uncovering underlying trends and relationships among variables:

- **Univariate & Bivariate Analysis**: Investigated feature distributions and their relationship with car pricing.
- **Correlation Mapping**: Analyzed how factors like engine size, mileage, and car age affect resale value.
- **Data Visualization**: Utilized bar charts, box plots, scatter plots, and heatmaps to support findings.
- **Market Segmentation**: Revealed clear demarcations between **budget** and **luxury** segments.


### 🧠 Market Segmentation: Budget vs. Luxury Cars

| 🔎 Aspect           |🚗 Budget Segment                       | 💼 Luxury Segment                         |
|-------------------  |--------------------------------------- |------------------------------------------|
| 🏙️ Top Cities       | Mumbai, Hyderabad, Pune                | Coimbatore, Mumbai, Kochi                 |
| ⛽ Fuel Type        | Petrol & Diesel dominate               | Mostly Diesel                             |
| ⚙️ Transmission     | Mostly Manual                          | Predominantly Automatic                   |
| 👤 Ownership        | Primarily First-owner                  | Higher share of Second-owner cars         |
| 🪑 Seating          | Mostly 5-seaters                       | 5-seaters hold stronger resale value      |
| 🏷️ Popular Brands   | Maruti, Hyundai, Honda                 | Mercedes, BMW, Audi, Toyota               |


## 📈 Insights & Observations

- The Indian used car market bifurcates into distinct **budget** and **luxury** categories.
- **Fuel type**, **transmission**, and **ownership history** significantly influence buyer behavior.
- **Sales volumes and brand preferences** vary widely by city, necessitating location-specific strategies.
- **Larger engines** tend to correlate with **lower mileage**, impacting long-term ownership costs.


## 👥 Stakeholder Value

This analysis holds actionable value for:

- **Used Car Dealerships**: Strategically manage stock based on city-level demand and segment-specific trends.
- **Online Auto Marketplaces**: Improve buyer personalization, dynamic pricing models, and ad targeting.
- **Banks & Lenders**: Build custom auto loan products aligned with buyer personas and risk profiles.


## 🔮 Next Steps

- Develop **Machine Learning models** for car price prediction and demand estimation.
- Integrate **Power BI/Tableau dashboards** for real-time insights.
- Expand analysis to include **regional trends, seasonal demand, and depreciation rates**.


## ⚙️ Tools & Technologies

- Python (Pandas, NumPy)
- Seaborn & Matplotlib (Data Visualization)
- Jupyter Notebook (Interactive Analysis)
- Git & GitHub (Version Control)


## 👩‍💻 Author

**Sanyogita Ingale**  
Aspirant in AI/ML and Data Science | Business & Market Analyst  
[GitHub Profile](https://github.com/sanyoing13)
