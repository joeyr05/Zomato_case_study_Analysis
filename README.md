# Zomato Case Study Analysis

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

| Column Name                    | Data Type |
|-------------------------------|-----------|
| index                         | int64     |
| url                           | object    |
| address                       | object    |
| name                          | object    |
| online_order                  | object    |
| book_table                    | object    |
| rate                          | float64   |
| votes                         | int64     |
| phone                         | object    |
| location                      | object    |
| rest_type                     | object    |
| dish_liked                    | object    |
| cuisines                      | object    |
| approx_cost(for two people)   | object    |
| reviews_list                  | object    |
| menu_item                     | object    |
| listed_in(type)               | object    |
| listed_in(city)               | object    |

## Executive Summary

**This project explores Zomato data to uncover key insights:**

A strong link between online orders and customer ratings

![rating vs online order](C:\~LOCAL DISK D\PORTFOLIO PROJECTS\Zomato Case Study\rating_vs_online_order.png)

Valuable patterns in user reviews through bigram, and trigram analysis 

![bigram analysis](C:\~LOCAL DISK D\PORTFOLIO PROJECTS\Zomato Case Study\bigram_analysis.png)

![trigram analysis](C:\~LOCAL DISK D\PORTFOLIO PROJECTS\Zomato Case Study\trigram_analysis.png)

High-demand restaurant zones identified via geospatial heatmapping.

![geo location](C:\~LOCAL DISK D\PORTFOLIO PROJECTS\Zomato Case Study\geospatial_data.png)
