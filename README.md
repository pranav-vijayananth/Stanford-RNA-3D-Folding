# Stanford-RNA-3D-Folding

The goal of this project is to predict RNA 3D structures based on sequences and machine learning models.

## Evaluation 

To evaluate my model, I will be using the TM-score ("template modeling" score) which ranges from 0.0 to 0.10: 

TM-score = max (1 / L_ref) × Σᵢ₌₁^L_align [1 / (1 + (dᵢ / d₀)²)]

where: 
- L_ref is the ground truth
- L_align is the number of aligned residues
- d_i is the distance of the i_th pair of aligned residues, in Angstroms
- d_0 is a distance scaling factor in Angstroms, defined as:
  d_0 = 0.6 (L_{\text{ref}} - 0.5)^{1/2}  - 2.5 


