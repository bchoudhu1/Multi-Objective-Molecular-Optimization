For the Microbiome Modulator Notebook, REINFORCE + GRU Conditional Generator is used for data-constrained setting.

For the Multi-Objective Molecular Property Optimization notebook, PPO + GRU Conditional Generator is used with molecular properties learnt from RDKit, 
but one can easily adapt the reward-function to a molecular-property estimator trained on quantum chemistry datasets.

The approach can be a more data-efficient layer prior to VAE based methods(population encoder + SMILES decoder) 
as evident across other genome-expression->small molecule perturbation based workflows.
