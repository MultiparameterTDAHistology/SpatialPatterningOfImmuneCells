# Spatial Patterning of Immune Cells

This repository contains example code to accompany the computational paper ..., in which we analyse the spatial patterning of immune cells in tumours using topological techniques.

The complete pipeline for our analysis from histology image to topological observations can be broken down into four main steps:

1. Histology Scan to Cell Point Cloud
2. Multiparameter Persistence Computation
3. Multiparameter Landscape Computation
4. Statistical Analysis and Classification

In this repository we provide example notebooks detailing the novel part of this pipeline: steps 3 and 4.

Scripts and software to perform all four steps of our analysis are outlined below. 

**Histology Image to Cell Point Clouds**
https://github.com/JABull1066/ImageAnalysisScripts

**Multiparameter Persistence Computation**
https://github.com/rivetTDA/rivet

**Multiparameter Landscape Computation**
https://github.com/OliverVipond/Multiparameter_Persistence_Landscapes detailed in notebook `Example Writing RIVET Input, Computing Multiparameter Persistence and Landscapes.ipynb`

**Statistical Analysis and Classification**
https://scikit-learn.org/stable/ detailed in notebook `Example Small Sample Statistical Analysis.ipynb`
