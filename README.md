PREAMBLE:

This repo holds the jupyter notebooks used to generate the data used in 'Feature Distillation with Synthetic Training Data: a Spectral Methods Approach' which will be submitted to Optics Express in September 2024.
This repo is maintained by the first author, Altai Perry.

ORGANIZATION:

Where applicable, the data that was generated (models, datasets) are uploaded and analysis notebooks refer to their dir. The generator notebooks output their locations to a USER_CREATED_DATA dir. If you want to generate your own data and models and analyze them (rather than what I supply in the CURATED_DATA dir), change the reference in the applicable analysis notebooks. 

The CiFAR-10 dataset can be found here: https://www.cs.toronto.edu/~kriz/cifar.html or, as used in the notebooks, via tensorflow

All other datasets used are either generated or supplied through KERAS in TensorFlow.

List of the packages used and their ver are found in packages.md.

ABSTRACT:

Currently, there is significant interest in understanding how artificial neural networks distill features and learn to classify patterns. Additionally, since machine-learning models require significant volumes of training data, the training data is often synthesized in a manner to emulate real test data.Here, we introduce a spectral-methods paradigm where the synthetic training images do not resemble the test images. As a result, the neural network focuses on learning specific features defined by the training data. In a demonstration with encoded diffraction optical neural networks, we parameterize the synthetic training data with a spectral methods approach.Our ``diffuse attention'' training data forces the neural network to learn the correlations from different combinations of sampled image locations. We both reconstruct and classify the reconstructed images, showing that the most faithfully reproduced images are not the ones that are the most accurately classified. We achieve feature distillation--the accentuating of differences in visual classes--with CIFAR-100 images with classification accuracies of 60\% with little computational overhead, which is an important milestone result. Our work highlights opportunities to understand feature-distillation with parameterized synthetic optical training data. 
