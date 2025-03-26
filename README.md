## Active populations and growth of soil microorganisms are framed by mean annual precipitation in three California annual grasslands

This repo contains code necessary to perform primary qSIP calculations used in ["Active Populations and the growth of soil microorganisms are framed by mean annual precipitation"](https://doi.org/10.1016/j.soilbio.2022.108886) 

## Experiment overview  

In this experiment we collected soils from three annual grasslands in California that span a rainfall gradient and performed incubations with isotopically labelled "heavy water" (H<sub>2</sub><sup>18</sup>O). Microorganisms incorporate <sup>18</sup>O into DNA during genome replication and the amount of isotopic incorporation approximates in situ bacterial growth rates (Schwartz 2007). EAF <sup>18</sup>O  was calculated for each bacterial ASV following the protocol outlined in Hungate et al., 2015.

![Presentation4](https://github.com/user-attachments/assets/b67544d0-b7ab-4529-8fb8-ca1166a313b2)

Map of California: (https://gisgeography.com/how-to-cite/)

Illustration by Victoria Queeney, inspired by the illustrations in *The Art of Fermentation* by Sandor Ellix Katz.

## Scripts  
  
1. ["Data_preparation"](https://htmlpreview.github.io/?https://github.com/mmf289/MAP-and-microbial-growth/blob/main/docs/Data_preparation.html): formats 16S seq data and incubation data so that it is compatible with the qSIP pipeline. 

2. ["qSIP_calculations"](https://htmlpreview.github.io/?https://github.com/mmf289/MAP-and-microbial-growth/blob/main/docs/qSIP_calculations.html): performs taxon filtering and computes EAF <sup>18</sup>O for bacterial ASVs at each site.  


## Citations

Schwartz, E. (2007). Characterization of growing microorganisms in soil by stable isotope probing with H218O. Applied and environmental microbiology, 73(8), 2541-2546.

Hungate, B. A., Mau, R. L., Schwartz, E., et al., (2015). Quantitative microbial ecology through stable isotope probing. Applied and environmental microbiology, 81(21), 7570-7581.
