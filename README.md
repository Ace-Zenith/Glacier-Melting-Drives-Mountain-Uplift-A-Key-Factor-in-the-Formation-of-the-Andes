# Glacier-Melting-Drives-Mountain-Uplift-A-Key-Factor-in-the-Formation-of-the-Andes

## About Repository
* This repository only contains the necessary codes for our 2-D convectional simulation. 

* There are three types of files, the .prm files are the source codes of ASPECT which could run on Linux platforms. The open-source code ASPECT (v2.4.0) (Bangerth et al., 2022) is available for download on GitHub <https:/github.com/geodynamics/aspect/releases/tag/v2.4.0> or Zenodo <https://doi.org/10.5281/zenodo.5131909>.
* The .wb file could run by the code Geodynamic World Builder (v0.4.0) (Fraters et al., 2019) which is used to build the models. The GWB is available for download on GitHub
<https://github.com/GeodynamicWorldBuilder/WorldBuilder/releases/tag/v0.4.0> or Zenode <https://doi.org/10.5281/zenodo.5014808>.
* The prem.txt is a gravity profile that follows the description of the preliminary reference Earth model (PREM) by Dziewonski & Anderson (1981), <https://doi.org/10.1016/0031-9201(81)90046-7>.

## About Codes
* The names of the .prm files contain three parts, the height of glacier loading refers to 'load X km', the melting velocity refers to 'XXXmelt' in which '001melt' refers to 0.01 m/year for example. The nine files of this kind correspond to Model 1-9, while the noload.prm corresponds to Model 0, loadhalf1.prm and loadhalf2.prm correspond to Model 10 and Model 11.
* Before running, please change '**set World builder file =**' and '**set Data directory =**' to your own file repository and change the '**set End time =**' to the final end time according to the Model Setup.
