# sypotential-kernel
Efficient evaluation of dense potential kernels on CPUs and GPUs via SYCL.


The aim of this library is to provide a simple framework in Python and C++ to evaluate dense potentials on CPU and GPU devices.
In particular, the following functionality is planned.

- Evaluation of Laplace and Helmholtz type kernels for sets of source and target points in 3 dimensions
- Framework for easy integration of custom kernels
- Device offloading with SYCL
- Support for vectorized operations on CPUs
- Integration in Python with Pybind11

