# AIM-Mapper: ATG8-interacting motif analyzer

<img src="https://github.com/andyposbe/AIM-Mapper/blob/main/ATG8_Schematic.png?raw=true" height="350" align="right" style="height:350">

Toolkit for contact analysis and prediction of ATG8/LC3 interacting motifs from AlphaFold2-multimer model data.

 For details, refer to manuscript:

[Tarhan Ibrahim,Virendrasinh Khandare,Federico Gabriel Mirkin,Yasin Tumtas,Doryen Bubeck ,Tolga O. Bozkurt AlphaFold2-multimer guided high-accuracy prediction of typical and atypical ATG8-binding motifs
*PLOS Biology*, 2023](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001962)

**Usage**

`complex_directory` Google Drive directory containing ColabFold output files from modelling of the ATG8 target together with its putative ligands (.pdb and .json files required).

`ligand_directory` directory with ColabFold output files from ligand proteins modelled by themselves.


<strong>Please keep filenames consistent between the complex and ligand model files (i.e. ensure the first ~15 characters match).</strong>
