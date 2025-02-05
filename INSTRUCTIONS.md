# Instructions on how to reproduce our results:

1. Go to the optimization file on the BioUML server using one of the following links:<br>
   * [optimization](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/CYP2C9_losartan_metabolism/Data/Optimizations/optimization%20for%20initial%20model) of the parameters of the original model by [Karatza et al. (2020)](https://doi.org/10.1111/bcpt.13321),<br>
   * [optimization](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/CYP2C9_losartan_metabolism/Data/Optimizations/optimization%20for%20E-max%20model) of the E-max model parameters.

2. To start the optimization process, click the ”Start optimization process” button.
<br/><br/>
![start_optimization](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/start_optimization.png?raw=true)

3. After that, you will see an optimization progress bar with the values of the objective and penalty functions, as well as the number of completed evaluations.
<br/><br/>
![optimization_progress_bar](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/optimization_progress_bar.png?raw=true)

4. After the optimization process is completed, you will see a folder with the optimization results in the folder with the optimization files.
<br/><br/>
![optimization_result_folder](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/optimization_result_folder.png?raw=true)

5. In this folder you can find the following files:
<br/><br/>
![optimization_result_folder_opened](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/optimization_result_folder_opened.png?raw=true)

   * optimizationInfo - optimized values of the model parameters (given in Supplementary Table S8 for the original Karatza model and Supplementary Table S6 for the E-max model), values of the objective function (calculation deviation) and penalty function (in our case it is equal to 0, since we did not consider additional constraints on the model parameters), and the number of evaluations.
   ![optimizationInfo](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/optimizationInfo.png?raw=true)
   Note that in optimizationInfo for the original model by Karatza et al., you will have 3 values of the parameter _k_m_ for each experiment (i.e. for each genotype) since this parameter was considered as local in this optimization.
   ![local_k_m](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/local_k_m.png?raw=true)
   * Files whose names end with "plot" contain comparisons between the simulation results after optimization and the experimental data used for it. Such plots are provided for each experiment and can be found in our manuscript (Figure 3).
   ![plot](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/plot.png?raw=true)
   * Files whose names end with "chart" are similar to plots, but use a different programming format for use via Java script if needed.
   ![chart](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/chart.png?raw=true)
   * Files whose names end with "state" are in a special software format for using optimized values ​​in BioUML diagrams as individual states.<br>
   ![state](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/state.png?raw=true)
   * Files whose names end with "sr" contain numerical results of simulations and are used to create plots in BioUML.
   ![sr](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/Pictures%20of%20instructions/sr.png?raw=true)

6. The experimental data used for parameter fitting are available in tabular form at the links below:<br>
   * to optimize the parameters of the original model by [Karatza et al. (2020)](https://doi.org/10.1111/bcpt.13321) we used data from the work by [Yasar et al. (2002)](https://doi.org/10.1067/mcp.2002.121216) for 3 _CYP2C9_ genotypes: [_CYP2C9\*1/CYP2C9\*1_](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/CYP2C9_losartan_metabolism/Data/Experimental%20data/Yasar2002%20-%20ExpData_CYP2C9*1_CYP2C9*1), [_CYP2C9\2/CYP2C9\*2_](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/CYP2C9_losartan_metabolism/Data/Experimental%20data/Yasar2002%20-%20ExpData_CYP2C9*2_CYP2C9*2) and [_CYP2C9\*3/CYP2C9\*3_](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/CYP2C9_losartan_metabolism/Data/Experimental%20data/Yasar2002%20-%20ExpData_CYP2C9*3_CYP2C9*3):

   * to optimize the parameters  of the E-max model we used [data](https://sirius-web.org/bioumlweb/#de=data/Collaboration%20(git)/CYP2C9_losartan_metabolism/Data/Experimental%20data/Data%20for%20E-max%20model%20validation) from the works by [Kutumova et al. (2022)](https://doi.org/10.3389/fphys.2022.1070115) (for 0.886 and 0.954 k_block values) and by [Gradman et al. (1995)](https://doi.org/10.1161/01.hyp.25.6.1345) (for 0.1 k_block value):



