# PyTorch basics

This repository collects short `juputer notebook`s using `PyTorch`
starting with the fundamentals.

_This is work in progress._

Topics currently covered:
- activation functions: graph of functions with their derivatives  
- step functions: construct step functions from activation functions  
- bump functions: construct bump functions from step functions  
- dataloaders: basic usage examples  
- a minimal example showing the effect of setting (or not) gradients
  to zero  
- forward function hooks: basic usage examples  
- hidden layers: accessing sates of hidden layers via `PyTorch`
  (forward) hooks
- automatic differentiation in `PyTorch`: the `backward()` function
  and the vector-Jacobian product   
- function approximation:  
  - approximating a sigmoid with a multi-layer perceptron (MLP) using
  `ReLU` activation functions  
  - approximating a sine wave with MLPs: evidence of the vanishing
    gradient problem, impact of the choice of activation functions  
- linear regression: for pedagogical purposes we include a series of
  notebooks implementing linear regression using a varying number of
  functionalities from `PyTorch`  
- logistic regression  
- Fourier analysis: 
  - low-pass filters with `nn.Modules`
