# Dataset 1
## Tests
- These tests were run at various different C-Rates on 1 40T battery
    - Discharge 
        - Battery was discharged from 100% SoC to 0% SoC
    - Charge 
        - Battery was charged from 0% SoC to 100% SoC
    - Wait
        - Battery was held at steady state 

## File Naming
- The number before the .lvm is the cycle number of that battery 
- The folder name will include the C-Rate of the test files in that folder 
    - Examples can be seen in the file structure section of this ReadMe 

## File Structure
```file
📁 dataset-1
├── 📁 Cycle0_.5CDischarge
    ├── 📄 40T_ChargeCycle0.lvm
    ├── 📄 40T_DischargeCycle0.lvm
    ├── 📄 40T_DischargeWait0.lvm
├── 📁 Cycle1_.5CDischarge
    ├── 📄 40T_ChargeCycle1.lvm
    ├── 📄 40T_DischargeCycle1.lvm
    ├── 📄 40T_DischargeWait1.lvm
.
.
.
├── 📁 Cycle5_2CDischarge    
    ├── 📄 40T_ChargeCycle5.lvm
    ├── 📄 40T_DischargeCycle5.lvm
    ├── 📄 40T_DischargeWait5.lvm
```
