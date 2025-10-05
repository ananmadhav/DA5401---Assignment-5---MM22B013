# DA5401 – Assignment 5

**Name:** Anan Madhav T V  
**Roll Number:** MM22B013  

---

## 📂 Folder Structure  

├── DA5401_A5_MM22B013.ipynb           # Main Jupyter Notebook  
├── README.md                          # Documentation file  
├── yeast.arff                         # Dataset
└── yeast.xml                   


---

## ⚙️ How to Run  
1. Open the notebook `DA5401_A4_MM22B013.ipynb` in **Jupyter Notebook** or **Google Colab**.  
2. Ensure the `yeast.arff` and `yeast.xml` file is present in the same directory.  

---

## 📝 Assignment Work

In this assignment, I worked on **multi-label classification using the Yeast dataset**. The main steps I performed are:  

1. **Data Exploration:** Checked dataset structure.  
2. **Preprocessing:** Normalized features.  
3. **Dimensionality Reduction:** Applied **t-SNE** and **Isomap** for 2D visualization.  
4. **Outlier Detection:** Used z-score analysis on t-SNE coordinates to find unusual samples.  
5. **Comparison:** Compared t-SNE and Isomap visualizations to study local vs. global structure.  

---

## ✅ Conclusion

- **t-SNE** captured local clusters effectively but distorted some global relationships.  
- **Isomap** preserved overall structure better and revealed global patterns.  
- Outlier detection highlighted rare/atypical samples that may affect modeling.

**Overall:** Use **Isomap** to understand global structure and **t-SNE** to inspect local clusters in this multi-label yeast dataset.

