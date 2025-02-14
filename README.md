# Affinity_MC-Gauss
This repo has some modifications of code for calculating affinity values by 2 options: 
    1) MC generation of non-perturbative parameters 
    2) Normal (Gaussian) distribution for non-perturbative parameters with the filter "k_it^2 - M_ki^2 > 0"


If you want to make calculations with MC generation you should go to the Folder "Affinity" -> "Affinity_CLAS12_values" -> driver

If you want to make calculations with Gaussian distributed parameters you should go to the Folder "Affinity" -> "Affinity_random_values" -> driver

In "driver" you can see what files it is using for calculations and in the defining of the function "gen_np_values(params,x,z,level,size=100)" (probably 5th 'line' in jupyter notebook) you can
see and change the file you are using for non-perturbative (MC or Gaussian generated) parameters.
