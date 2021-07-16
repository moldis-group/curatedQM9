---
layout: default
---

## curatedQM9 dataset

The QM9 dataset [Ref-1] comprises structures and properties of 133,885 stable, synthetically feasible small organic molecules with up to 9 C, N, O and F atoms. The geometries and structures are calculated using density functional theory (DFT) at the B3LYP/6-31G(2df,p) level. The initial geometries of these molecules were generated from SMILES strings reported in the GDB17 chemical universe [Ref-2]. Out of 133885 molecules in the QM9 set, 3054 have been labeled as 'uncharacterized' because these molecules rearranged during geometry optimization. This 3054 set has been curated [Ref-3] using a high-throughput workflow that performs CONNectivity preserving Geometry Optimization (ConnGO) with the same DFT method as in [Ref-1]. With ConnGO, 2830 molecules (out of 3054) are successfully converged to geometries with correct connectivities as encoded in their original SMILES. The resulting curatedQM9 dataset contains 130831 + 2830 = 133660 molecules.     

Download link: [133660_curatedQM9_outof_133885.zip, 208 MB](https://drive.google.com/file/d/12jDXoVPkNnDwAWvKlDncF5iUWWDk0yZ-/view?usp=sharing). 

***

## References

[Ref-1] [_Quantum chemistry structures and properties of 134 kilo molecules_](http://www.nature.com/articles/sdata201422)          
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

[Ref-2] [_Enumeration of 166 Billion Organic Small Molecules in the Chemical Universe Database GDB-17_](https://doi.org/10.1021/ci300415d)     
Lars Ruddigkeit, Ruud van Deursen, Lorenz C. Blum, and Jean-Louis Reymond     
J. Chem. Inf. Model. 52 (2012) 2864-2875
```
@article{ruddigkeit2012enumeration,
  title={Enumeration of 166 billion organic small molecules in the chemical universe database GDB-17},
  author={Ruddigkeit, Lars and Van Deursen, Ruud and Blum, Lorenz C and Reymond, Jean-Louis},
  journal={Journal of chemical information and modeling},
  volume={52},
  number={11},
  pages={2864--2875},
  year={2012},
  publisher={ACS Publications}
}
```

[Ref-3] [_Troubleshooting unstable molecules in chemical space_](https://doi.org/10.1039/D0SC05591C)            
Salini Senthil, Sabyasachi Chakraborty and Raghunathan Ramakrishnan     
Chemical Science 12 (2021) 5566-5573     
[Supplementary Information to the article (PDF)](https://www.rsc.org/suppdata/d0/sc/d0sc05591c/d0sc05591c1.pdf)

```
@article{senthil2021troubleshooting,
  title={Troubleshooting unstable molecules in chemical space},
  author={Senthil, Salini and Chakraborty, Sabyasachi and Ramakrishnan, Raghunathan},
  journal={Chemical Science},
  volume={12},
  number={15},
  pages={5566--5573},
  year={2021},
  publisher={Royal Society of Chemistry}
}
```
