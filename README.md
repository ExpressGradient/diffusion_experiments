# Diffusion Experiments

## Energy Guided Flow Matching

This project implements a sampling pipeline using Energy-Guided Flow Matching (EGFM), combining flow-based models with energy-based guidance for controlled image generation. The sampler progressively refines images from random noise, leveraging both learned velocity fields and energy gradients to steer the generation process. The approach enables more structured and controllable outputs compared to standard flow-based methods.

The code is still a work in progress, and results may vary depending on hyperparameters, model architectures, and training stability. Expect potential issues related to memory usage, convergence, and sampling efficiency, as improvements are actively being explored. Use it at your own discretion and feel free to experiment with modifications.
