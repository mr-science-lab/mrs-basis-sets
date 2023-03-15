# mrs-basis-sets
## Basis Sets for Spectral Quantification
### Summary
Spectral quantification, decomposing proton magnetic resonance (<sup>1</sup>H MR) spectra into component metabolite signals that may comprise them, is an important step on the path to deriving physically meaningful metabolite concentrations from <sup>1</sup>H MRS data sets. Linear combination modeling of simulated or measured basis spectra--typically one per metabolite expected to appear in the data--is currently the recommended procedure for achieving this for the majority of in vivo MRS use cases [1]. Physically realistic and accurate basis sets are an integral aspect of spectral quantification by linear combination modeling, but it has been previously shown that basis function shapes may change significantly with details like radiofrequency (RF) pulse profile and consequently sequence vendor, even within the same general type of pulse sequence [2]. Against a backdrop of diverse approaches employed to acquire, process, and analyze <sup>1</sup>H MRS data for biomedical research use [3], correct correspondence between the pulse sequences used for acquisition and the basis sets used for spectral quantification is one aspect among many that those who employ <sup>1</sup>H MRS in their own research have the tools to standardize.

The below basis sets were generated in MARSS for *T<sub>E</sub>* = 30 and *T<sub>E</sub>* = 35 ms stock PRESS sequences for the three major vendors (Siemens, Philips and GE), as well as *T<sub>E</sub>* = 20 ms STEAM sequence (*T<sub>M</sub>* = 10 ms for GE/Siemens, *T<sub>M</sub>* = 16 ms for Philips, as is default). Simulations included 128 spatial points in each of the three spatial dimensions (128<sup>3</sup> total spatial points), realistic shaped RF pulses and exact timings via MARSS. Simulations were performed for BW = 2500/4000 Hz, and number of points in the FID = 1024/2048. The folders “RawBasis_” can be read into LCModel, whereas the folders ‘SummedSpins_” can be read into INSPECTOR.

### Citation
The citation for use of MARSS and these basis functions is: Landheer K, Swanberg KM and Juchem C. (2019). Magnetic Resonance Spectrum Simulator (MARSS), a novel software package for fast and computationally efficient basis set simulation. *NMR Biomed* e4129.

### References
[1] Near J, Harris AD, Juchem C, Kreis R, Marjańska M, Öz G, Slotboom J, Wilson M, Gasparovic C. Preprocessing, analysis and quantification in single-voxel magnetic resonance spectroscopy: experts' consensus recommendations. *NMR Biomed.* 2020 Feb 21: e4257.

[2] Landheer K, Swanberg KM and Juchem C. (2019). Magnetic Resonance Spectrum Simulator (MARSS), a novel software package for fast and computationally efficient basis set simulation. *NMR Biomed* e4129.

[3] Swanberg KM, Landheer K, Pitt D, and Juchem C. (2019). Quantifying the metabolic signature of multiple sclerosis by in vivo proton magnetic resonance spectroscopy: Current challenges and future outlook in the translation from proton signal to diagnostic biomarker. *Frontiers in Neurology* 2019; 10:1173.
