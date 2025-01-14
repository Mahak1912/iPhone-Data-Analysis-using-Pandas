# iPhone Models Data Analysis

This repository contains a comprehensive analysis of an iPhone dataset, including data preprocessing, exploratory data analysis (EDA), and answering specific business questions. The code provides insights into various iPhone models, their ratings, discounts, reviews, and pricing strategies.

---

## Features

### Data Preprocessing
1. Renamed column names to replace spaces with underscores for better programmatic access.
2. Handled missing ratings:
   - Option 1: Filled with the average rating of all models.
   - Option 2: Filled with the average rating based on RAM configuration.
3. Added a new column `Discount_Percentage` to calculate the discount offered on each model.

### Analysis Questions Addressed
1. **Model with the Highest Percent Discount:** Identify which iPhone model has the maximum discount.
2. **Total Models by Storage Configuration:** Count models based on storage options (e.g., 128 GB, 64 GB).
3. **Total Models by Color:** Count models based on color availability.
4. **Models by iPhone Version:** Group models by their version (e.g., iPhone 11, iPhone XR).
5. **Top 5 Models with Highest Reviews:** List models with the highest number of reviews.
6. **Price Difference Between Highest and Lowest MRP:** Calculate the range of iPhone prices.
7. **Total Reviews for iPhone 11 and iPhone 12:** Aggregate reviews for these categories.
8. **iPhone with 3rd Highest MRP:** Find the model with the third-highest price.
9. **Average MRP Above 100,000:** Compute the average price of high-end models.
10. **Highest Rating-to-Review Ratio (128 GB Models):** Determine the model with the best ratings-to-review ratio among 128 GB options.

---


## Key Insights:
The model with the highest discount is iPhone 12 Pro.
The price range of iPhones (MRP) is ₹70,000.
iPhones above ₹100,000 have an average MRP of ₹124,999.
The top-rated 128 GB model based on the rating-to-review ratio is iPhone 11.
