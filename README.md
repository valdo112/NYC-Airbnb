NYC Airbnb Market Analysis
🔍 Project Overview

This project explores the New York City Airbnb Open Dataset to identify key factors influencing listing prices and market dynamics.
The analysis is designed from a Business Intelligence perspective, focusing on actionable insights rather than purely statistical exploration.

The goal is to answer:

What drives Airbnb prices in NYC?

How do prices differ across locations and room types?

What strategic insights can be derived for hosts entering the market?

🎯 Objectives

Analyze Airbnb price distribution and handle extreme outliers responsibly

Compare pricing across NYC boroughs

Examine how room types impact pricing

Translate analytical findings into business insights and recommendations

🗂 Dataset

Source: NYC Airbnb Open Data (Kaggle)

Records: ~49,000 listings

Key Features Used:

price

neighbourhood_group

room_type

minimum_nights

availability_365

number_of_reviews

reviews_per_month

🧹 Data Preparation

Key preprocessing steps:

Handled missing values in listing names, host names, and review-related fields

Preserved meaningful missing values (e.g. no reviews as a business signal)

Conducted targeted outlier analysis instead of blanket removal

Created a filtered dataset (price ≤ 1000) for pricing-related analysis while keeping the raw data intact

📈 Exploratory Data Analysis
1️⃣ Price Distribution

Airbnb prices in NYC are right-skewed, with most listings concentrated in the lower to mid-price range

Extreme values above $1,000 represent a small niche market and were excluded from core pricing analysis to avoid distortion

2️⃣ Price by Neighbourhood Group

Manhattan shows the highest median prices

Brooklyn offers lower prices with a large number of active listings

Bronx and Staten Island have the lowest median prices, indicating different demand and accessibility dynamics

3️⃣ Price by Room Type

Entire home/apt listings command the highest prices

Private rooms provide a more affordable alternative with strong market presence

Shared rooms represent a small and budget-focused segment

💡 Key Insights

The NYC Airbnb market is dominated by budget to mid-range listings, not luxury accommodations

Location plays a major role in pricing, with central and tourist-heavy areas commanding a premium

Brooklyn emerges as a strong value-for-money alternative to Manhattan

Entire home listings are priced significantly higher, while private rooms balance affordability and demand

📌 Business Recommendations

New Hosts:
Consider entering the market through private room listings in Brooklyn, which offer lower entry costs while maintaining strong demand.

Pricing Strategy:
Avoid competing in the luxury segment unless targeting a niche market. Competitive pricing within the mid-range is more aligned with typical market demand.

Room Type Optimization:
Hosts with spare rooms may benefit from listing private rooms instead of shared accommodations to achieve better pricing potential.

Market Positioning:
Manhattan listings should emphasize location and convenience to justify premium pricing, while outer borough listings should compete on value.

🛠 Tools & Technologies

Python (Pandas, NumPy)

Matplotlib

Jupyter Notebook
