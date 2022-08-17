# *iSace*1144 - A genome-scale metabolic model of *Saccharomyces cerevisiae*
This repository provides resources and model files for the genome-scale model *iSace*1144 that accompanies the following manuscript:<br>
**Proteome capacity constraints favor respiratory ATP generation**<br>
Yihui Shen, Hoang V. Dinh, Edward Cruz, Catherine M. Call, Heide Baron, Rolf-Peter Ryseck, Jimmy Pratas, Arjuna Subramanian, Zia Fatma, Daniel Weilandt, Sudharsan Dwaraknath, Tianxia Xiao, John I. Hendry, Vinh Tran, Lifeng Yang, Yasuo Yoshikuni, Huimin Zhao, Costas D. Maranas, Martin Wuhr, Joshua D. Rabinowitz<br>
bioRxiv 2022.08.10.503479; doi: https://doi.org/10.1101/2022.08.10.503479


The model is sourced from yeast 8.3.4 (at https://github.com/SysBioChalmers/yeast-GEM) and then is reformatted to the format in another yeast model (at https://github.com/maranasgroup/iRhto_memote) plus additional curations and fixes.<br>

#### Features
* Reactions and metabolites' IDs are in BiGG format
* Simplified lipid metabolism: modeling lipid species with average acyl-group representation rather than listing all specific lipid species containing combinations of acyl groups of different chain lengths.
* Updated and reformatted biomass reaction (see ./resources/iSace_biomass_formulation.xlsx)
* Content curations and fixes (see ./change_log/\*)
