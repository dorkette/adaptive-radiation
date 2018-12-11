# adaptive-radiation
This is a copy of the supplemental material from "Adaptive Radiation in Resource Competition in Digital Organisms" by Chow, Wilke, Ofria, Lenski, and Adami, published in Science (2004)

I am the "Chow" in the author list, and wrote the clustering source code. The source code of the version of Avida used in our experiments is included as part of the supplemental material, but I am not its author. For the newest version of Avida, [find it on github](https://github.com/devosoft/avida) or [check out its website](http://avida.devosoft.org/).

The clustering algorithm uses as a distance measure the number of steps separating one organism from another on the phylogenetic tree; since the digital organisms are initialized as a clonal population, this is straightforward to calculate.

The original README file for the supplementary material, slightly edited for readability and clarity, follows:

Source code in source/

The Avida source code (version 1.99) used in the experiments is
available in the source/avida/ directory.

The clustering source code is in the source/clustering directory.



Experimental Setup in exp-setup/

The experiment configuration files, sorted by experiment, are in the
exp-setup/ directory. The config/ subdirectory of each experiment
contains the files required by avida. The run_list file is a script to
run the experiments on the Beowulf cluster at the Center for Microbial
Ecology at Michigan State University.

The experiments:

calibration/

experiments to calibrate the cutoff used by the species clustering algorithm

resources/

limited resource environment experiments

resources_long_runs/
limited resource environment experiments with inflows of 10 and 0.1,
with doubled duration to look at long term trends

freq_dependent_selection/

frequency dependent selection species invasion experiments -- one
species from an ecosystem tries to invade a population of the other
species in the ecosystem

ecosystem_invasion/
invasion experiments -- specialists from inflow 100000 replicates
are competed against an ecosystem evolved at inflow 1000
