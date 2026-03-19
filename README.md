# Linear Regression from Scratch (PyTorch)

This project implements linear regression from scratch using PyTorch without high-level APIs.

## Objective

Learn how machine learning models work internally by implementing:

- Forward pass
- Mean Squared Error loss
- Gradient computation (autograd)
- Gradient descent updates

## Model

The model learns the relationship:

y = wx + b

from synthetic data:

y = 3x + 2 + noise

## Training Process

1. Initialize parameters randomly
2. Predict outputs
3. Compute loss
4. Backpropagate gradients
5. Update parameters

## Results

The model successfully learns parameters close to:

- w ≈ 3
- b ≈ 2

## Output

The plot below shows the fitted regression line:


<img width="772" height="588" alt="results" src="https://github.com/user-attachments/assets/1db8c7fb-face-4d5b-8313-c34012ecd54c" />

## Run

```bash
pip install -r requirements.txt
python main.py
