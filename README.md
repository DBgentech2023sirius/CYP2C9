# Mathematical modeling of pharmacokinetics and pharmacodynamics of losartan in relation to CYP2C9 allele variants
Pharmacokinetic [Model](https://uni.sirius-web.org:58443/bioumlweb/#de=data/Collaboration/Babaev_Dmitry_Sirius/Data/PK_2/final_model) that predicts plasma concentration-time curves of losartan and its metabolite E-3174 for patients with the most common alleles of the CYP2C9 gene: _CYP2C9\*1_, _CYP2C9\*2_, and _CYP2C9\*3_.

![Model](https://gitlab.sirius-web.org/DB_gentech2023_sirius/CYP2C9/-/raw/master/Pictures/схема_модели_BioUML_english.png)

You can download this model in different formats:
<ul>
<li><a id="raw-url" href="https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Model_for_download/CYP2C9_model_SBML.xml">SBML</a></li>
<li><a id="raw-url" href="https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Model_for_download/CYP2C9_model_BioUML.dml">BioUML format (*.dml)</a></li>
<li><a id="raw-url" href="https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Model_for_download/CYP2C9_model_SBGN_ML.xml">SBGN-ML</a></li>
<li><a id="raw-url" href="https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Model_for_download/CYP2C9_model_GraphML.graphml">GraphML (*.graphml)</a></li>
<li><a id="raw-url" href="https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Model_for_download/CYP2C9_model_COMBINE_archive.omex">COMBINE archive (*.omex)</a></li>
</ul>

___
### Experimental data [(Yasar et al., 2002)](https://ascpt.onlinelibrary.wiley.com/doi/10.1067/mcp.2002.121216) used for model validation are presented here:

_CYP2C9\*1/CYP2C9\*1_:

| Time (h) | Losartan (nM) | E-3174 (nM) |
| :---: | :---: | :---: |
|0.35|337.17|10.93|
|0.86|675.00|57.26|
|1.32|315.35|158.84|
|1.82|258.00|280.51|
|3.85|88.46|603.00|
|5.87|54.46|331.57|
|7.89|46.85|221.95|
|9.87|23.60|158.84|
|11.84|-|102.83|
|23.94|-|16.33|

_CYP2C9\*2/CYP2C9\*2_:

| Time (h) | Losartan (nM) | E-3174 (nM) |
| :---: | :---: | :---: |
|0.61|713.00|48.80|
|0.98|338.05|159.55|
|1.59|272.13|201.53|
|3.74|238.13|441.50|
|5.79|211.88|486.00|
|7.80|92.00|343.74|
|10.05|54.84|204.92|
|12.06|21.54|118.16|

_CYP2C9\*3/CYP2C9\*3_:

| Time (h) | Losartan (nM) | E-3174 (nM) |
| :---: | :---: | :---: |
|0.39|22.06|-|
|0.88|706.00|-|
|1.46|633.70|-|
|1.90|457.49|5.72|
|3.90|234.58|25.00|
|5.95|180.75|18.47|
|7.90|116.42|16.48|
|9.95|76.22|16.21|
|11.95|-|13.12|

___

### Pharmacokinetic parameters [(Yasar et al., 2002)](https://ascpt.onlinelibrary.wiley.com/doi/10.1067/mcp.2002.121216) used for model verification:

For losartan:
|Parameter|_CYP2C9\*1/CYP2C9\*1_<br>(n = 6)|_CYP2C9\*1/CYP2C9\*2_<br>(n = 3)|_CYP2C9\*1/CYP2C9\*3_<br>(n = 5)|_CYP2C9\*2/CYP2C9\*2_<br>(n = 3)|_CYP2C9\*2/CYP2C9\*3_<br>(n = 4)|_CYP2C9\*3/CYP2C9\*3_<br>(n = 1)|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| C<sub>max</sub> (nM)<br>Mean±SD<br>Range | 675 ± 417<br>328-1404 | 731 ± 489<br>208-1178 | 353 ± 160<br>148-596 | 713 ± 423<br>448-1201 | 635 ± 388<br>213-1062 | 706<br>- |
| t<sub>1/2</sub> (h)<br>Mean±SD<br>Range | 1.9 ± 0.6<br>1.2-2.9 | 2.1 ± 0.4<br>1.6-2.5 | 2.4 ± 0.5<br>1.9-3.2 | 2.0 ± 0.6<br>1.3-2.5 | 3.0 ± 0.6<br>2.2-3.5 | 3.6<br>- |
| AUC<sub>total</sub> (nmol*h/L)<br>Mean±SD<br>Range | 1697 ± 1061<br>522-3373 | 1521 ± 850<br>750-2432 | 1249 ± 248<br>925-1572 | 1912 ± 438<br>1419-2254 | 2006 ± 632<br>1269-2639 | 2769<br>- |

For E-3174:
|Parameter|_CYP2C9\*1/CYP2C9\*1_<br>(n = 6)|_CYP2C9\*1/CYP2C9\*2_<br>(n = 3)|_CYP2C9\*1/CYP2C9\*3_<br>(n = 5)|_CYP2C9\*2/CYP2C9\*2_<br>(n = 3)|_CYP2C9\*2/CYP2C9\*3_<br>(n = 4)|_CYP2C9\*3/CYP2C9\*3_<br>(n = 1)|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| C<sub>max</sub> (nM)<br>Mean±SD<br>Range | 603 ± 443<br>282-1451 | 763 ± 565<br>384-1412 | 241 ± 102<br>108-369 | 486 ± 210<br>256-669 | 179 ± 39<br>144-217 | 25<br>- |
| t<sub>1/2</sub> (h)<br>Mean±SD<br>Range | 4.0 ± 1.1<br>2.7-5.9 | 4.3 ± 0.2<br>4.1-4.3 | 5.6 ± 1.0<br>4.5-7.0 | 3.8 ± 1.2<br>2.9-5.2 | 6.1 ± 1.6<br>4.4-7.6 | 6.8<br>- |
| AUC<sub>total</sub> (nmol*h/L)<br>Mean±SD<br>Range | 4346 ± 2584<br>2162-9183 | 5564 ± 3505<br>3355-9605 | 2753 ± 898<br>1446-3740 | 4104 ± 2097<br>1931-6116 | 2134 ± 491<br>1749-2849 | 312<br>- |
|AUC<sub>Losartan</sub>/AUC<sub>E-3174</sub>| 0.3 ± 0.1<br>0.2-0.5 | 0.3 ± 0.1<br>0.2-0.4 | 0.5 ± 0.2<br>0.3-0.8 | 0.6 ± 0.5<br>0.33-1.2 | 0.9 ± 0.4<br>0.5-1.3 | 8.9<br> |
___
### The initial [(Karatza and Karalis, 2020)](https://onlinelibrary.wiley.com/doi/10.1111/bcpt.13321) and final values of model parameters are presented below:
| Parameter | initial value | final value |
| :---: | :---: | :---: |
|_CL<sub>m</sub>_|5.500|16.456|
|_CL<sub>p</sub>_|184.000|30.401|
|_T_|0.271|0.819|
|_V<sub>m</sub>_|9.660|57.598|
|_V<sub>p1</sub>_|43.700|56.175|
|_V<sub>p2</sub>_|1160.000|135.63|
|_Q_|129.000|217.103|
|_a_|4.560|6.645|
|_k<sub>a</sub>_|1.930|5.127|

___
The time-dependent concentrations of losartan and E-3174 after a single oral dose of 50 mg losartan potassium for all _CYP2C9_ genotypes predicted by the model are shown below:

![concentration-time curves](https://gitlab.sirius-web.org/DB_gentech2023_sirius/CYP2C9/-/raw/master/Pictures/гомозиготы_with_one_legend_eng.png)
![h](https://github.com/DBgentech2023sirius/CYP2C9/blob/master/Pictures/heterozygotes_with_one_legend_eng.png?raw=true)

C_p - predicted profile of losartan;<br>
C_m - predicted profile of E-3174;<br>
C_p (exp.) - experimental time-course of losartan;<br>
C_m (exp.) - experimental time-course of E-3174.
___

### How to reproduce the data:
1. Fit the initial values of the model parameters according to the experimental data:
    * select one of the optimization methods and its settings;
    * select experimental data and corresponding model parameters<br> (_C<sub>p</sub>_ = Losartan concentration (nM))<br> (_C<sub>m</sub>_ = E-3174 concentration (nM));
    * select model parametrs, which values would be changed to approximate experimental data, and the borders, where the final value would be found;<br>set locality to the experiments for _k<sub>m</sub>_;
    * select initial, terminal simulation time and time increment for model simulation.
2. Apply new values of the model parameters, set _k<sub>m</sub>_ in different states of the model.
3. Repeat step 1, but now select appropriate state for each experiment and do not use _k<sub>m</sub>_ for optimization.
<div style="color: red">Please note that optimization methods are stochastic, consequently, values that differ from each other may be obtained at different runs!!!</div> 