## MAP & the growth of soil microbes (16S qSIP) 

This repo contains code necessary to perform primary qSIP calculations used in ["Active Populations and the growth of soil microorganisms are framed by mean annual precipitation"](https://doi.org/10.1016/j.soilbio.2022.108886) 

## Experiment overview  

In this experiment we collected soils from three annual grasslands in California that span a rainfall gradient and performed incubations with isotopically heav water (H<sub>2</sub><sup>18</sup>O). Microorganisms incorporate <sup>18</sup>O into DNA during genome replication and the amount of isotopic incorporation approximates in situ bacterial growth rates (Schwartz 2007). EAF <sup>18</sup>O  was calculated for each bacterial ASV following the protocol outlined in Hungate et al., 2015.  

## Scripts  
  
1. Data_preparation formats 16S seq data and incubation data so that it is compatible with the qSIP pipeline. 
https://htmlpreview.github.io/?https://github.com/mmf289/MAP-and-microbial-growth/blob/main/docs/Data_preparation.html

2. qSIP_calculations performs taxon filtering and computes EAF <sup>18</sup>O for bacterial ASVs at each site.  
https://htmlpreview.github.io/?https://github.com/mmf289/MAP-and-microbial-growth/blob/main/docs/qSIP_calculations.html

## Citations

Schwartz, E. (2007). Characterization of growing microorganisms in soil by stable isotope probing with H218O. Applied and environmental microbiology, 73(8), 2541-2546.

Hungate, B. A., Mau, R. L., Schwartz, E., et al., (2015). Quantitative microbial ecology through stable isotope probing. Applied and environmental microbiology, 81(21), 7570-7581.
