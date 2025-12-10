# Understanding Decision Trees: How Impurity and Pruning Shape Model Performance (Penguins Dataset)

This repository contains the code and materials for my tutorial:

**"Understanding Decision Trees: How Impurity and Pruning Shape Model Performance (with the Penguins Dataset)"**

The tutorial focuses on:

- how Decision Trees use impurity measures (Gini vs Entropy) to choose splits,  
- how tree depth affects overfitting and generalisation, and  
- how cost-complexity pruning (`ccp_alpha`) can simplify a tree while keeping good performance.

---

## Repository Structure

- `decision_tree_penguins_tutorial.ipynb`  
  Jupyter notebook with all the code used in the tutorial, including intermediate steps and figure generation.

- `figures/`  
  Folder containing the figures exported from the notebook (tree plots, accuracy curves, feature importance, etc.) that are used in the PDF tutorial.

- `tutorial.pdf`  
  The written tutorial explaining the concepts and results in a more narrative, accessible way.

- `LICENSE`  
  Licence file indicating under what terms others may use this code.

---

## How to Run the Notebook

### Requirements

This project was tested with:

- Python 3.10+  
- `numpy`  
- `pandas`  
- `matplotlib`  
- `scikit-learn`

can install the dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn
