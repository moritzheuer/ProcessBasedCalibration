# Multi-variable process-based calibration of a behavioural hydrological model

This repository contains the used model together with the input data necessary for simulation runs of the study catchment `Riverisbach'.

The folder Control contains the control files for the model runs. Included are two controlfiles per used PTF: one for the spin up period and one for the main model run.

The folder Input contains the used climate data together with the grids (k_x, k_y, colmation, [...]) in binary format.

In order to run the model, Init-folder and Output-folder are necessary next to the control- and input-folder. Init-folders are named Init_1 to Init_12 with the number indicating the used PTF. This also applies to the Output-folder (Output_1 to Output_12).

For the model run, the included run.bat file can be started, which initialises WaSiM-model runs for all PTFs.
