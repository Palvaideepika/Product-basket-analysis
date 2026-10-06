# Product Basket Analysis

## 📌 Project Overview

This project analyzes customer transaction data to identify products that are frequently purchased together.

The analysis uses the Online Retail II dataset and Python-based basket analysis techniques to discover frequently purchased product pairs and generate product recommendations.

## 🎯 Objective

The main objectives of this project are:

- Identify products frequently purchased together
- Generate product pairs from customer transactions
- Calculate pair frequency
- Calculate support
- Calculate confidence
- Identify potential product recommendations
- Visualize frequently purchased product combinations

## 📊 Dataset

The project uses the Online Retail II dataset.

The dataset contains customer transaction information including:

- Invoice
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Price
- Customer ID
- Country

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

## 🔄 Project Workflow

1. Load the Online Retail II dataset
2. Combine the available dataset sheets
3. Inspect the transaction data
4. Remove missing product descriptions
5. Remove cancelled transactions
6. Remove invalid quantities
7. Remove duplicate products within the same invoice
8. Group products by invoice
9. Generate product combinations
10. Count product-pair frequency
11. Calculate support
12. Calculate confidence
13. Identify top product pairs
14. Generate product recommendations
15. Visualize the results

## 📈 Key Analysis

### Product Pair Frequency

Product combinations were generated for each transaction to determine which products were commonly purchased together.

### Support

Support measures how frequently a product pair occurs across all transactions.

### Confidence

Confidence measures how likely one product is to be purchased when another product is purchased.

## 📁 Project Files

| File | Description |
|---|---|
| `Product_Basket_Analysis.ipynb` | Complete Python analysis |
| `top_10_product_pairs.csv` | Top frequently purchased product pairs |
| `product_recommendations.csv` | Product recommendation results |

## 💡 Business Applications

The results of this analysis can be used for:

- Product recommendations
- Cross-selling
- Product bundling
- Promotional offers
- E-commerce recommendations
- Store layout optimization
- Personalized marketing

## 📌 Conclusion

The analysis identifies frequently purchased product combinations and provides insights that can help businesses improve cross-selling and recommendation strategies.

Python and Pandas were used to transform transaction-level data into actionable product association insights.
