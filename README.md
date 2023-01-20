# Diagonalizing matrix flows

This repo contains a Python notebook for diagonalizing matrix flows, as described in a [paper by Khesin and Modin](https://arxiv.org/abs/2207.10214) (the notebook was used to generate all the figures in that paper). Three different gradient matrix flows are studied: the Toda flow, the incompressible porous medium equation (spatially discretized via quantization), and a new diagonalizing flow that does not strive to sort the diagonal elements.

To run the notebook the following modules are needed:
- `numpy` and `scipy`
- `matplotlib` (linked to `ffmpeg` for creating movies)
- [`quflow`](https://github.com/klasmodin/quflow)
- `h5py`
