# rhapsody-in-blue
***

This repository is a companion to the following paper: 

> **Sulfur K-edge Micro- and Full-field XANES Identifies Marker for Preparation Method of Ultramarine Pigment from Lapis Lazuli in Historical Paints** <br>
Alessa A. Gambardella (1), 
Marine Cotte (2,3), 
Kokkie Schnetz (4), 
Wout de Nolf(2), 
Rob Erdmann (1,5)
Roel van Elsas (6),
Victor Gonzalez (1),
Arie Wallert (1,7),
Piet D. Iedema (4),
Myriam Eveno (8,9),
Katrien Keune (1,4) <br>
> 1. Rijksmuseum, Conservation and Science, Hobbemastraat 22, 1071 ZC, Amsterdam, The Netherlands
> 2. European Synchrotron Radiation Facility (ESRF), 71 Avenue des Martyrs, 38000, Grenoble, France
> 3. Sorbonne Université, CNRS, Laboratoire d’archeologie moleculaire et structurale, LAMS, 4 place Jussieu, 75005 Paris, France
> 4. Van’t Hoff Institute for Molecular Sciences, University of Amsterdam, Science Park 904, 1090 GD, Amsterdam, The Netherlands
> 5. Conservation and Restoration, University of Amsterdam, Johannes Vermeerplein 1, 1071 DV, Amsterdam, The Netherlands
> 6. Vrije Universiteit, De Boelelaan 1105, 1081 HV, Amsterdam, The Netherlands
> 7. ....
> 8. Centre de Recherche et de Restauration de Musées de France, 14 Quai François Mitterrand, Palais du Louvre, 75001, Paris France
> 9. PSL Research University, Chimie ParisTech – CNRS, Institut de Recherche Chimie Paris, UMR8247, 75005, Paris, France <br> <br>
**Abstract:** *Ultramarine blue pigment from lapis lazuli is one of the most valued natural artist’s pigments used throughout history for its brilliant hue. Historical recipes describe various pigment preparation methods, however, little is understood about why such treatments were performed or how to distinguish them a posteriori on historical paintings. One such historically relevant treatment is heating of the lapis lazuli rock prior to extracting lazurite. X-ray absorption near-edge structure spectroscopy (XANES) at the sulfur K-edge in microbeam and full-field modes (analyzed with non-negative matrix factorization, NMF) is employed to monitor the changes in the sulfur species within lazurite following treatments. Sulfur signatures in lazurite show dependence on the heat-treatment of lapis lazuli rock from which it is derived. In particular, peaks at 2469.0 and 2471.2 eV, attributed to contributions from the trisulfur radical (S3•⁃), which is responsible for the blue color of lazurite, increase in relative intensity with heat of treatment ≥ 600 °C, paralleled by an intensified blue hue. The peak at 2472.5 eV (presumed as S8), on the other hand, decreases in relative intensity. The sulfur signature following heat-treatment is not only unique but also retained following accelerated aging of each pigment mixed as a paint with linseed oil. Further, XANES spectra using an attenuated focused microbeam were gathered on lazurite particles from five historical paint samples. In each, profiles matching that of pigment derived from heat-treated rock were identified, providing a marker for artists’ pigments that had been extracted from heat-treated lapis lazuli.*

The aim of this repository is to allow reproducibilty of the processed results presented in the publication from experimentally obtained raw data. The intention is that the presented research is fully reproducible. Efforts have been made to the best of the authors' abilities to make the data -- and associated processing procedures -- 'FAIR' (i.e. findable, accessible, interoperable, and reusable) in support of the growing Open Science movement. 

All of the figures in the paper corresponding to XANES data (unfocussed, microbeam, and full-field) can be reproduced herein following the set of notebooks contained and compiling in Inkscape 0.92.4 (https://inkscape.org/)

---
---
## Overview of contents
---
#### Jupyter notebooks
The Jupyter notebooks contained are numbered 01 to 17. To produce the final figures, the data underwent varying degrees of processing (or 'Treatments'). To successfully reproduce the final figures, notebooks should be run sequentially. At the start of each notebook, a summary of the input data, objective, program required, and output data is provided for reference. Further pertinent instructions are provided throughout each notebook.
Version: Jupyter notebook 5.5.0, Python 3.6.5.

#### Folders
The folders contained are those within which raw or processed data (or 'datasets') following various Treatments are stored. The first number (1 to 4) refers to the original raw dataset from which all other data is derived. The second number is merely sequential with respect to the order of data processing, with 1 referring to the raw dataset and 2 or higher referring to processed datasets. Further, there are six folders referring to specific Figures, as additional processing was needed for these figures prior to compiling in Inkscape.  

---
---
## Raw data
---
Four raw datasets are necessary to produce the final figures. Links to the raw data are within the notebooks or alternatively available below:
> Dataset_11 <br> Dataset_21 <br> Dataset_31 <br> Dataset_41

---
---
## Summary of datasets generated by notebooks
---

Below is a summary of the files contained/produced in each dataset; this information is similarly provided within the notebooks.

**Dataset_11** *(filenames consistent with that at ESRF)* (SEPARATE .dat!!) is there a way to separate these out into its own raw .dat file?
> 15092501.dat <br> 
- 'P-020' = scan #s 123, 129, 135 <br> 
- 'P-415' = scan #s 141, 147, 153 <br> 
- 'P-600' = scan #s 159, 165, 171 <br> 
- 'P-750' = scan #s 179, 185, 191

**Dataset_12**
> 2015_avg_P020.txt <br> 2015_avg_P415.txt <br> 2015_avg_P600.txt <br> 2015_avg_P750.txt

**Dataset_21** *filenames consistent with those at ESRF*
> 20Vpow_1.h5 <br> 415pow_1.hf <br> 600Vpow_1.h5 <br> 750Vpow_1.h5 <br> 20VoilL4.h5 <br> 750VL4.h5

**Dataset_22**
> H020_norm.hdf <br> H415_norm.hdf <br> H600_norm.hdf <br> H750_norm.hdf <br> H020oilL4_norm.hdf <br> H750oilL4_norm.hdf

**Dataset_x**
> H020_energy_1.csv

**Dataset_23**
> mean_value_H020_norm_date.png <br> 
mean_value_H415_norm_date.png <br> 
mean_value_600Vpow_1_date.png <br> 
mean_value_H750_norm_date.png <br> 
mean_value_H020oilL4_norm_date.png <br> 
mean_value_H750oilL4_norm_date.png

**Dataset_24**
> mask_mean_value_H020_norm_date.png <br> 
mask_mean_value_H415_norm_date.png <br> 
mask_mean_value_600Vpow_1_date.png <br>
mask_mean_value_H750_norm_date.png <br> 
mask_mean_value_H020oilL4_norm_date.png <br> 
mask_mean_value_H750oilL4_norm_date.png

**Dataset_25**
> H020_norm_wanted_particles_average_date.txt <br> 
H415_norm_wanted_particles_average_date.txt <br> 
H600_norm_wanted_particles_average_date.txt <br> 
H750_norm_wanted_particles_average_date.txt <br> 
H020oilL4_norm_wanted_particles_average_date.txt <br>
H750oilL4_norm_wanted_particles_average_date.txt

**Dataset_26**
> NMF_H750fit_3components_date_0.svg

**Dataset_27**
> NMF_H750fit_com_of_3_date_0.png (dpi = 600) <br>
NMFhist_H750fit_com_of_3_date_0.png (dpi = 600) <br>
NMFoil_H750fit_com_of_3_date_0.png (dpi = 600)

**Dataset_28**
> *with tick labels for reference* <br>
H020_norm_diff31_of_3_date_0.svg <br> 
H415_norm_diff31_of_3_date_0.svg <br> 
H650_norm_diff31_of_3_date_0.svg <br> 
H750_norm_diff31_of_3_date_0.svg <br> 
H020oilL4_norm_diff31_of_3_date_0.svg <br> 
H750oilL4_norm_diff31_of_3_date_0.svg

> *without tick labels for figure presentation* <br>
H020_normnotix_diff31_of_3_date_0.svg <br> 
H415_normnotix_diff31_of_3_date_0.svg <br> 
H650_normnotix_diff31_of_3_date_0.svg <br> 
H750_normnotix_diff31_of_3_date_0.svg <br> 
H020oilL4_normnotix_diff31_of_3_date_0.svg <br> 
H750oilL4_normnotix_diff31_of_3_date_0.svg

**Dataset_29**
> *consequentive spectra across two particles * <br>
spec_H020_norm_diff31_of_3_date_0.svg <br> 
spec_H415_norm_diff31_of_3_date_0.svg <br> 
spec_H650_norm_diff31_of_3_date_0.svg <br> 
spec_H750_norm_diff31_of_3_date_0.svg (1st & 2nd)<br> 
spec_H750_norm_diff31_of_3_date_1.svg (3rd & 4th)<br> 

> *locations of particles on full image with cursors showing location of spectra* <br>
H020_norm_20190524_cursors_um_0.svg <br>
H415_norm_20190524_cursors_um_0.svg <br>
H600_norm_20190524_cursors_um_0.svg <br>
H750_norm_20190524_cursors_um_0.svg (1st & 2nd)<br>
H750_norm_20190524_cursors_um_1.svg (3rd & 4th)<br>

> *zoom of particles with cursors showing location of spectra (with tick labels for reference)* <br>
H020_norm_1st_date_cursors_um_0.svg <br>
H020_norm_2nd_date_cursors_um_0.svg <br><br>
H415_norm_1st_date_cursors_um_0.svg <br>
H415_norm_2nd_date_cursors_um_0.svg <br><br>
H600_norm_1st_date_cursors_um_0.svg <br>
H600_norm_2nd_date_cursors_um_0.svg <br><br>
H750_norm_1st_date_cursors_um_0.svg <br>
H750_norm_2nd_date_cursors_um_0.svg <br>
H750_norm_3rd_date_cursors_um_0.svg <br>
H750_norm_4th_date_cursors_um_0.svg <br>

> *zoom of particles with cursors showing location of spectra (without tick labels for figure presentation)* <br>
H020_norm_notix_1st_date_cursors_um_0.svg <br>
H020_norm_notix_2nd_date_cursors_um_0.svg <br><br>
H415_norm_notix_1st_date_cursors_um_0.svg <br>
H415_norm_notix_2nd_date_cursors_um_0.svg <br><br>
H600_norm_notix_1st_date_cursors_um_0.svg <br>
H600_norm_notix_2nd_date_cursors_um_0.svg <br><br>
H750_norm_notix_1st_date_cursors_um_0.svg <br>
H750_norm_notix_2nd_date_cursors_um_0.svg <br>
H750_norm_notix_3rd_date_cursors_um_0.svg <br>
H750_norm_notix_4th_date_cursors_um_0.svg <br>

**Dataset_31** (SEPARATE .h5!!)
> allfiles_hg94.h5 <br>
- 'MH0170_5_att' = scan #s 133 - 150 <br>
*note:* mislabeled in .h5 as 'SKA2845_2_att' <br>
- 'SKA2102_8_att' = scan #s 190 - 222 <br> 
*note:* mislabeled in .h5 as 'SKA2845_2_att'

**Dataset_32**
> c_2017_MH0170_5_133_150.dat <br> c_2017_SKA2102_8_190_222.dat

**Dataset_33**
> c_2017_MH0170_5_vals_133to137_date_1.csv <br> 
c_2017_MH0170_5_vals_138to140_date_1.csv <br>
c_2017_MH0170_5_vals_141to142_date_1.csv <br>
c_2017_MH0170_5_vals_143to145_date_1.csv <br>
c_2017_MH0170_5_vals_146to148_date_1.csv <br>
c_2017_MH0170_5_vals_149to150_date_1.csv <br> <br>
c_2017_SKA2102_8_vals_190to191_date_1.csv <br>
c_2017_SKA2102_8_vals_192to193_date_1.csv <br>
c_2017_SKA2102_8_vals_194to195_date_1.csv <br>
c_2017_SKA2102_8_vals_196to198_date_1.csv <br>
c_2017_SKA2102_8_vals_199to202_date_1.csv <br>
c_2017_SKA2102_8_vals_203only_date_1.csv <br>
c_2017_SKA2102_8_vals_204to207_date_1.csv <br>
c_2017_SKA2102_8_vals_208to212_date_1.csv <br>
c_2017_SKA2102_8_vals_213to215_date_1.csv <br>
c_2017_SKA2102_8_vals_216to217_date_1.csv <br>
c_2017_SKA2102_8_vals_218to219_date_1.csv <br>
c_2017_SKA2102_8_vals_220to222_date_1.csv

**Dataset_41** (SEPARATE .h5!!)
> allfiles_hg139_2.h5 <br>
- 'MH0264X07b_att' = scan #s 003 - 060 <br>
- 'S18500_att' = scan #s 002 - 051 <br> 
- 'S18506_att' = scan #s 002 - 059 <br> 

**Dataset_42**
> c_2018_MH0264X07b_003_060.dat <br> c_2018_S18500_002_051.dat <br> c_2018_S18506_002_059.dat

**Dataset_43**
> c_2018_MH0264X07b_vals_12to18_date_1.csv <br>
c_2018_MH0264X07b_vals_19to22_date_1.csv <br>
c_2018_MH0264X07b_vals_23to25_date_1.csv <br>
c_2018_MH0264X07b_vals_26to31_date_1.csv <br>
c_2018_MH0264X07b_vals_32to33_date_1.csv <br>
c_2018_MH0264X07b_vals_34to37_date_1.csv <br>
c_2018_MH0264X07b_vals_38to39_date_1.csv <br>
c_2018_MH0264X07b_vals_3to11skip8_date_1.csv <br>
c_2018_MH0264X07b_vals_40only_date_1.csv <br>
c_2018_MH0264X07b_vals_41only_date_1.csv <br>
c_2018_MH0264X07b_vals_42to45_date_1.csv <br>
c_2018_MH0264X07b_vals_46to49_date_1.csv <br>
c_2018_MH0264X07b_vals_50to54_date_1.csv <br>
c_2018_MH0264X07b_vals_55to57_date_1.csv <br><br>
c_2018_S18500_vals_11to13_date_1.csv <br>
c_2018_S18500_vals_14to16_date_1.csv <br>
c_2018_S18500_vals_17to24_date_1.csv <br>
c_2018_S18500_vals_25to27_date_1.csv <br>
c_2018_S18500_vals_28to31_date_1.csv <br>
c_2018_S18500_vals_2to3_date_1.csv <br>
c_2018_S18500_vals_32to33_date_1.csv <br>
c_2018_S18500_vals_34to39_date_1.csv <br>
c_2018_S18500_vals_40to41_date_1.csv <br>
c_2018_S18500_vals_42to43and51_date_1.csv <br>
c_2018_S18500_vals_44to45_date_1.csv <br>
c_2018_S18500_vals_46only_date_1.csv <br>
c_2018_S18500_vals_48to49_date_1.csv <br>
c_2018_S18500_vals_4to10_date_1.csv <br>
c_2018_S18500_vals_50only_date_1.csv <br>
c_2018_S18506_vals_16to22_date_1.csv <br><br>
c_2018_S18506_vals_23to25_date_1.csv <br>
c_2018_S18506_vals_26to30_date_1.csv <br>
c_2018_S18506_vals_2to7_date_1.csv <br>
c_2018_S18506_vals_31to34_date_1.csv <br>
c_2018_S18506_vals_35to38_date_1.csv <br>
c_2018_S18506_vals_39to47_date_1.csv <br>
c_2018_S18506_vals_48to54_date_1.csv <br>
c_2018_S18506_vals_55to59_date_1.csv <br>
c_2018_S18506_vals_8to15_date_1.csv <br>

**Dataset_RAD** NEED!!!!!!!!!!
> !!c_2017_MH0169_vals_054_058_date_1.csv

---
---
# Specifics for Figures that require Jupyter workup
---
Below is a summary of the files needed and produced for specific figures; this information is similarly provided within the notebooks. For all others Figures, only Inkscape is required (see the following section for details)

## Figure 1
### Input
**Dataset_12** 
> *average normalized spectra from pastello treatment (unfocussed beam)* <br>
2015_avg_P020.txt <br> 2015_avg_P415.txt <br> 2015_avg_P600.txt <br> 2015_avg_P750.txt

**Dataset_25**
> *average normalized spectra from heavy-liquid treatment (full-field)* <br>
H020_norm_wanted_particles_average_date.txt <br> 
H415_norm_wanted_particles_average_date.txt <br> 
H600_norm_wanted_particles_average_date.txt <br> 
H750_norm_wanted_particles_average_date.txt <br> 
H020oilL4_norm_wanted_particles_average_date.txt <br> 
H750oilL4_norm_wanted_particles_average_date.txt <br> 

### Output (Input for Inkscape)
**Figure_1**
> Figure1_date_0.svg <br> 
Figure1_date_inset_0.svg

## Figure 4
### Input
**Dataset_33**
> *average normalized spectra from single lazurite particles in paintings (attenuated microbeam)* <br> c_2017_MH0170_5_vals_133to137_date_1.csv <br> 
c_2017_SKA2102_8_vals_194to195_date_1.csv

**Dataset_43**
> *average normalized spectra from single lazurite particles in paintings (attenuated microbeam)* <br>
c_2018_MH0264X07b_vals_38to39_date_1.csv <br> 
c_2018_S18500_vals_34to39_date_1.csv <br> 
c_2018_S18506_vals_16to22_date_1.csv

### Output (Input for Inkscape)
**Figure_4**
> Figure4_date_0.svg

## Figure 5
### Input
**Dataset_43**
> *average normalized spectra per particle for a single painting (attenutated microbeam)* <br>
c_2018_S18500_vals_002to003_1.csv <br>
c_2018_S18500_vals_004to010_1.csv <br>
c_2018_S18500_vals_011to013_1.csv <br>
c_2018_S18500_vals_014to016_1.csv <br>
c_2018_S18500_vals_017to024_1.csv <br>
c_2018_S18500_vals_025to027_1.csv <br>
c_2018_S18500_vals_028to031_1.csv <br>
c_2018_S18500_vals_032_033_1.csv <br>
c_2018_S18500_vals_034to039_1.csv <br>
c_2018_S18500_vals_040_041_1.csv <br>
c_2018_S18500_vals_042_043_051_1.csv <br>
c_2018_S18500_vals_044_045_1.csv <br>
c_2018_S18500_vals_046only_1.csv <br>
c_2018_S18500_vals_046to047_1.csv <br>
c_2018_S18500_vals_048to049_1.csv <br>
c_2018_S18500_vals_050_1.csv <br> <br>

### Output (Input for Inkscape)  
**Figure_5**
> Figure5_date_S18500_0.svg

## Figure SI3 NEED
### Input
**Dataset_RAD**
> *normalized consequetive scans on same spot (microbeam)* <br>
??c_2017_MH0169_vals_054_058_date_1.csv 

### Output (Input for Inkscape)  
**Figure_SI3**
>  FigureSI3_date.svg

## Figure SI8
### Input
**Dataset_33**
> *average normalized spectra per particle for a other paintings (attenutated microbeam)* <br>
c_2017_MH0170_5_vals_133to137_1.csv <br> 
c_2017_MH0170_5_vals_138to140_1.csv <br>
c_2017_MH0170_5_vals_141to142_1.csv <br>
c_2017_MH0170_5_vals_143to145_1.csv <br>
c_2017_MH0170_5_vals_146to148_1.csv <br>
c_2017_MH0170_5_vals_149to150_1.csv <br> <br>
c_2017_SKA2102_8_vals_190to191_1.csv <br>
c_2017_SKA2102_8_vals_192to193_1.csv <br>
c_2017_SKA2102_8_vals_194to195_1.csv <br>
c_2017_SKA2102_8_vals_196to198_1.csv <br>
c_2017_SKA2102_8_vals_199to202_1.csv <br>
c_2017_SKA2102_8_vals_203only_1.csv <br>
c_2017_SKA2102_8_vals_204to207_1.csv <br>
c_2017_SKA2102_8_vals_208to212_1.csv <br>
c_2017_SKA2102_8_vals_213to215_1.csv <br>
c_2017_SKA2102_8_vals_216to217_1.csv <br>
c_2017_SKA2102_8_vals_218to219_1.csv <br>
c_2017_SKA2102_8_vals_220to222_1.csv

**Dataset_43**
> *average normalized spectra per particle for a other paintings (attenutated microbeam)* <br>
c_2018_MH0264X07b_vals_003to011not008_1.csv <br>
c_2018_MH0264X07b_vals_012to018_1.csv <br>
c_2018_MH0264X07b_vals_019to022_1.csv <br>
c_2018_MH0264X07b_vals_023to025_1.csv <br>
c_2018_MH0264X07b_vals_026to031_1.csv <br>
c_2018_MH0264X07b_vals_032to033_1.csv <br>
c_2018_MH0264X07b_vals_034to037_1.csv <br>
c_2018_MH0264X07b_vals_038to039_1.csv <br>
c_2018_MH0264X07b_vals_040only_1.csv <br>
c_2018_MH0264X07b_vals_041only_1.csv <br>
c_2018_MH0264X07b_vals_042to045_1.csv <br>
c_2018_MH0264X07b_vals_046to049_1.csv <br>
c_2018_MH0264X07b_vals_050to054_1.csv <br>
c_2018_MH0264X07b_vals_055to057_1.csv <br> <br>
c_2018_S18506_vals_002to007_1.csv <br>
c_2018_S18506_vals_008to015_1.csv <br>
c_2018_S18506_vals_016to022_1.csv <br>
c_2018_S18506_vals_023to025_1.csv <br>
c_2018_S18506_vals_026to030_1.csv <br>
c_2018_S18506_vals_031to034_1.csv <br>
c_2018_S18506_vals_035to038_1.csv <br>
c_2018_S18506_vals_039to047_1.csv <br>
c_2018_S18506_vals_048to054_1.csv <br>
c_2018_S18506_vals_055to059_1.csv 

### Output (Input for Inkscape)
**Figure_SI8**
> FigureSI8_date_MH0170_0.svg <br>
FigureSI8_date_SKA2102_0.svg <br>
FigureSI8_date_MH0284X07b_0.svg <br>
FigureSI8_date_S18506_0.svg <br>

---
---
# Specifics for Figures that only require arranging in Inkscape
---
Below is a summary of the files needed to produce the remaining figures using Inkscape.

## Figure 2 
### Input
**Dataset_26**
> *components resulting from NMF on 750 heavy-liqid pigment (form full-field)* <br>
NMF_H750fit_3components_date_0.svg

**Dataset_27**
> *pair-plot of two components for each raw heavy-liquid pigment (from full-field)* <br>
NMF_H750fit_com_of_3_date_0.png (dpi = 600)

**Dataset_28**
> *without tick labels for figure presentation, false-colored images based on NMF components (from full-field)* <br>
H020_normnotix_diff31_of_3_date_0.svg <br> 
H415_normnotix_diff31_of_3_date_0.svg <br> 
H650_normnotix_diff31_of_3_date_0.svg <br> 
H750_normnotix_diff31_of_3_date_0.svg <br> 

**Dataset_29**
> *consequentive normalized spectra across two particles (full-field)* <br>
spec_H750_norm_diff31_of_3_date_0.svg (1st & 2nd)

> *without tick labels for figure presentation, zoom of particles with cursors showing location of spectra (full-field)* <br>
H750_norm_notix_1st_date_cursors_um_0.svg <br>
H750_norm_notix_2nd_date_cursors_um_0.svg <br>

## Figure SI5a
**Dataset_29**
> *consequentive normalized spectra across two particles (full-field)* <br>
spec_H020_norm_diff31_of_3_date_0.svg <br> 
spec_H415_norm_diff31_of_3_date_0.svg <br> 
spec_H650_norm_diff31_of_3_date_0.svg <br> 
spec_H750_norm_diff31_of_3_date_1.svg (3rd & 4th)<br> 

> *zoom of particles with cursors showing location of spectra (for reference only)* <br>
H020_norm_notix_1st_date_cursors_um_0.svg <br>
H020_norm_notix_2nd_date_cursors_um_0.svg <br><br>
H415_norm_notix_1st_date_cursors_um_0.svg <br>
H415_norm_notix_2nd_date_cursors_um_0.svg <br><br>
H600_norm_notix_1st_date_cursors_um_0.svg <br>
H600_norm_notix_2nd_date_cursors_um_0.svg <br><br>
H750_norm_notix_3rd_date_cursors_um_0.svg <br>
H750_norm_notix_4th_date_cursors_um_0.svg <br>

## Figure SI5b (larger version of Figure 2, for indicating other particles)
**Dataset_28**
> *without tick labels for figure presentation, false-colored images based on NMF components (from full-field)* <br>
H020_normnotix_diff31_of_3_date_0.svg <br> 
H415_normnotix_diff31_of_3_date_0.svg <br> 
H650_normnotix_diff31_of_3_date_0.svg <br> 
H750_normnotix_diff31_of_3_date_0.svg <br> 

## Figure SI6
**Dataset_28**
> *without tick labels for figure presentation* <br>
H020oilL4_normnotix_diff31_of_3_date_0.svg <br> 
H750oilL4_normnotix_diff31_of_3_date_0.svg

**Dataset_27**
> NMFhist_H750fit_com_of_3_20190625_0 <br>
NMFoil_H750fit_com_of_3_20190625_0
