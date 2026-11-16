# Product Recommendation System – Apriori and ECLAT

A Python-based Product Recommendation System that applies **Association Rule Mining** techniques, using Apriori and ECLAT algorithms, to discover frequently co-purchased products and generate product recommendations from retail transaction data.

The project implements market basket analysis to identify frequent itemsets and uncover relationships between products using Support, Confidence, and Lift metrics. It also compares the results of both algorithms to explore product associations and potential cross-selling opportunities.

## Key Features
- **Data Preprocessing:** Cleansing, normalization, duplicate removal, and transaction grouping.
- **Apriori Algorithm:** Identifies frequent itemsets using minimum support thresholds.
- **ECLAT Algorithm:** Implements vertical transaction ID-based mining using set intersections.
- **Association Rule Mining:** Generates product association rules using Support, Confidence, and Lift.
- **Product Recommendations:** Recommends related products based on identified associations.
- **Algorithm Comparison:** Compares frequent itemsets and generated association rules from both approaches.
- **Data Visualization:** Visualizes top product association rules based on Lift.

## Dataset
- **Source:** Groceries Dataset (Kaggle)
- **Records:** 38,765
- **Transactions:** 14,963
- **Unique Products:** 167
- **Preprocessing:** Missing-value handling, duplicate removal, product-name normalization, and transaction encoding.

## Evaluation Results

| Metric | Apriori | ECLAT |
|---|---:|---:|
| Frequent Itemsets | 750 | 750 |
| Association Rules | 37 | 37 |

**Thresholds:**
- Minimum Support: 0.001 (0.1%)
- Minimum Confidence: 0.10 (10%)
- Minimum Lift: 1.0

## Technologies Used
Python, Pandas, NumPy, Matplotlib, MLxtend, Jupyter Notebook.

## Project Objective
To explore association-rule-based recommendation techniques, understand purchasing patterns, and derive actionable product-placement and cross-selling insights from retail transaction data.
