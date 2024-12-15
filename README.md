#### Data Analytics Assignment for upliance.ai

## Overview
This project analyzes user behavior, cooking preferences, and order trends for a hypothetical AI-powered cooking assistant. The primary objectives are to:
- Understand the relationship between cooking sessions and user orders.
- Identify popular dishes and meal preferences.
- Explore demographic factors influencing user behavior.
- Generate actionable business insights and recommendations.

## Datasets
The analysis is based on the following datasets:
1. **UserDetails**: Contains user demographic data and preferences.
2. **CookingSessions**: Logs of cooking sessions, including session ratings and duration.
3. **OrderDetails**: Information about orders placed by users, including meal types and order statuses.

## Objectives
1. Clean and merge the datasets to ensure consistency.
2. Analyze:
   - The relationship between cooking sessions and orders.
   - Popular dishes and meal preferences.
   - Demographic trends such as age-based order behavior.
3. Create visualizations for key insights.
4. Summarize findings and provide business recommendations.

## Project Structure
The repository contains the following files:
- **Assignment.xlsx**: The dataset provided for analysis.
- **analysis.py**: Python script containing the data cleaning, analysis, and visualization code.
- **Report.txt**: Text file summarizing the findings and recommendations.
- **README.md**: This file, describing the project structure and methodology.

## Methodology
### Data Cleaning
- Missing values in the `Rating` column were filled with the mean.
- Column names were standardized by removing extra spaces and normalizing case.
- Duplicate columns (e.g., `Meal Type_x`, `Meal Type_y`) resulting from merges were resolved.

### Analysis
1. **Relationship Between Cooking Sessions and Orders**:
   - Examined how session ratings influenced order completion rates.
2. **Popular Dishes**:
   - Identified the top 5 most frequently ordered or cooked dishes.
3. **Demographic Analysis**:
   - Explored age-based trends in ordering behavior.
4. **Meal Preferences**:
   - Analyzed preferences for meal types (e.g., breakfast, lunch, dinner).

### Visualizations
- **Session Rating vs. Order Completion**: Bar chart showing how session ratings correlate with order completion rates.
- **Top 5 Popular Dishes**: Bar chart of the most frequently cooked or ordered dishes.
- **Age vs. Total Orders**: Line chart displaying how age influences total orders.
- **Meal Type Preferences**: Pie chart showing the distribution of meal types.

### Recommendations
- Leverage top-rated dishes for promotions.
- Target campaigns to users with low session ratings to improve engagement.
- Focus on specific age groups with higher order activity for marketing efforts.

## How to Run the Code
1. Install the required libraries: `pandas`, `matplotlib`, `seaborn`.
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Run the Python script:
   ```bash
   python upliaceassignment.py
   ```
3. Review the generated visualizations and the `Report.txt` file for insights.

## Key Insights
1. **Popular Dishes**:
   - [List top 5 dishes, e.g., Caesar Salad, Pancakes...]
2. **Session Ratings Influence**:
   - Higher session ratings strongly correlate with order completion.
3. **Age-Based Trends**:
   - Users aged [X-Y] tend to place the most orders.
4. **Meal Type Preferences**:
   - Dinner is the most popular meal type.

## Deliverables
1. **Python Script**: Contains the full analysis workflow.
2. **Visualizations**: Plots illustrating key insights.
3. **Report**: Summary of findings and actionable business recommendations.
