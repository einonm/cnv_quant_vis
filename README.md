# Visualiser for the effect of CNVs on Quantitative Traits

Interaction visaluations of phenotypic distributions for CNV carriers in UK Biobank using Bokeh. Hosted by Cardiff University and available [here](https://kirov.psycm.cf.ac.uk/patch_cnv/patch_cnv).

![bokeh_app](/figures/bokeh_example.png)

**Required packages**
- bokeh
- scipy
- pandas
- numpy
- statsmodels
- pyarrow


**Or simply:**
- git clone https://github.com/seafloor/cnv_quant_vis.git
- cd cnv_quant_vis
- conda env create -f environment.yml

Data must be in cnv_quant_vis/data/biobank2.parquet
