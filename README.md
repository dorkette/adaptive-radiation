# adaptive-radiation
copy of the supplemental material from "Adaptive Radiation in Resource Competition in Digital Organisms" by Chow, Wilke, Ofria, Lenski and Adami, Science (2004)

original README, slightly edited for readability and clarity, follows:

Source code in source/

The Avida source code (version 1.99) used in the experiments is
available in the source/avida/ directory.

The clustering source code is in the source/clustering directory.

\\

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

/ecosystem_invasion
invasion experiments -- specialists from inflow 100000 replicates
are competed against an ecosystem evolved at inflow 1000
