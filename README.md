# Label_smoothing_from_scratch
This project implements a fully connected neural network in NumPy to classify Fashion MNIST images. It demonstrates:

- He initialization
- ReLU and Softmax activations
- Mini-batch gradient descent
- L2 regularization
- Label smoothing
- Model checkpointing
- Custom training loop

## How to Run

1. Upload `fashion-mnist_train.csv` to your environment (Kaggle, Colab, or local).
2. Run the provided Python script or notebook.
3. Monitor training and test accuracy over epochs.
4. Saved weights (`W0.npy`, `B0.npy`, etc.) are created when test accuracy improves.

## Requirements

- Python 3
- NumPy
- Pandas
- scikit-learn
- Matplotlib

## Example

The script trains for 600 epochs and prints performance metrics at each step.

## License

MIT License
