# Helpful Votes Analysis – Amazon All Beauty Dataset

## Project Overview
This project was completed as part of the **MeriSKILL Data Analyst Virtual Internship**. The goal of this analysis is to explore customer reviews from the **Amazon All Beauty** dataset and identify the key factors that make a review helpful to other shoppers.

## Objectives
- Clean and preprocess raw e-commerce review data.
- Analyze the relationship between star ratings, review length, verified purchases, and helpful votes.
- Visualize patterns in customer engagement and review usefulness.

## Tools & Libraries Used
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

## Key Workflow
1. **Data Cleaning:** Handled missing values, converted timestamps to readable dates, and parsed helpful vote counts into numeric formats.
2. **Feature Engineering:** Created new metrics including review word count (`review_word_count`), review summary length, and image attachment flags.
3. **Exploratory Data Analysis (EDA):** Compared average helpful votes across 1-to-5 star ratings, verified vs. unverified purchases, and review lengths.

## Key Insights
- **Detailed Reviews Perform Better:** Longer, more descriptive reviews consistently receive more helpful votes than short one-line comments.
- **Extreme Ratings Drive Engagement:** 1-star and 5-star reviews attract significantly higher helpful vote counts compared to neutral 3-star reviews.
- **Verified Purchases Build Trust:** Reviews from verified buyers generate higher engagement and stronger helpfulness ratios.

## How to Run
1. Clone this repository to your local machine.
2. Ensure Python and the required libraries (`pandas`, `matplotlib`, `seaborn`) are installed.
3. Place the `All_Beauty` dataset in the project directory and run the Jupyter Notebook.
