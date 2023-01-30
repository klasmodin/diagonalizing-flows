# Diagonalizing matrix flows

![Evolution of diagonals for Toda](images/gradient_flow_N_256_toda_diagonals.png)

This repo contains a Python notebook for diagonalizing matrix flows, as described in a [paper by Khesin and Modin](https://arxiv.org/abs/2207.10214) (the notebook was used to generate all the figures in that paper). Three different gradient matrix flows are studied: the Toda flow, the incompressible porous medium equation (spatially discretized via quantization), and a new diagonalizing flow that does not strive to sort the diagonal elements.

To run the notebook the following modules are needed:
- `numpy` and `scipy`
- `matplotlib` (linked to `ffmpeg` for creating movies)
- [`quflow`](https://github.com/klasmodin/quflow)
- `h5py`

Here is the [HTML-version](diagonalizing-flows.html) of the notebook (in case you cannot run Jupyter notebooks but still would like to see the code).

Below you see the animations of the three flows studies, represented as incompressible porous medium equations on the sphere.

## Toda flow (TODA)

https://user-images.githubusercontent.com/2172666/215596567-089c3370-462c-4461-b321-e168830cc04a.mp4

## Incompressible porous medium (IPM)

https://user-images.githubusercontent.com/2172666/215596641-e889aea2-e396-4a6e-ade5-eb31f356ebc5.mp4

## Diagonalizing incompressible flow (DIAG)

https://user-images.githubusercontent.com/2172666/215596703-41077c1a-b1af-4d95-b321-a9e5e7fdc24f.mp4

