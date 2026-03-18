# Optimization Algorithm Comparison

Interactive single-page visualization comparing four optimization algorithms on randomizable 1D functions:

- **Vanilla Gradient Descent** — follows the slope downhill, always trapped by local minima
- **GD + Momentum** — accumulates velocity to roll through small bumps
- **Adam** — adaptive learning rate that self-adjusts to gradient scale
- **Simulated Annealing** — random jumps with probabilistic uphill acceptance, not gradient-based

## Features

- Randomize the target function (sum of sinusoids + Gaussians)
- Click the chart to set start position
- Adjustable parameters for each algorithm
- Playback controls with configurable step delay
- Rerun from the same start to compare different settings

## Usage

Open `index.html` in a browser. No dependencies, no build step — it's a single self-contained HTML file.

## GitHub Pages

Live at: https://zwoodard.github.io/simulated-annealing-vs-gradient-descent-visualization/
