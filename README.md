PREAMBLE:

This repo holds the jupyter notebooks used to generate the data used in SVD ENTROPY MEASURES LEARNING RATE AND GENERALIZABILITY OF ENCODED DIFFRACTION RECONSTRUCTION which was submitted to IEEE International Conference on Image Processing (ICIP) 2022.
This repo is maintained by the first author, Altai Perry.

ORGANIZATION:

Where applicable, the data that was generated (models, datasets) are uploaded and analysis notebooks refer to their dir. The generator notebooks output their locations to a USER_CREATED_DATA dir. If you want to generate your own data and models and analyze them (rather than what I supply in the CURATED_DATA dir), change the reference in the applicable analysis notebooks.

ABSTRACT:

Coded diffraction offers effective means of solving the phase problem. However, efforts to develop faster methods of Fourier image reconstruction are a significant area of current research as established methods require O[8n^2(\log n)^4] and a deliberate sampling scheme. This paper refines a generalized reconstruction model that is capable of reconstruction with at worst O[2n^4], advantageous in low resolution, low SWaP applications. We show that synthetic training data with higher singular value decomposition entropy (H_{SVD}) increases accuracy with generalized image reconstruction; in order to learn high-H_{SVD} images, a low-H_{SVD} vortex lens is required. We show slower convergence rates with higher-H_{SVD} training data at the trade off of reconstruction at higher fidelity.
