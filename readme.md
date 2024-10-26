## Setup venv
```python
python3 -m venv .
```

## Activate venv
```python
source bin/activate
# install deps
pip install -r requirements.txt
# run notebook
jupyter notebook
```

## Download tiny shakespeare
```bash
curl https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt -o tinyshakespeare.txt
```

## Todo
PCA and Dimensionality Reduction: Implement Principal Component Analysis (PCA) from scratch in Python to gain experience with eigenvalues, eigenvectors, and transformations.

Implement Simple Neural Network Operations: Code simple neural networks from scratch using only NumPy. Try manually implementing forward and backward propagation for a single-layer perceptron, which will exercise your matrix multiplication, transpose, and gradient skills.
