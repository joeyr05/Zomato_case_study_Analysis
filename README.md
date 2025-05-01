z# Zomato Case Study Analysis
## Project Overview

Zomato is a global restaurant aggregator and food delivery service that connects users with a variety of dining options through an intuitive platform. It offers services like restaurant discovery, online ordering, and customer reviews, making it a go-to app for food lovers across cities.
From a managerial perspective, Zomato focuses on enhancing customer experience, optimizing restaurant partnerships, and leveraging data to drive business decisions. Its emphasis on user feedback, timely delivery, and regional engagement helps guide its strategic planning and operational efficiency.

**Insights Gained:**

**Sales Insights:** Analyzed the relationship between online order frequency and restaurant ratings. Findings showed that higher-rated restaurants generally saw more online orders, although some lower-rated venues still attracted significant sales due to pricing or location advantages.

**Text Analysis:** Conducted unigram, bigram, and trigram analysis on user reviews. This revealed common customer sentiments and preferences, such as frequently mentioned dishes, service quality indicators, and recurring complaints, providing actionable feedback for restaurant improvements.

**Geographical Heatmap:** Developed an automated heatmap to visualize restaurant locations and popularity across regions. This enabled the identification of high-demand areas and underserved zones, assisting in strategic expansion and targeted marketing.

## Project Background
This project focuses on analyzing restaurant data from Zomato to uncover key business insights and provide actionable recommendations. Using data-driven methods, the aim was to explore customer behavior, restaurant performance, and regional food trends to support strategic decision-making.

**Introduction to Zomato:**

Zomato is a popular food delivery and restaurant discovery platform operating across multiple countries. It helps users find restaurants, read reviews, order food online, and explore trending dining spots, making it a vital player in the food-tech industry.

**Insights and Recommendations:**

**Sales & Ratings:** Found a positive correlation between high customer ratings and online order volumes, suggesting that maintaining quality service and food can directly boost sales.

**Text Analysis:** Unigram, bigram, and trigram analysis of reviews highlighted frequent keywords related to food quality, service, and ambiance. This can guide restaurants on what customers value most or need improvement.

**Geographical Insights:** Automated heatmaps revealed clusters of high restaurant density and user activity, helping identify profitable locations and areas for expansion.

**Tools and Techniques:**

Python was used extensively for data cleaning **(Pandas, NumPy)**, text analysis **(NLTK)**, and generating geographical heatmaps **(Folium)**. These tools allowed for effective preprocessing, sentiment extraction, and visualization of spatial trends.

## Data Structure and Data types

    Column                       Non-Null Count  Dtype   
 0   index                        51672 non-null  int64  
 1   url                          51672 non-null  object 
 2   address                      51672 non-null  object 
 3   name                         51672 non-null  object 
 4   online_order                 51672 non-null  object 
 5   book_table                   51672 non-null  object 
 6   rate                         41654 non-null  float64
 7   votes                        51672 non-null  int64  
 8   phone                        50493 non-null  object 
 9   location                     51672 non-null  object 
 10  rest_type                    51466 non-null  object 
 11  dish_liked                   23639 non-null  object 
 12  cuisines                     51672 non-null  object 
 13  approx_cost(for two people)  51352 non-null  object 
 14  reviews_list                 51672 non-null  object 
 15  menu_item                    51672 non-null  object 
 16  listed_in(type)              51672 non-null  object 
 17  listed_in(city)              51672 non-null  object 

