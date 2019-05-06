# SigPy for MRI Tutorial


In this tutorial, you will learn how to use [SigPy](https://github.com/mikgroup/sigpy) for MRI reconstruction.

There are three parts of the tutorial:

1. [Gridding Reconstruction](01-gridding-reconstruction.ipynb): This notebook goes through basic features of SigPy using the gridding reconstruction as an example usage.
2. [Parallel Imaginng Compressed Sensing Reconstruction](02-parallel-imaging-compressed-sensing-reconstruction.ipynb): This notebook shows how to run Apps in SigPy to perform parallel imaging compressed sensing reconstructions.
3. [Buiding a Parallel Imaging Compressed Sensing App](03-building-an-l1-wavelet-recon-app.ipynb): This notebook shows how to create an L1 wavelet regularized reconstruction App from scratch.


Some topics that are not covered in depth or at all:

- Non-Cartesian support in MRI Apps.
- MRI simulation functions, such as generating Poisson disk sampling using `poisson`.
- Plotting functions.
- Multi-CPU and GPUs using MPI.
- PyTorch interopability.
