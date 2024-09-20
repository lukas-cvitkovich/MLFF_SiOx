# MLFF_SiOx
This repository contains the interatomic machine learning force field (MLFF) suitable for the dynamic oxidation of silicon. You are free to use the MLFF for non-commercial use. If you do, please cite [1] or the according publication in the Journal of Chemical Physics (to be published)

# For use in LAMMPS:
pair_style	quip
pair_coeff	* * GAP_SiOx_v1.0.xml "Potential xml_label=GAP_2023_9_18_120_4_5_0_872" 1 8 14


# Reference:
[1]: https://arxiv.org/abs/2405.13635
