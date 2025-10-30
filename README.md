# 🍃 Tea Management System - Machine Learning Project

This project is a **Tea Management System** built using **Python** and **Machine Learning (Decision Tree Classifier)**.  
It analyzes product cost, selling price, profit, and quantity sold to provide **AI-based recommendations** for improving sales and profit margins.  
The project also automatically generates a **PowerPoint presentation** summarizing the analysis, decision tree, and visual results.

---

## 📊 Features

✅ Predicts the quantity of tea sold using a trained **Decision Tree Classifier**  
✅ Analyzes relationships between **cost price, selling price, full quantity, and profit**  
✅ Visualizes:
- Decision Tree structure  
- Feature importance chart  
- Product Type vs Quantity Sold graph  

✅ Generates a **PowerPoint presentation (`Tea_Management_AI.pptx`)** containing:
- Dataset Overview  
- Decision Tree Visualization  
- Feature Importance  
- Product Type vs Quantity Sold  

✅ Provides **AI-based recommendations** for each product:
- Low profit margin  
- Promote high-profit products  
- Suggests discounts for low sales  
- Advises on price increases for high demand  

---

## 🧠 Machine Learning Model

- **Algorithm**: Decision Tree Classifier  
- **Library**: `scikit-learn`  
- **Training Data**: Custom dataset of product attributes  
- **Target Variable**: Quantity Sold  

Example training data:
| Product Type (g) | Cost Price | Selling Price | Full Quantity | Profit | Quantity Sold |
|------------------:|-----------:|---------------:|---------------:|--------:|----------------:|
| 250 | 375.00 | 480.00 | 60 | 105.00 | 15 |
| 100 | 165.00 | 200.00 | 150 | 35.00 | 20 |

---

## 🧩 Technologies Used

- **Python 3.x**
- **pandas** – Data processing  
- **scikit-learn** – Machine learning model  
- **matplotlib** – Visualizations  
- **python-pptx** – PowerPoint generation  

---

## ⚙️ How to Run

1. Clone the Repository
     ```bash
     git clone https://github.com/Shalani98/Tea-Management-ML.git
     cd Tea-Management-ML
2. Install Dependencies
    pip install pandas scikit-learn matplotlib python-pptx
3. Run the Script
    python Tea.py
4. Output
    Visualizations appear during executions.
    A powerpoint file Tea_Management_AI.pptx generated in your porject folder
