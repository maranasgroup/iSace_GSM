#### Notes
The model needs to be configured to simulate growth under specific conditions. Already-configured ready-to-go model files are available in the respective folders. To configure the "full_model" into condition-specific model, see the scripts demonstrating for COBRApy JSON format<br>
<br>
Specifically, what being changes between models for different growth conditions can be summarized as:<br>
* GAM and NGAM changes between conditions
* Specific extra nutrients are needed to be provided for anaerobic conditions due to absence of oxygen: Ergosterol, unsaturated fatty acid (Tween-80 in experiments), and nicotinate and R-pantothenate (part of YNB media). If you intend to simulate that the model cannot growth without these extra nutrients, use the aerobic model but set allowed oxygen uptake to zero.
* Certain (but not all) ceramide metabolites that require oxygen for production need to be removed from compCER reaction (synthesizing an average ceramide from different ceramide species)
