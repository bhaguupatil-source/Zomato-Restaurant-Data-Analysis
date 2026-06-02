Zomato-Restaurant-Data-Analysis
# Zomato-Restaurant-Data-Analysis
🍽️ Zomato Restaurant Data Analysis
This repository contains an exploratory data analysis (EDA) of a cleaned Zomato dataset. 
The analysis aims to uncover valuable insights into restaurant types, cuisines, ratings, 
pricing, and geographic distribution, particularly focusing on Indian cities.

📌 Project Objective
The goal of this project is to perform a comprehensive analysis of Zomato restaurant data 
using Python. This includes visualizing key metrics and trends such as:
  - Distribution of restaurant types
  - Most popular cuisines
  - Price range and cost for two people
  - Online delivery trends
  - Ratings and reviews
  - City-wise restaurant availability and performance

🗂️ Dataset Information
  - Dataset Name: Clean Zomato Data.csv
  - Source: Zomato public data (cleaned and preprocessed)
  - Total Records: ~5,550+
  - Key Features:
    - Restaurant Name
    - Cuisines
    - Location
    - Average Cost for two
    - Price range
    - Has Table booking, Has Online delivery
    - Aggregate rating, Rating text, Votes
    - Country, City
  
🧪 Tools & Technologies Used
 - Language: Python
 - Libraries:
   - pandas, numpy – Data manipulation and analysis
   - matplotlib, seaborn – Data visualization
   - plotly – Interactive visualizations
   - missingno – Missing value analysis
   - wordcloud – Text-based visual insights
 - Platform: Jupyter Notebook / Google Colab

📊 Exploratory Data Analysis Highlights
✅ Data Cleaning
 - Removed duplicate and null entries
 - Standardized categorical values
 - Mapped country codes to actual country names
 - Removed irrelevant columns

📍 City & Country Insights
 - Identified cities and countries with the highest number of restaurants.
 - Found that most restaurants are located in Indian cities like Bangalore, Delhi,
    and Mumbai.
    
🍽️ Cuisines & Restaurant Types
 - North Indian, Chinese, and Fast Food are the most common cuisines.
 - Quick Bites and Casual Dining are the most popular restaurant types.

⭐ Rating & Pricing
 - Most restaurants have ratings between 3.0 to 4.5.
 - Price ranges show a strong preference for affordable dining.
 - Compared the cost for two people across various cities.

🚚 Online Delivery & Booking
 - Analyzed which cities have the most restaurants offering online delivery
   and table booking.
 - Correlation analysis between rating and delivery/booking options.

📌 Key Insights
- India is the dominant country in the dataset, with the highest restaurant density.
- Cities like New Delhi and Bangalore offer the most diverse food options.
- Majority of restaurants don't offer table booking but do support online delivery.
- There is a positive correlation between higher ratings and restaurants that
  offer delivery and booking options.
- Cost-effective restaurants receive more customer engagement.

📁 Repository Structure

            Zomato-EDA/
          │
          ├── Clean Zomato Data.csv          # Cleaned dataset used for analysis
          ├── Zomato (1).ipynb               # Jupyter Notebook with full analysis and visualizations
          ├── README.md                      # Project documentation

📌 Future Work
- Build a Power BI dashboard using the same dataset for business reporting
- Perform sentiment analysis on customer reviews (if review data is available)
- Create a recommendation system for restaurant discovery

🚀 How to Run
  1. Clone this repository:
     
         https://github.com/Vaishnavi-76304/Zomato-Restaurant-Data-Analysis.git
     
  3. Open the Jupyter Notebook or upload it to Google Colab.
  4. Run the cells sequentially to see the visualizations and insights.






