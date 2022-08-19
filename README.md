# dm-b_scat
#### 'all_functions_for_Mij_and_Delta_f.ipynb':
Contains all relevant functions (with comments), and is imported by the other jupyter notebooks.

#### 'figures_of_Gamma_ij.ipynb':
Calculates the time-invariant differential scattering rate, $\widetilde\Gamma_{ij}$, and the 
scattering matrix $M_{ij}$ (eq. (47) in Gandhi & Ali-Haïmoud (2022)). This nb can be used to 
generate Figure 1 in our paper.

#### 'figures_of_Delta_f_evolution.ipynb':
Has the code for calculating the evolution of the DM velocity distribution. It can be used
to generate Figure 2 in Gandhi & Ali-Haïmoud (2022).

#### 'FIG2_QFP_n=024_mchims=3e1_1e1_3e0_1e0_3.3e-1_1e-1_3.3e-2_1e-2_dlnxFP=0.002.npy':
Binary file that contains data for heat-exchange rates calculated in the FP approximation. 
Generated using code from Ali-Haïmoud (2019). This file is used to make Figure 2 in our paper,
and is called in 'figures_of_Delta_f_evolution.ipynb'
