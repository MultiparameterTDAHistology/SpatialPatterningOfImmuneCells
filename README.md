# Spatial Patterning of Immune Cells

This repository contains example code to accompany the computational topology paper [INSERT LINK], in which we analyse the spatial patterning of immune cells in tumours using topological techniques.

The complete pipeline for our analysis from histology image to topological observations can be broken down into four main steps:

1. Histology Scan to Cell Point Cloud
2. Multiparameter Persistence Computation
3. Multiparameter Landscape Computation
4. Statistical Analysis and Classification

In this repository we provide example notebooks detailing the novel part of this pipeline: steps 3 and 4. HTML versions of the notebooks are available for ease of access.

Scripts and software to perform all four steps of our analysis are outlined below. 

**Histology Image to Cell Point Clouds**
https://github.com/JABull1066/ImageAnalysisScripts

**Multiparameter Persistence Computation**
https://github.com/rivetTDA/rivet

**Multiparameter Landscape Computation**
https://github.com/OliverVipond/Multiparameter_Persistence_Landscapes detailed in notebook `Example Writing RIVET Input, Computing Multiparameter Persistence and Landscapes.ipynb`

**Statistical Analysis and Classification**
https://scikit-learn.org/stable/ detailed in notebook `Example Small Sample Statistical Analysis.ipynb`


### Data availability

**ABM data**
Available at https://drive.google.com/file/d/1JtjlKyvLVLt-OueOVFhkQ3W1T5witpUj/view?usp=sharing

**1.5mm Pointclouds**
Contained in repository `1.5mmRegions.zip`
