# Deep Learning Semantics

So I currently reading a book called "Deep Learning with Pytorch" by Eli Stevens, Luca Antiga, and Thomas Viehmann with some of my lab mates. 

In the forward, it briefly mentioned some variable notation in passing:

- Variables with a `_t` suffix are tensors stored in CPU memory
- Variables with a `_g` suffic are tensors stored in GPU memory
- Variables with a `_a` suffix are NumPy arrays 

They also mentioned the boilerplate they like to use for their Jupyter notebooks using PyTorch, and I'll probably use it too for my future projects::

    %matplotlib inline
    from matplotlib import pyplot as plt
    import numpy as np
    
    import torch
    import torch.nn as nn
    import torch.nn.functional as F
    import torch.optim as optim
    
    torch.set_printoptions(edgeitems=2)
    torch.manual_seed(123)`
    
I will probably update this "blog post" as I learn more useful tidbits from reading this book.
