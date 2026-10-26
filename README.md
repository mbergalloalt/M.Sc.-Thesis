# M.S.c Thesis
MATLAB scripts from my M.S.c Thesis "Discriminación de procesos de relajación y difusión en resonancia magnética nuclear unilateral" (_Discrimination of relaxation and diffusion processes in single-sided nuclear magnetic resonance_)
## Note on the FLINT algorithm
The FLINT algorithm (three-kernel inversion) is not currently included in this repository. If you need it, please contact me at **martibergallo@gmail.com** and I will be happy to share them with you. This section will be updated in the future.
## MATLAB Scripts

| Script | Figure number | Description |
|---|---|---|
| `figura_4_1_loop_D.m` | Fig. 4.1 | Simulation of individual CPMG decay rates varying D |
| `figura_4_2_loop_TE.m` | Fig. 4.2 | Simulation of individual CPMG decay rates varying TE |
| `figura_4_3_cpmg_til.m` | Fig. 4.3 | Simulation of thirty CPMG signals varying D and Laplace Inversion (ILT) |
| `figura_4_4_loop_D_tau2.m` | Fig. 4.4 | Simulation of STE signal and diffusion decay rate varying D and τ₂ simultaneously |
| `figura_4_5_error_D.m` | Fig. 4.5 | Error calculation in the estimation of D |
| `figura_5_1_mapa_4_poblaciones_2K.m` | Fig. 5.1 | D-T₂ map of 4 populations using the two-kernel model |
| `figura_5_2_mapa_4_poblaciones_2K_curva_T2ef.m` | Fig. 5.2 | D-T₂ map (2K) with overlaid effective T₂ curve |
| `figura_5_4_mapa_4_poblaciones_3K.m` | Fig. 5.4 | D-T₂ map of 4 populations using the three-kernel model |
| `figura_5_5_mapa_4_poblaciones_3K_curva_T2ef.m` | Fig. 5.5 | D-T₂ map (3K) with overlaid effective T₂ curve |
| `figura_5_6_mapa_con_proyección_y_FWHM.m` | Fig. 5.6 | D-T₂ map with projection and FWHM calculation |
| `figura_5_7_mapa_con_proyección_arriba.m` | Fig. 5.7 | D-T₂ map with top projection |
| `figura_5_8_grilla_valores_FWHM.m` | Fig. 5.8 | Grid of FWHM values over the parameter space |
## Scripts requiring external data
The scripts for Figures 5.6, 5.7, and 5.8 load data from a large-scale simulation that is not included in this repository due to file size limits. If you need to run these scripts, please contact me at **martibergallo@gmail.com** and I will share the dataset with you. In the future, I will upload this database to an external repository and update this README with the link.
