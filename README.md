# EEF1-SB
This folder contains the distribution version of 'EEF1-SB'

This includes the three force field files (param, solvpar, top) defining
the force field, as well as an example input file for a fragment of 
hen lysozyme. *** Note that the non-bonded parameters are different
from those for the original EEF1. *** This is to make the 1-4 parameters
more consistent with the all-atom force field.



Files here:

eef1sb.inp			: example CHARMM input file. Note that the 
					nonbonded parameters are different 
					from the original C19 EEF1.
hewl19.psf			: psf for example
hewl19_random.pdb		: pdb for example
param_all36_eef1sb.prm		: EEF1SB parameter file
solvpar_eef1sb.inp		: EEF1SB solvation parameters
top_all36_prot_eef1sb.rtf	: EEF1SB topology file


Reference: 
@article{bottaro2013variational,
  title={Variational optimization of an all-atom implicit solvent force field to match explicit solvent simulation data},
  author={Bottaro, Sandro and Lindorff-Larsen, Kresten and Best, Robert B},
  journal={Journal of chemical theory and computation},
  volume={9},
  number={12},
  pages={5641--5652},
  year={2013},
  publisher={ACS Publications}
}
