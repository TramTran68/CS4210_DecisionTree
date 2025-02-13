# CS4210 Decision Tree for Contact Lens Recommendation

## **Overview**
- This program implements a decision tree classifier to determine whether a contact lens should be prescribed based on patient attributes such as age, spectacle prescription, astigmatism, and tear production rate. It uses the ID3 algorithm and is implemented using the scikit-learn library.
---

## **Installation**
- Ensure Python is installed on your system. Then, install the required libraries using: **pip install scikit-learn matplotlib**
---

## **Usage**
1. Place the contact_lens.csv file in the same directory as decision_tree.py.
2. Run the script: python decision_tree.py
3. The program will:
- Read the dataset from **contact_lens.csv**.
- Convert categorical values into numerical values.
- Train a decision tree model.
- Display a visualization of the decision tree.
---

## **Expected Output**
- The decision tree is printed and visualized using matplotlib.
- The tree structure can be compared to manually computed ID3 results.
