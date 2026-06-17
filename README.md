# Gradient descent
Gradient descent is an optimization algorithm used to minimize loss functions by iteratively updating parameters,
and it comes in three main forms. Batch gradient descent computes the gradient using the entire dataset,
giving smooth and stable convergence but at the cost of being slow and memory‑intensive. 
**Stochastic gradient descent (SGD)** updates parameters using just one randomly chosen sample at a time,
making it fast and efficient for large datasets, though the path of convergence is noisy. 
**Mini‑batch gradient descent** strikes a balance by updating parameters with small groups of samples, reducing noise
while remaining faster than full batch updates, which is why it’s the most widely used method in modern 
machine learning and deep learning training.
