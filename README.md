# AEGIS
Astrophysical Event Generator for Integration with Simulation-based inference

AEGIS is a python framework for simulating astrophysical point sources and their corresponding photon maps. A wide array of user defined source distributions and spectra can be simulated. Optimized for generation of numerous faint sources, it stategically only generates sources that end up emitting photons that are detected. The underlying calculations take advantage of optimized C code via numpy arrays for rapid data generation. For a tutorial of some of the features of AEGIS, take a look at 'AEGIS Introduction.ipynb'.

AEGIS, or an earlier varient, has been utilized in the following papers:
https://arxiv.org/abs/2112.00255
https://arxiv.org/abs/2402.04549
[coming soon] A follow up paper to 2112.00255
