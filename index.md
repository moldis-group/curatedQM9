---
layout: default
---

## QM9NMR dataset

The QM9-NMR dataset [Ref-1] contains gas and (implicit) solvent phase mPW1PW91/6-311+G(2d,p)-level chemical shielding for all atoms in the QM9 dataset [Ref-2] comprising 130,831 stable, synthetically feasible small organic molecules with up to 9 C, N, O and F atoms.

***

## QM9NMR

### B3LYP/6-31G(2df,p) geometries
[SI_DFT_geo.xyz](https://drive.google.com/file/d/1Kr9ZdYw503QsGT8qO2bid8wWQGQB-401/view?usp=sharing) Contains 130,831 molecules relaxed at B3LYP/6-31G(2df,p) level. These geometries are collected from the QM9 dataset reported in the [Ref-2](https://www.nature.com/articles/sdata201422)

### mPW1PW91/6-311+G(2d,p) @ B3LYP/6-31G(2df,p) NMR data
[SI_DFT_NMR.txt](https://drive.google.com/file/d/13vqG1zTsemLgfZP635pcAHjARhqDzJ8I/view?usp=sharing) For each molecule in SI_DFT_geo.xyz, file contains number of atoms, followed by molecule name and isotropic shielding tensors per atom in the molecule in Gas, CCl4, THF, Acetone, Methanol and DMSO respectively, obtained at mPW1PW91/6-311+G(2d,p).   

####  mPW1PW91/6-311+G(2d,p) @ B3LYP/6-31G(2df,p) <sup>13</sup>C shielding for tetramethylsilane (TMS) [in ppm] 
```
Gas      - 186.9704
CCl4     - 187.2352
THF      - 187.4958
Acetone  - 187.5949
Methanol - 187.6181
DMSO     - 187.6304
```

### PM7 geometries
[SI_baseline_geo.xyz](https://drive.google.com/file/d/1TgH_cbABKPMq9wG2wnftwDO_wl3XYTk2/view?usp=sharing) Contains 130,831 molecules relaxed at PM7 level.   

### B3LYP/STO-3G @ PM7 NMR data
[SI_baseline_NMR.txt](https://drive.google.com/file/d/16uw_v2VlPYK57NRjDnxVYi_hfspRLQdi/view?usp=sharing) For each molecule in SI_baseline_geo.xyz, file contains number of atoms, followed by molecule name and isotropic shielding tensors per atom in the molecule in Gas phase obtained at B3LYP/STO-3G level.

####  B3LYP/STO-3G @ PM7 <sup>13</sup>C shielding for tetramethylsilane (TMS) [in ppm] 
```
Gas      - 232.4620
```

***

## Case studies

### Geometries

| [SI_12Drugs_DFT_geo.xyz](data/SI_12Drugs_DFT_geo.xyz)               | Contains 12 Drug molecules relaxed at B3LYP/6-31G(2df,p) level.                            
| [SI_12Drugs_baseline_geo.xyz](data/SI_12Drugs_baseline_geo.xyz)     | Contains 12 Drug molecules relaxed at PM7 level.                                           
| [SI_40Drugs_DFT_geo.xyz](data/SI_40Drugs_DFT_geo.xyz)               | Contains 40 Drug molecules relaxed at B3LYP/6-31G(2df,p) level.                            
| [SI_40Drugs_baseline_geo.xyz](data/SI_40Drugs_baseline_geo.xyz)     | Contains 40 Drug molecules relaxed at PM7 level.                                           
| [SI_PAH_DFT_geo.xyz](data/SI_PAH_DFT_geo.xyz)                       | Contains 5 Polycyclic Aromatic Hydrocarbons molecules relaxed at B3LYP/6-31G(2df,p) level. 
| [SI_PAH_baseline_geo.xyz](data/SI_PAH_baseline_geo.xyz)             | Contains 5 Polycyclic Aromatic Hydrocarbons molecules relaxed at PM7 level.                
| [SI_GDB10to17_DFT_geo.xyz](data/SI_GDB10to17_DFT_geo.xyz)           | Contains 200 molecules from GDB10 to GDB17 molecules relaxed at B3LYP/6-31G(2df,p) level.  
| [SI_GDB10to17_baseline_geo.xyz](data/SI_GDB10to17_baseline_geo.xyz) | Contains 200 molecules from GDB10 to GDB17 molecules relaxed at PM7 level.                

### NMR data

| [SI_12Drugs_DFT_NMR.txt](data/SI_12Drugs_DFT_NMR.txt) 	| For each molecule in SI_12Drugs_DFT_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).       
| [SI_12Drugs_baseline_NMR.txt](data/SI_12Drugs_baseline_NMR.txt) 	| For each molecule in SI_12Drugs_baseline_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/STO-3G level.      
| [SI_40Drugs_DFT_NMR.txt](data/SI_40Drugs_DFT_NMR.txt) 	| For each molecule in SI_40Drugs_DFT_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).         
| [SI_40Drugs_baseline_NMR.txt](data/SI_40Drugs_baseline_NMR.txt) 	| For each molecule in SI_40Drugs_baseline_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/STO-3G level.          
| [SI_PAH_DFT_NMR.txt](data/SI_PAH_DFT_NMR.txt) 	| For each molecule in SI_PAH_DFT_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).           
| [SI_PAH_baseline_NMR.txt](data/SI_PAH_baseline_NMR.txt) 	| For each molecule in SI_PAH_baseline_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/STO-3G level.          
| [SI_GDB10to17_DFT_NMR.txt](data/SI_GDB10to17_DFT_NMR.txt) 	| For each molecule in SI_GDB10to17_DFT_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).            
| [SI_GDB10to17_baseline_NMR.txt](data/SI_GDB10to17_baseline_NMR.txt) 	| For each molecule in SI_GDB10to17_baseline_geo.xyz, contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/STO-3G level. 

***

## Revision notes

_19 June 2021: In our original upload, the atomic indices of the baseline data such as the PM7 geometries were shuffled. We thank Eric Collins for pointing this out. We have now uploaded the file 'pm7.tar.gz' with correct atomic indices._

***

## References
[Ref-1] [_Revving up <sup>13</sup>C NMR shielding predictions across chemical space: benchmarks for atoms-in-molecules kernel machine learning with new data for 134 kilo molecules_](https://doi.org/10.1088/2632-2153/abe347)            
Amit Gupta, Sabyasachi Chakraborty and Raghunathan Ramakrishnan     
Mach. Learn.: Sci. Technol. 2 (2021) 035010     
[Supplementary Information to the article (PDF)](data/SI.pdf)

```
@article{gupta2021revving,
  title={Revving up 13C NMR shielding predictions across chemical space: Benchmarks for atoms-in-molecules kernel machine learning with new data for 134 kilo molecules},
  author={Gupta, Amit and Chakraborty, Sabyasachi and Ramakrishnan, Raghunathan},
  journal={Machine Learning: Science and Technology},
  volume={2},
  number={3},
  pages={035010},
  year={2021},
  publisher={IOP Publishing}
}
```

[Ref-2] [_Quantum chemistry structures and properties of 134 kilo molecules_](http://www.nature.com/articles/sdata201422)          
Raghunathan Ramakrishnan, Pavlo Dral, Matthias Rupp, O. Anatole von Lilienfeld      
Scientific Data 1, Article number: 140022 (2014).    

```
@article{ramakrishnan2014quantum,
  title={Quantum chemistry structures and properties of 134 kilo molecules},
  author={Ramakrishnan, Raghunathan and Dral, Pavlo O and Rupp, Matthias and Von Lilienfeld, O Anatole},
  journal={Scientific data},
  volume={1},
  number={1},
  pages={1--7},
  year={2014},
  publisher={Nature Publishing Group}
}
```