# *iSace*1144 - A genome-scale metabolic model of *Saccharomyces cerevisiae*
This repository provides resources and model files for the genome-scale model *iSace*1144 that accompanies the following manuscripts:<br>
<br>
**Mitochondrial ATP generation is more proteome efficient than glycolysis**<br>
Yihui Shen, Hoang V. Dinh, Edward R. Cruz, Zihong Chen, Caroline R. Bartman, Tianxia Xiao, Catherine M. Call, Rolf-Peter Ryseck, Jimmy Pratas, Daniel Weilandt, Heide Baron, Arjuna Subramanian, Zia Fatma, Zong-Yen Wu, Sudharsan Dwaraknath, John I. Hendry, Vinh G. Tran, Lifeng Yang, Yasuo Yoshikuni, Huimin Zhao, Costas D. Maranas, Martin Wühr & Joshua D. Rabinowitz<br>
Nature Chemical Biology. 2024. [doi: https://doi.org/10.1101/2022.08.10.503479](https://doi.org/10.1038/s41589-024-01571-y)<br>
(Original reconstruction. The model is sourced from yeast 8.3.4 (at https://github.com/SysBioChalmers/yeast-GEM) and then is reformatted to the format in another yeast model (at https://github.com/maranasgroup/iRhto_memote) plus additional curations and fixes.)<br>
<br>
**Evaluating proteome allocation of *Saccharomyces cerevisiae* phenotypes with resource balance analysis**<br>
Hoang V. Dinh and Costas D. Maranas<br>
Metabolic Engineering, 2023, 77:242-255; doi: https://doi.org/10.1016/j.ymben.2023.04.009<br>
(Further important updates to the model's growth and non-growth associated ATP maintenance (i.e., GAM and NGAM) parameters have been added.)<br>

#### Features
* Reactions and metabolites' IDs are in BiGG format
* Simplified lipid metabolism: modeling lipid species with average acyl-group representation rather than listing all specific lipid species containing combinations of acyl groups of different chain lengths.
* Updated and reformatted biomass reaction (see ./resources/)
* Content curations and fixes (see ./change_log/\*)
* Condition-specific GAM and NGAM values derived from experimental data for: (i) Batch, anaerobic, (ii) C-lim, anaerobic, (iii) Batch and C-lim, aerobic, (iv) N-lim and aerobic
