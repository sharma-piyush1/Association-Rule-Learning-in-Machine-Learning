# Association Rule Learning in Machine Learning

This repository contains implementations of **Apriori** and **Eclat** algorithms for mining frequent itemsets and extracting association rules.  
Both algorithms are applied on the **Market Basket Optimization Dataset** to identify relationships between purchased items.

---

## 📁 Project Structure
```bash
ASSOCIATION RULE LEARNING
│
├── .vscode/
│
├── Market_Basket_Optimisation.csv
│
├── Apriori
│ ├── apriori.ipynb
│ └── apriori.py
│
└── Eclat
├── eclat.ipynb
└── eclat.py
```

---

## 📊 Dataset

The dataset contains transactional purchase records from a retail store.  
Each row represents a customer transaction and the items bought together.

---

## 🧠 Algorithms Used

| Algorithm | Description |
|-----------|------------|
| Apriori | Uses support, confidence, and lift to identify strong association rules. |
| Eclat | Itemset mining technique based on intersection of transaction IDs for fast computation. |

---

## 🚀 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- mlxtend  
- Matplotlib  
- Seaborn  

---

## 📈 Outputs

- Frequent itemsets
- Association rule confidence & lift analysis
- Visual insights for item relationship patterns

---

## 🔗 Future Enhancements

- Add FP-growth algorithm
- Add interactive dashboard using Streamlit
- Add rule comparison visualizations

---

## 🧑‍💻 Author

Created as part of machine learning practice and portfolio work.

---

### ⭐ Star the repo if you find it useful.

