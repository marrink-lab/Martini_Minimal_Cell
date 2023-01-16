# Martini Minimal Cell

This directory contains the complete composition description for the Martini model of the Minimal Cell JCVI-syn3A.

The initial version of this whole-cell model is published in [Stevens et al., 2023](https://doi.org/10.3389/fchem.2023.1106495). We treat this GitHub page as a *living* description of our *in silico* cell, which will be kept up-to-date as the cell model is further developed. 

The model information is stored in the [composition file](composition.json), while references to the used -omics data, Martini parameters and Software tools are presented below.

## Compositional information
- Genomics: [GenBank CP016816.2](https://www.ncbi.nlm.nih.gov/nuccore/CP016816.2)
- Lipidomics: [Thornburg et al., 2021](https://doi.org/10.1016/j.cell.2021.12.025)
- Proteomics: [Thornburg et al., 2021](https://doi.org/10.1016/j.cell.2021.12.025)
- Metabolomics: [Thornburg et al., 2021](https://doi.org/10.1016/j.cell.2021.12.025)
- Cytosolic Protein structures: [Bianchi et al., 2022](https://doi.org/10.1021/acs.jpcb.2c04188)
- Membrane Protein structures: PDB ids [1POY](https://www.rcsb.org/structure/1POY), [2XZB](https://www.rcsb.org/structure/2XZB), [5WS4](https://www.rcsb.org/structure/5WS4), [6BVG](https://www.rcsb.org/structure/6BVG), [5JKI](https://www.rcsb.org/structure/5JKI)
- Ribosome structure: PDB id [4V42](https://www.rcsb.org/structure/4V42) and model from [Uusitalo et al, 2017](https://doi.org/10.1016/j.bpj.2017.05.043)

## Martini parameters references:
- Martini Version 2.1: [Marrink et al., 2007](https://doi.org/10.1021/jp071097f)
- Proteins / amino acids: [Monticelli et al., 2008](https://doi.org/10.1021/ct700324x)
- Lipids: [Wassenaar et al, 2015](https://doi.org/10.1021/acs.jctc.5b00209)
- DNA: [Uusitalo et al, 2015](https://doi.org/10.1021/acs.jctc.5b00286)
- RNA: [Uusitalo et al, 2017](https://doi.org/10.1016/j.bpj.2017.05.043)
- Nucleotide Cofactors and Metabolites: [Sousa et al., 2021](https://doi.org/10.1021/acs.jcim.0c01077)

## Software references:
- [Martinize2](https://github.com/marrink-lab/vermouth-martinize)
- [Polyply](https://github.com/marrink-lab/polyply_1.0)
- [TS2CG](https://github.com/marrink-lab/TS2CG1.1)
