# Assignment 2: Network with convolutional filters

This assignment is based on the chapter 2 code from *Generative Deep Learning* (2nd ed.):
[`convolutions.ipynb`](https://github.com/davidADSP/Generative_Deep_Learning_2nd_Edition/blob/main/notebooks/02_deeplearning/02_cnn/convolutions.ipynb) and [`cnn.ipynb`](https://github.com/davidADSP/Generative_Deep_Learning_2nd_Edition/blob/main/notebooks/02_deeplearning/02_cnn/cnn.ipynb).

It builds two versions of each:
1. **Original code**: stride 2
2. **My stride**: stride 3

Both models are trained and evaluated in the same notebook, which also explains what the output and accuracy show.

**Notebook:** [`Assignment2_convolutions_stride.ipynb`](Assignment2_convolutions_stride.ipynb)

| CIFAR-10 CNN | Stride 2 (original) | Stride 3 (mine) |
|---|---|---|
| Test accuracy | 65.5% | 62.4% |
| Parameters | 592,554 | 199,338 |
| Final feature map | 8×8 | 4×4 |

The full interpretation is at the end of the notebook.
