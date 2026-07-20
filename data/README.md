# Data
Repo containing the datasets for the Samsung 40T battery for electro-thermal, mechanical, and deformation characterization. 

<!-- Forced convection - liquid cooled.

electro-thermal-mechanical -->

## Test Types
- **HPPC**:
    - Hybrid Pulse Power Characterization Test
      - Current pulses are applied to the battery to test its response
        - Current is constant 
        - C-Rate is recorded in the file name 
- **multi_cycle**:
  - Constant Current Test
    - Battery is charged and then discharged over a certain number of cycles
      - Current is constant 
      - C-rate is recorded in the file name
      - **Data needs to be added (remove when added)**
- **single_cycle**:
  - Constant Current Test
    - All tests have C-rates in file name
    - Datasets will have:
      - Discharge cycle:
        - Starts at 100% SoC and then discharges to 0% SoC
      - Charge cycle:
        - Starts at 0% SoC and then charges to 100% SoC
      - Wait cycle
        - Holds the battery in a steady state  
    


## Licensing and Citation

This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License [cc-by-sa 4.0].

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)


Cite this as: 

@Misc{ARTSLabDatasetElectrothermalDeformation,    
  author = {ARTS-Lab},  
  howpublished = {GitHub},  
  title  = {Dataset Electrothermal Deformation-Characterization for {S}amsung 40T cell},    
  groups = {ARTS-Lab},    
  url    = {https://github.com/ARTS-Laboratory/dataset-electrothermal-deformation-characterization-for-samsung-40T-cell},   
  note  = {Accessed: Month dd, yyyy},   
}

<p align="center">
<img src="media/QR-code.png" alt="drawing" width="200"/>
</p>
<p align="center">
QR code for repo.
</p>

