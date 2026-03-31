# SmartCart — E-Commerce Recommendation System Homework 2



## How to Run
1. Install dependencies:
```
   pip install pandas numpy scikit-learn mlxtend matplotlib seaborn
```
2. Place `ecommerce_user_data.csv` and `product_details.csv` in the same folder as the notebook.
3. Open `homework2.ipynb` and run all cells in order.

## Outputs
- User-item matrix and sparsity analysis
- User similarity heatmap
- Top-5 product recommendations for all 50 users (saved to `recommendations.csv`)
- Evaluation metrics: Precision@5, Recall@5, Coverage
- Frequent itemsets and association rules with support, confidence, and lift
- Visualizations: heatmap, frequent itemsets bar chart, association rules bar chart, category distribution chart

## Project Structure
- **Part 1:** Data loading, inspection, user-item matrix, behavior aggregation
- **Part 2:** Cosine similarity, recommendation function, evaluation
- **Part 3:** Apriori algorithm, association rules, support/confidence/lift visualization
- **Part 4:** Heatmap, recommendation tables, category analysis