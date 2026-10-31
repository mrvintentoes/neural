# neural

A neural network training visualizer in one self-contained file: [`index.html`](index.html). Open it in any modern browser (desktop or phone). It has no build step and no dependencies.

- A multilayer perceptron written from scratch: forward pass, backprop, SGD/Adam, L2, Xavier/He init, sigmoid + cross-entropy output.
- Five 2D datasets (spiral, circles, XOR, moons, Gaussian), adjustable noise, point count and train/test split. You can also tap the plot to add your own points.
- Live decision-boundary heatmap, network diagram (tap a neuron to see what it has learned), loss and accuracy charts.
- Run `gradCheck()` in the browser console to compare backprop gradients against finite differences.

Keyboard: `space` play/pause, `→` step one epoch, `r` reset weights.
