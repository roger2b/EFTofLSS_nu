# Tree-level bispectrum in the effective field theory of large-scale structure extended to massive neutrinos

This Mathematica notebook computes the EFTofLSS prediction for the tree-level bispectrum of the total density contrast in the presence of massive neutrinos. This is the code developed to obtain the results in [arXiv:1804.06849](https://arxiv.org/abs/1804.06849), with the formalism originally proposed by Senatore & Zaldarriaga [arXiv:1707.04698](https://arxiv.org/abs/1707.04698). Instructions for use and references to be acknowledged are included in the Mathematica notebook. The code is also hosted on the EFTofLSS code repository together with other highly useful codes. 

We compute the tree-level bispectrum of dark matter in the presence of massive neutrinos in the mildly non-linear regime in the context of the effective field theory of large- scale structure (EFTofLSS). For neutrinos, whose typical free streaming wavenumber (kfs) is longer than the non-linear scale (kNL), we solve a Boltzmann equation coupled to the effective fluid equation for dark matter. We solve perturbatively the coupled system by expanding in powers of the neutrino density fraction (fν) and the ratio of the wavenumber of interest over the non-linear scale (k/kNL) and add suitable counterterms to remove the dependence from short distance physics. For equilateral configurations, we find that the total-matter tree-level bispectrum is approximately 16fν times the dark matter one on short scales (k > kfs). The largest contribution stems from the back-reaction of massive neutrinos on the dark matter growth factor. On large scales (k < kfs) the contribution of neutrinos to the bispectrum is smaller by up to two orders of magnitude.

### Usage
1. Download the input power spectra P(k) with and without massive neutrinos in the folder data
2. Download Mathematica notebook and read in the input theory P(k). The code is self consistent and is able to reproduce all the results in the paper.

------
Please cite the following two papers, if you use this notebook:

R. de Belsunce & L. Senatore, *Tree-level bispectrum in the effective field theory of large-scale structure extended to massive neutrinos*, [JCAP 1902 (2019) 038](https://iopscience.iop.org/article/10.1088/1475-7516/2019/02/038), [arXiv](https://arxiv.org/abs/1804.06849)

L. Senatore & M. Zaldarriaga, *The Effective Field Theory of Large-Scale Structure in the presence of Massive Neutrinos* (2017), [arXiv:1707.04698](https://arxiv.org/abs/1707.04698)

