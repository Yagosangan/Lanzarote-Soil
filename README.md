# Lanzarote-Soil

## Statistical analysis of soil data from the arid island of Lanzarote

This project is an exploratory statistical analysis of more than 600 soil samples extracted from the island of Lanzarote, in the Canarian archipelago, throughout multiple
field campaigns between September 2010 and September 2016.

The exploration is developed in the R language, saving the whole process in R markdown documents. The document "Lanzarote Soil - Main" contains the principal analysis procedure. It is supported by the functions implemented in "Lanzarote Soil - Functions", which the main document access at the start using the "source" command (local path to the file must be manually introduced).

Currently, the principal function is "variable_exploration", which takes the variables of the dataframe one by one and generates a pdf document as the output, containing multiple  exploratory techniques. It is still under development, and will be improved with more tools and commands. The outputs of the function applied to every variable can be found in the (name of the file) file.

Nevertheless, the original data is not included due to license reasons.
