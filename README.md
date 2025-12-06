# groceries-market-basket-analysis


This project performs Market Basket Analysis on grocery purchase transactions to discover co-purchasing patterns between items. It uses association rule mining to identify strong item pairings and potential cross-selling opportunities. The notebook is written in a beginner-friendly way while still including deeper analytical concepts.

## Dataset
- Input file: groceries.csv  
- Each row represents one item purchased within a customer transaction  
- Transactions are grouped using customer ID and date  

## Objectives
- Identify frequently purchased items  
- Transform raw purchase data into transaction baskets  
- Apply Apriori to extract frequent itemsets  
- Generate association rules (support, confidence, lift)  
- Visualize top patterns using a lift heatmap  
- Interpret results from a business perspective  

## Tools Used
- Python  
- Pandas  
- Numpy  
- MLxtend  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Key Insights
- Certain items show strong co-purchasing behavior  
- High lift pairs indicate reliable associations beyond random chance  
- Items such as sausage, yogurt, root vegetables, and shopping bags appear frequently in association rules  
- Visualizations help highlight patterns that may not be obvious from raw data  

## Business Interpretation
- Strong item pairings can guide cross-selling and promotional strategies  
- Heatmap results provide insight into optimizing store layout  
- Frequent pairings support targeted marketing and inventory planning  
- The analysis demonstrates how transactional data can provide actionable retail insights  

## Files in this Repository
- groceries_market_basket_analysis.ipynb – main analysis notebook  
- groceries.csv – sample dataset  
- README.md – project documentation  

## How to Run
1. Clone the repository  
2. Place groceries.csv in the same folder as the notebook  
3. Install required libraries (including mlxtend and seaborn)  
4. Run the notebook step-by-step in Jupyter  

## Conclusion
The analysis successfully identifies meaningful co-purchasing patterns within grocery transactions. These results can help support store layout decisions, combo offers, targeted promotions, and personalized product recommendations.
