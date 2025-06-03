Customer Segmentation and Analysis

This project performs customer segmentation using Hierarchical Clustering to identify high-value customers based on their age, income, and purchasing behavior. The goal is to uncover customer insights and provide actionable recommendations for marketing and product strategy.

Dataset

The dataset includes anonymized customer information with the following key columns:

- `Customer_ID`: Unique identifier
- `Age`: Age of the customer
- `Income`: Annual income
- `Purchase_Amount`: Total spending
- `Product_Category`: Category of purchased products

Objective

To:
- Identify the age and income of the customer who purchases the most
- Segment customers using clustering
- Visualize and analyze key behavioral patterns
- Provide psychographic profiles and business recommendations

Tools & Libraries

- Python
- Pandas & NumPy
- Scikit-learn
- Seaborn & Matplotlib
- Scipy (for Hierarchical Clustering)

Analysis & Segmentation

- Preprocessed and scaled the data
- Performed Hierarchical Clustering (Ward Method) on a random sample to avoid memory issues
- Identified 4 distinct customer segments based on age, income, and purchase amount
- Visualized relationships between features using scatter plots, heatmaps, bar charts, and box plots

Key Insights

- The highest-spending customers are typically middle-aged and high-income.
- Customers aged 26-45 showed the highest engagement and spending.
- Product categories with higher average purchase amounts offer opportunities for focused marketing.
- Four unique customer segments were identified with distinct behavioral and demographic patterns.

Psychographics (Inferred)

- High-income, high-spend: Likely value convenience, quality, and premium offerings.
- Young, moderate spend: Trend-sensitive, price-conscious, digitally engaged.
- Moderate-income, low spend: May be cautious spenders; potential for upselling with offers.

Recommendations

- Focus marketing on high-value customer segments (Segment 2).
- Upsell to moderate-income segments using bundle deals.
- Design age-specific campaigns, especially for the 26–45 age group.
- Use exclusive memberships to retain high-income, low-frequency buyers.

Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Pc434/customer-segmentation.git
   cd customer-segmentation

2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook:
   jupyter notebook customer_segmentation.ipynb

