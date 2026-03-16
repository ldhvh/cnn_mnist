# CNN-MNIST

CNN trained on the MNIST dataset to recognize handwritten digits. Two conv layers, dropout ~98% test accuracy after 5 epochs.

## notebook contents

- data prep and normalisation
- model architecture with summary
- training with accuracy and loss curves
- confusion matrix
- sample predictions

## model

```
Conv2D(32) -> MaxPool -> Conv2D(64) -> MaxPool -> Dropout(0.3) -> Dense(128) -> Dense(10)
```
