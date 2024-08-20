## Jaxleyverse: Differentiable neuron simulations on CPU, GPU, or TPU

The `Jaxleyverse` contains code for simulating neurons with automatic differentiation and on accelerators (CPU, GPU, or TPU).

The center of the `Jaxleyverse` is the [`Jaxley` simulator](https://github.com/jaxleyverse/jaxley). `Jaxley` allows to simulate biophysically detailed neuron models and can compute gradients with respect to parameters such as ion channel or synaptic parameters. On top of `Jaxley`, the `Jaxleyverse` also contains [`jaxley-mech`](https://github.com/jaxleyverse/jaxley-mech), which is a collection of ion channels and synapses.
