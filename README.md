### distort_images
This repo is a minimal python package of https://github.com/rgeirhos/generalisation-humans-DNNs

### :tada: Update (Aug 2021): 
Would you like to test how well your own model performs on challenging generalisation tests, and whether it might even match or outperform human observers? This has never been easier! The comprehensive toolbox at [bethgelab:model-vs-human](https://github.com/bethgelab/model-vs-human) supports all datasets reported here and comes with code to evaluate arbitrary PyTorch / TensorFlow models. Simply load your favourite models, hit run and get a full PDF report on generalisation behaviour including ready-to-use figures!

# Install Eidolon 

```bash
pip install git+https://github.com/f-amerehi/Eidolon.git
```

# Data and materials from <br>"Generalisation in humans and deep neural networks"

This repository contains information, data and materials from the paper [Generalisation in humans and deep neural networks](https://arxiv.org/abs/1808.08750) by Robert Geirhos, Carlos R. Medina Temme, Jonas Rauber, Heiko H. Schütt, Matthias Bethge, and Felix A. Wichmann. We hope that you may find this repository a useful resource for your own research.

Please don't hesitate to contact me at robert.geirhos@bethgelab.org or open an issue in case there is any question!

This README is structured according to the repo's structure: one section per subdirectory (alphabetically).

A subset of the experiments described here were reported in an earlier version posted on arXiv ("Comparing deep neural networks against humans: object recognition when the signal gets weaker", Geirhos et al., June 2017). We now extended our previous work by additional image manipulations (now 83K instead of 40K psychophysical trials), more recent networks (ResNet instead of AlexNet) plus extensive results for testing generalisation performance of networks trained directly on distortions.
