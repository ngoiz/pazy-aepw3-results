# Pazy Wing Analysis Results

Results for simulations/experiments conducted on the Pazy wing.

The results are presented in Jupyter notebooks in the respective folders which you should be able to view from within Github.

Currently available:
  
  * `01_Bending`: static bending experimental and computational comparison. Mass placed mid-chord at the wing-tip
  * `02_Torsion`: static twisting experimental and computational comparison. Mass placed 80mm ahead of leading edge at the wing-tip
  * `03_StaticAeroelastic`: coupled aeroelastic static solution at various angles of attack. Computational and experimental comparison
  * `04_DeformedModal`: change of structural modal frequencies with deformation caused by aerodynamic loading
  * `05_StraightWingFlutter`: stability analysis of the Pazy wing at zero degree angle of attack (straight wing)
  * `06_DeformedWingFlutter`: stability analysis of the Pazy wing deformed by the aerodynamic loading caused by non-zero angles of attack
  
## SHARPy and the Pazy wing model

For more information on SHARPy, visit the repo [https://github.com/imperialcollegelondon/sharpy](https://github.com/imperialcollegelondon/sharpy)

The Pazy wing model for SHARPy has been derived from the model available for UM/NAST [1]. The SHARPy model is available [here](https://github.com/ngoiz/pazy-model).
  
## Contributing

Feel free to add your own set of results. From the Jupyter notebook file in each of the tests it should be fairly straight forward to add any new cases. If you do, please make sure that the data you add requires no post-processing in order to keep the files as clean as possible.

## References
[1] Riso, C., & Cesnik, C. E. S.. Equivalent Beam Distributions of the Pazy Wing. University of Michigan; 2020.

## Contact

If you have any questions and want to get in touch:
  * [Norberto Goizueta](https://www.imperial.ac.uk/aeroelastics/people/goizueta/)
  * [Rafael Palacios](https://www.imperial.ac.uk/people/r.palacios)
