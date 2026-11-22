# Neural Net Visualiser

**A real neural network learning in front of you.**
Open `index.html` in a browser.

## What it does
Trains a small network from scratch on four problems: **XOR, AND, OR and a circle**. You can watch connection weights change and a loss chart fall as it learns.

## How it works
- Forward pass: each neuron sums its weighted inputs and applies an activation function.
- **Backpropagation** works out how much each weight contributed to the error.
- **Gradient descent** nudges each weight to reduce the error.
- No machine-learning library is used. The maths is written by hand.

## Why XOR matters
AND and OR can be solved with one straight line. XOR cannot, so it needs a hidden layer. That is why it's the classic test.

## Limits
Small network, tiny datasets, and no testing on unseen data.

## What I learned
A neural net is just repeated multiply, add and adjust. Seeing the weights move made backpropagation make sense.

## Next steps
Add a "learning rate" slider and show the decision boundary as a coloured map.

---
Part of [Aadit's projects](https://github.com/TechTonicCortex/techtoniccortex).
