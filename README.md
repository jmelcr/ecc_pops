# ECC-POPS: parameters for POPS lipid employing ECC as model polarizability

This repository shows the
 development of ECC-POPS - 
classical MD lipid models with 
implicitly embedded electronic polarization
through Electronic Continuum Correction ([ECC](https://jmelcr.github.io/blog/ECC-post)).

Directory structure and working style is highly inspired by 
open-collaboration [NMRLipids projects](https://nmrlipids.blogspot.fi/),
with its [GitHub repositories](https://github.com/NMRLipids).

Folder
**Manuscript** contains LaTeX and PDF version of the manuscript.

Folder
**topologies** contains topologies of the employed molecules in Gromacs format (i.e. *.itp files). 
This includes:
ECC-lipids:
- phospholipids POPC & POPS
- SPC/E water model
- ECC cations and anions
Amber lipid14/17:
- phospholipids POPC & POPS
- TIP3p water model
- cations and anions


Repository [MATCH](https://github.com/NMRLipids/MATCH) is often also employed 
as a data source and a tool with analysis scripts.

Parameters for ions are directly taken from 
a [repository collecting most of the available models.](https://bitbucket.org/hseara/ions/src/master/)


# published papers

+ [ECC-POPC](https://pubs.acs.org/doi/10.1021/acs.jpcb.7b12510) also available at [GitHub](https://github.com/ohsOllila/NMRlipids_VI-NewIonModel)

## related work

+ [NMRLipids projects](https://nmrlipids.blogspot.cz/)
   + [proj. II: lipid-ion interaction](https://github.com/NMRLipids/lipid_ionINTERACTION), 
      published in PCCP, 2017, DOI: [10.1039/C6CP04883H](https://pubs.rsc.org/en/content/articlelanding/2016/cp/c6cp04883h#!)
   + [proj. IV](https://github.com/NMRLipids/NMRlipidsIVotherHGs) 

+ [MD in electronic continuum (MDEC)](http://scitation.aip.org/content/aip/journal/jcp/130/8/10.1063/1.3060164) and a [follow-up paper](http://dx.doi.org/10.1021/ct9005807)


