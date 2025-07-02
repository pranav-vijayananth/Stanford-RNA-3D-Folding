# Stanford-RNA-3D-Folding

The goal of this project is to predict RNA 3D structures based on sequences and machine learning models.

## Evaluation 

To evaluate my model, I will be using the TM-score ("template modeling" score) which ranges from 0.0 to 0.10: 

<pre> TM-score = max (1 / L_ref) * ∑_{i=1}^{L_align} [1 / (1 + (d_i / d_0)^2)] </pre>


