# From Lorenz to AI Weather Models: a Minimal AI Weather Model Testbed

This repository contains a simple and self-contained notebook introducing the Lorenz system, chaotic dynamics, and a neural-network-based emulator trained to reproduce Lorenz trajectories.

The notebook is designed for educational and hackathon purposes and can be run directly in Google Colab.

## Notebook

The main notebook is located in:

```text
notebook/integrated_notebook_colab_ready.ipynb
```

You can:

* open it directly in Google Colab,
* or download and run it locally.

## Topics covered

* The Lorenz equations and chaotic systems
* Numerical integration with RK4
* Training a neural-network emulator using PyTorch
* Long rollouts and trajectory comparison
* Sensitivity to initial conditions
* Comparing physics-based and AI-based dynamics

## Example result

![Lorenz rollout](./figure/lorenz_rollout.png)

## Requirements

The notebook mainly uses:

```python
numpy
matplotlib
torch
```

These packages are available by default in Google Colab.

## Repository structure

```text
notebook/    -> Main Colab notebook
figure/      -> Figures used in README
```

## Intended use

This material was prepared as a lightweight educational testbed for understanding how AI models learn, approximate, and sometimes diverge from chaotic physical systems.
