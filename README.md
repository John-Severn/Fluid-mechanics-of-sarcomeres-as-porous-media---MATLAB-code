"Compute_Darcy_flow_and_plot_heatmap" calculates the dimensionless Darcy flow in a sarcomere with a specified packing ratio, filament lengths, radius, and percentage contraction. The file "bessel_zeros" must be loaded before running. All coefficients of Eq. (16) are computed, and the solution for fluid flow and pressure is evaluated at a specified number of radial and axial points. A heatmap of the results is then plotted, as seen in Fig. 3A.

"Calculate_Darcy_grid_deformation" calculates the dimensionless Darcy flow at varying levels of contraction, determining the advective motion of marked fluid parcels in a grid pattern, whose size is given by the variables "r_grids" and "z_grids". "precision" determines the number of marked fluid parcels per grid square, whilst "contraction_precision" determines the size of the contraction steps. "bessel_zeros" must be loaded before running. A video of the grid deformation is automatically generated.

"Plot_grid_deformation" plots the deformation calculated by "Calculate_Darcy_grid_deformation" for a specified contraction.

"Plot_comsol_heatmap" plots COMSOL data in a heatmap, reproducing Fig. 3B. Some COMSOL data from the data folder must be loaded before running.

"Compare_fixed_r_varying_z" compares the radial flux between the Darcy model and COMSOL data, requiring "bessel_zeros" and the appropriate COMSOL data to be loaded first. This code can reproduce Fig. 3C.

"Compare_fixed_z_varying_r" compares the axial flux between the Darcy model and COMSOL data, requiring "bessel_zeros" and the appropriate COMSOL data to be loaded first. This code can reproduce Fig. 4.
