
# Airbnb Seattle Data Analysis

## Project Overview
This project analyzes Airbnb listings, calendar data, and reviews from Seattle to uncover trends and insights that can aid stakeholders in making informed decisions. Using descriptive analysis, visualizations, and Python-based data wrangling, the project sheds light on key patterns in pricing, availability, and customer feedback.

### Key Questions Answered:
1. What factors influence the price of a listing?
2. Are there seasonal trends in Airbnb bookings?
3. How do customer reviews impact a listing's success?

### Insights:
- Larger properties (more bedrooms and accommodates capacity) are more expensive.
- Seasonal demand peaks lead to lower availability.
- Listings with more reviews generally have higher review scores, but exceptions exist.

---

### Repository Structure:
Here’s how the repository is organized:
. ├── .gitignore ├── Airbnb_Seattle_Analysis.ipynb # Jupyter Notebook with full analysis ├── README.md # Project README file ├── requirements.txt # Dependencies for the project ├── data/ # Contains raw and cleaned datasets │ ├── calendar.csv # Original calendar dataset │ ├── calendar_cleaned.csv # Cleaned calendar data │ ├── listings.csv # Original listings dataset │ ├── listings_cleaned.csv # Cleaned listings data │ ├── reviews.csv # Original reviews dataset │ ├── reviews_cleaned.csv # Cleaned reviews data ├── output/ # Output visualizations │ ├── Availability Over Time.png │ ├── Number of Reviews Over Time.png │ ├── output1.png │ ├── output2.png │ ├── output3.png │ ├── Price Distribution of Listings (After Outlier Removal).png │ ├── Price Distribution of Listings (Before Outlier Removal).png │ ├── Room Type Distribution.png
---

### Tools Used:
- **Python**:
  - pandas
  - numpy
  - matplotlib
  - seaborn

---

### Data Source:
The data used in this project is publicly available and was sourced from Kaggle:  
[Seattle Airbnb Data](https://www.kaggle.com/datasets/airbnb/seattle/data)

---

### Blog Post
For a non-technical summary of the findings, refer to the blog post:  
**[Unlocking Insights from Seattle's Airbnb Market: A Data-Driven Exploration](https://medium.com/@cw.smith_12977/unlocking-insights-from-seattles-airbnb-market-a-data-driven-exploration-8e5a1d496265)**