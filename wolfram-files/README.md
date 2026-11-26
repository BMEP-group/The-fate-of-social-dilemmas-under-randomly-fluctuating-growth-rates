# Wolfram Files

The following directory contains all the Wolfram Mathematica files required to obtain the plots, graphs and figures for the main paper. Each of the directories here (Coexistence, Dominance and Bistability) contain a single Wolfram notebook that was used to obtain all the resources for the respective game. 



## Usage

While the scripts may be opened directly, in order to obtain some graphs it is required to setup the simulator, which is available separately, written in C++ for doing fast calculations. The scripts invoke the simulator, which can be used either remotely via 'ssh' (as it is currently left in the scripts), or locally, equivalent to invoking a program on host computer where the script is located.



The root directory has a single file 'definitions.nb', which merely shows how the simulator is used. 



## The output

The figures are saved as SVG files. Each of the three main directories contains a 'main' svg file, which is an Inkscape file that groups all the necessary graphs together. 



