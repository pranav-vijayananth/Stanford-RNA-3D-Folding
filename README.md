# Stanford-RNA-3D-Folding

The goal of this project is to predict RNA 3D structures based on sequences and machine learning models.

## Evaluation 

To evaluate my model, I will be using the TM-score ("template modeling" score) which ranges from 0.0 to 0.10: 

![TM-score formula](https://latex.codecogs.com/png.image?\dpi{120} \text{TM-score} = \max \left( \frac{1}{L_{\text{ref}}} \sum_{i=1}^{L_{\text{align}}} \frac{1}{1 + \left( \frac{d_i}{d_0} \right)^2 } \right))


