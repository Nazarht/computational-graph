# **Understanding Computational Graphs**

This repository contains a Jupyter Notebook that walks you through the basics of computational graphs and how they are used for automatic differentiation. The focus is on demonstrating the concepts, not creating a library or reusable tool.

---

## **What's Inside**

- **A Simple Framework**  
  A small implementation of computational graphs designed to show:
  - How variables and operations can be tracked.
  - How gradients are calculated step-by-step using the chain rule.

- **Manual vs. Automatic Gradients**  
  Side-by-side examples of calculating gradients manually and using a custom implementation to automate the process.

- **PyTorch Comparison**  
  Tests that compare the results of the custom implementation with PyTorch to highlight its accuracy and reinforce the learning process.

---

## **Why This Notebook Exists**

The goal here isn’t to build a robust or production-ready tool. Instead, this notebook is all about **learning by doing**. The code is written to be straightforward and easy to follow, making it a great way to understand what’s happening behind the scenes in frameworks like PyTorch or TensorFlow.

That being said, the implementation is limited in scope and might have some quirks or bugs. For example:
- It only supports basic operations like addition, subtraction, multiplication, division, and exponentiation.
- It doesn’t handle vectors, matrices, or complex edge cases like division by zero.

---

## **How to Use It**

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Install the required libraries:
   ```bash
   pip install numpy torch
   ```

3. Open the notebook in Jupyter or a similar environment:
   ```bash
   jupyter notebook
   ```

4. Run through the cells step by step to explore the code and see how it works.

---

## **Things to Keep in Mind**

- **This is for demonstration only.**  
  The code is intentionally simplified and may not cover every possible scenario. It’s written with clarity in mind, so you can focus on understanding the concepts rather than getting lost in complexity.

- **You’re encouraged to experiment.**  
  Feel free to modify the code, break it, fix it, and play around. That’s the best way to learn!

---

## **What You'll Learn**

By working through this notebook, you’ll get a hands-on understanding of:
- How computational graphs are built dynamically as operations are performed.
- How gradients are calculated locally for each operation and then propagated globally through the graph.
- The principles that power automatic differentiation in modern machine learning frameworks.

---

This project is meant to be approachable, not perfect. I hope you enjoy diving into the basics of computational graphs as much as I enjoyed putting this together!
