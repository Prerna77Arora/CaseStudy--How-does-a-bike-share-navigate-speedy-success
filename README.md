# CaseStudy--How-does-a-bike-share-navigate-speedy-success
# 🚴 Cyclistic Bike-Share Case Study

## 📌 Project Overview
This project is part of the Google Data Analytics Capstone. The goal is to **analyze how casual riders and annual members use Cyclistic bikes differently** and provide **data-driven recommendations** to increase annual memberships.

**Business Task:**  
> Determine how annual members and casual riders use Cyclistic bikes differently to help design a marketing strategy that converts casual riders into members.

**Tools Used:**  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook / Google Colab  
- Excel/Google Sheets (initial data check)  

---

## 📂 Project Workflow
The project follows the **Ask → Prepare → Process → Analyze → Share → Act** framework:

1. **Ask**  
   - Define the business task and key stakeholders.
2. **Prepare**  
   - Download 12 months of Divvy/Cyclistic bike trip data (CSV).  
   - Organize raw and cleaned data files.
3. **Process**  
   - Clean and combine 12 CSVs using Python (handle nulls, duplicates, invalid ride times).  
   - Create new columns: `ride_length` (minutes) and `day_of_week`.
4. **Analyze**  
   - Calculate ride frequency, average ride length, and weekly/monthly trends.  
   - Use groupby and pivot-table style summaries in Python.
5. **Share**  
   - Visualize insights using **Matplotlib** and **Seaborn**.  
   - Charts: Ride counts, Average ride length, Weekly trends, Monthly trends.
6. **Act**  
   - Generate 3 data-driven recommendations to increase membership conversions.

---

## 📊 Key Visualizations
The project includes the following visualizations:

1. **Number of Rides by User Type**  
2. **Average Ride Length by User Type**  
3. **Rides by Day of the Week (Members vs Casual)**  
4. **Average Ride Length by Day of the Week**  
5. **Monthly Ride Trends (Optional)**  

---

## 🔑 Key Findings
- **Casual riders** take **longer rides**, especially on **weekends**, suggesting leisure trips.  
- **Members** ride **shorter, more frequent trips**, mainly on **weekdays**, likely for commuting.  
- **Peak riding months** (summer) show a **significant increase in casual rider activity**, creating conversion opportunities.

---

## ✅ Top 3 Recommendations
1. **Target Weekend Leisure Riders with Membership Offers**  
   - Provide weekend or seasonal discounts to convert casual riders.  
   - Promote weekend perks like free extra minutes or first-hour free rides.

2. **Focus Marketing Campaigns During Peak Months**  
   - Launch seasonal ads and email campaigns during summer months.  
   - Offer limited-time membership discounts to capture high casual rider activity.

3. **Incentivize Short and Frequent Rides for Commuters**  
   - Introduce loyalty points or monthly rewards for frequent casual weekday riders.  
   - Highlight cost savings and convenience of annual memberships for commuters.

---

## 📂 Project Structure
```plaintext
Cyclistic_Case_Study/
│
├── Raw_Data/                # Original 12 monthly CSVs
├── Cleaned_Data/            # Cleaned dataset (combined CSV)
├── Visuals/                 # Saved visualization charts (PNG, PDF)
├── Cyclistic_Analysis.ipynb # Data cleaning & analysis notebook
├── Cyclistic_Visuals.ipynb  # Visualization notebook
└── README.md                # Project documentation




---

## 🏆 Outcome
By analyzing usage patterns and sharing actionable recommendations, this project provides a **data-backed marketing strategy** to convert **casual riders into annual members**, helping Cyclistic achieve long-term growth.

---
