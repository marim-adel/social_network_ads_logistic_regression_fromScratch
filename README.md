# Summary: Logistic Regression from Scratch

- I implemented **Logistic Regression** using only Python + NumPy (no sklearn model)
- Dataset used: **Social_Network_Ads.csv** (features: Age, EstimatedSalary → Target: Purchased)
  
- Steps:
  1. **Preprocessing** → load data, split into train/test, scale features.  
  2. **Sigmoid Function** → converts linear output into probability.  
  3. **Binary Cross-Entropy Loss** → measures prediction error.  
  4. **Gradient Descent** → update weights and bias step by step.  
  5. **Training Loop** → forward pass, loss calculation, backward pass, parameter update.  
  6. **Prediction** → probability → class (threshold = 0.5).  
  7. **Evaluation** → accuracy, precision, recall, f1, confusion matrix.  

- **Key Idea**: Logistic regression is a linear model that estimates probability using the sigmoid.  
- **Why from scratch?** → To understand what libraries (like sklearn) do internally.  

