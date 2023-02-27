# Great Sitkin FWANT work in 2023
This repository contains the imaging parameters and the resultant velocity model for the Great Sitkin full-wave ambient noise tomograhy (FWANT) paper.

Contact Xiaotao Yang (xtyang AT purdue DOT edu) for questions regarding this repository.

## Directories:
* EGFscripts

Scripts used to download the continous waveforms and extract the empirical Green's functions. The scripts use the SeisGo package [https://github.com/xtyangpsp/SeisGo] for processing the seismic waveforms. See the instructions there for installing and using SeisGo.

* stations_events

Informaiton of seismic stations and earthquakes used in the paper.

* vmodel

The velocity model from the full-wave ambient noise tomography. The MATLAB script/function to read the netCDF model is also provided. The format of the model file follows the standard/convention by IRIS EMC.

* outlines

Outline data used in plotting, including coastline for the Great Sitkin island and the outlien of the resolvable area (station coverage) used in masking the velocity model.

## References
* The Great Sitkin FWANT paper
Yang, X., Roman, D. C., Haney, M., Kupres, C. A. (in review). Double reservoirs imaged below Great Sitkin Volcano, Alaska, explain the migration of volcanic seismicity, Geophysical Research Letters

* Full-wave ambient noise tomograhy method
Gao, H., & Shen, Y. (2014). Upper mantle structure of the Cascades from full-wave ambient noise tomography: Evidence for 3D mantle upwelling in the back-arc. Earth and Planetary Science Letters, 390, 222–233. https://doi.org/10.1016/j.epsl.2014.01.012

Yang, X., & Gao, H. (2020). Segmentation of the Aleutian‐Alaska Subduction Zone Revealed by Full‐Wave Ambient Noise Tomography: Implications for the Along‐Strike Variation of Volcanism. Journal of Geophysical Research: Solid Earth, 125(11), 1–20. https://doi.org/10.1029/2020JB019677

* SeisGo package
Yang, X., Zuffoletti, I. D., D’Souza, N. J., & Denolle, M. A. (2022, 1). SeisGo: A ready-to-go Python toolbox for seismic data analysis [Computer Software]. Zenodo. Retrieved from https://doi.org/10.5281/zenodo.5873724 doi: 10.5281/zenodo.5873724
