# scitran/fsl-fast
[![Docker Pulls](https://img.shields.io/docker/pulls/scitran/fsl-bet.svg)](https://hub.docker.com/r/scitran/fsl-fast/)
[![Docker Stars](https://img.shields.io/docker/stars/scitran/fsl-bet.svg)](https://hub.docker.com/r/scitran/fsl-fast/)

Build context for a [Flywheel Gear](https://github.com/flywheel-io/gears/tree/master/spec) which runs FSL's [FAST](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FAST).

 FMRIB's Automated Segmentation Tool (FAST) segments a 3D image of the brain into different tissue types (Grey Matter, White Matter, CSF, etc.), whilst also correcting for spatial intensity variations (also known as bias field or RF inhomogeneities). The underlying method is based on a hidden Markov random field model and an associated Expectation-Maximization algorithm. The whole process is fully automated and can also produce a bias field-corrected input image and a probabilistic and/or partial volume tissue segmentation. It is robust and reliable, compared to most finite mixture model-based methods, which are sensitive to noise.

If you use FAST in your research, please quote the article:

> Zhang, Y. and Brady, M. and Smith, S. Segmentation of brain MR images through a hidden Markov random field model and the expectation-maximization algorithm. IEEE Trans Med Imag, 20(1):45-57, 2001.
