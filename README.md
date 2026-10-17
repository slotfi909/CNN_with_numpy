# CNN_with_numpy

A step-by-step Jupyter notebook implementing convolutional neural network building blocks in Python with NumPy. The exercises demonstrate individual layer operations and gradients using small random arrays, rather than training an end-to-end classifier.

## Features

- Zero-padding and convolution with configurable stride and padding.
- Max and average pooling.
- Backward propagation for convolution and pooling layers.
- Numerical examples, expected outputs, and a padding visualization.

## Installation and Usage

With Python 3 installed, run the following from the project directory:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install notebook numpy matplotlib h5py
python -m notebook ex06.ipynb
```

In Jupyter, select the environment's Python kernel and run the cells from top to bottom. NumPy implements the operations, Matplotlib provides plotting, and h5py is imported by the notebook.

The repository also includes a [lab handout](CI_LAB_6_CNN_with_numpy.pdf) and SIGNS datasets in `datasets/`. The separate `cnn_utils.py` module contains dataset utilities and legacy TensorFlow 1.x helpers; it is not imported by the notebook, so TensorFlow is not needed for the workflow above.
