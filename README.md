# Neural Network from Scratch
Built a fully-connected neural network from scratch using only NumPy, without any ML libraries.

## Implemented:
- Forward and backward **propagation**
- Multiple hidden layers (Used 3 for an example)
- ReLU & Softmax **activation functions**
- Categorical cross-entropy loss
- Training loop with accuracy & loss tracking
- L1 & L2 **regularization**
- Dense and dropout layers
- Spiral dataset training
- Comparison of **optimizers**:
    - Learning Rate Decay
    - Momentum
    - AdaGrad
    - RMSprop
    - Adam


## Requirements

Python 3.x
NumPy
Matplotlib (for visualization)
nnfs (for dataset generation)

```bash
  pip install numpy matplotlib nnfs
```


## Results
### Popular Moon Dataset
Achieved **95% training accuracy**
Smooth decision boundary, low loss convergence

### Popular Spiral Dataset
Learned complex non-linear patterns, even humans fail to classify.
**90% training accuracy** after tuning

### Reference
*nnfs.io*
