ReadMe -- markdown

# Architectural Constraints on Feature Emergence in Neural Audio Models

This repository contains code and experiments for my dissertation research on why state-of-the-art neural audio models struggle to represent and control perceptually and physically meaningful features like pitch.

## Overview

Modern audio generation systems can produce convincing outputs, but they often fail to expose stable, controllable representations of basic musical features. This project investigates why: I show that interactions between model architecture and audio data geometry produce representational entanglements that make features like pitch difficult to isolate.

The core idea is that controllability is partly an architectural problem. By modifying design choices such as stride ratios, nonlinearities, and latent factorization, we can improve linear feature separability without reducing model performance. This reframes controllability as a design problem rather than a training limitation.

## Start Here

The core analysis is in: `notebooks/representational_geometry_analysis.ipynb`

This notebook contains the main experiments, visualizations, and findings.

Note: Most experiments were developed and run in Google Colab. The notebooks are provided for reference and readability; running them end-to-end may require additional setup (datasets, model weights, environment configuration).

## Repository Structure

- notebooks/: Main research notebooks and analyses
- figures/: Key visualizations from experiments
- requirements.txt: Approximate Python dependencies

## Status

This repository is under active development. I am currently refactoring research notebooks into cleaner scripts and documenting the core experimental pipeline.

## Example Results

*(Add 2–3 figures here)*

```markdown
![Feature Entanglement](figures/entanglement.png)
![Feature Separability](figures/separability.png)

### Use:
**MIT License**

Takes 30 seconds:
- GitHub → “Add file” → “Choose license template” → MIT
