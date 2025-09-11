<div dir="ltr">

# California Housing Data Analysis

## 📌 Objective  ِ
Determine the most suitable housing option in California by analyzing key attributes such as:
- Median house value  
- Population size  
- Housing median age  
- Number of households  
- Average (estimated) number of rooms per house across regions   

---

## 📂 Dataset  
The dataset used is the *California Housing Prices* dataset, which contains detailed information about various regions in California and their respective housing statistics.

---

## 🧾 Attributes 
- longitude: Longitude of the location  
- latitude: Latitude of the location  
- housing_median_age: Median age of houses in the area  
- total_rooms: Total number of rooms in houses in the area  
- total_bedrooms: Total number of bedrooms in houses in the area  
- population: Number of people living in the area  
- households: Number of households in the area  
- median_income: Median income of households in the area  
- median_house_value: Median value of houses in the area  
- ocean_proximity: Proximity to the ocean (categorical variable)  

---

## ✅ What I Did  

- 🧹 *Loaded and cleaned* the dataset, including handling missing values logically (e.g., filling total_bedrooms nulls based on median values per region).  
- 🧽 *Removed inconsistent rows*, such as those where total_bedrooms > total_rooms.  
- 📊 *Analyzed key features* by calculating *median values per region* based on proximity to the ocean (ocean_proximity).  
- 💱 *Converted* median_income and median_house_value from *USD to Saudi Riyals (SAR)* to make the data more relevant for local financial analysis.  
- 📈 *Visualized* important metrics such as:
  - Median house values  
  - Population  
  - Housing age  
  - Average rooms per household  
  across different regions  
- 🔍 *Explored relationships* between features to extract actionable insights for making better housing decisions.  

---

## 💡 Inspiration  
This project was inspired by the need to better understand real estate dynamics in California using publicly available data. By converting financial figures to SAR and visualizing regional differences, this analysis can help individuals and investors—especially from regions like Saudi Arabia—make more informed decisions when evaluating housing markets abroad.

</div>
