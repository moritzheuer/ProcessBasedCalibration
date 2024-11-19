# Multi-variable process-based calibration of a behavioural hydrological model

This repository contains the used model together with the input data necessary for simulation runs of the study catchment `Riverisbach'.

The folder Control contains the control files for the model runs. Included are two controlfiles per used PTF: one for the spin up period and one for the main model run.

The folder Input contains the used climate data together with the grids (k_x, k_y, colmation, [...]) in binary format.

In order to run the model, Init-folder and Output-folder are necessary next to the control- and input-folder. Init-folders are named Init_1 to Init_12 with the number indicating the used PTF. This also applies to the Output-folder (Output_1 to Output_12).

For the model run, the included run.bat file can be started, which initialises WaSiM-model runs for all PTFs.

**Model folder structure**

```
Model/
├─ Control/
│  ├─ 01_controlfile
│  ├─ 01_controlfile_Vorlauf
│  ├─ 02_controlfile
│  ├─ 02_controlfile_Vorlauf
│  ├─ 03_controlfile
│  ├─ 03_controlfile_Vorlauf
│  ├─ 04_controlfile
│  ├─ 04_controlfile_Vorlauf
│  ├─ 05_controlfile
│  ├─ 05_controlfile_Vorlauf
│  ├─ 06_controlfile
│  ├─ 06_controlfile_Vorlauf
│  ├─ 07_controlfile
│  ├─ 07_controlfile_Vorlauf
│  ├─ 08_controlfile
│  ├─ 08_controlfile_Vorlauf
│  ├─ 09_controlfile
│  ├─ 09_controlfile_Vorlauf
│  ├─ 10_controlfile
│  ├─ 10_controlfile_Vorlauf
│  ├─ 11_controlfile
│  ├─ 11_controlfile_Vorlauf
│  ├─ 12_controlfile
│  ├─ 12_controlfile_Vorlauf
│  ├─ run.bat
│  ├─ wasimvcz64.exe
├─ Input/
│  ├─ ASCII
│  ├─ Luftfeuchte2014.dat
│  ├─ Niederschlag2014.dat
│  ├─ Strahlung2014.dat
│  ├─ Temperatur2014.dat
│  ├─ Wind2014.dat
│  ├─ Riveris.aq1
│  ├─ Riveris.art
│  ├─ Riveris.bh1
│  ├─ Riveris.bq1
│  ├─ Riveris.dgm
│  ├─ Riveris.exp
│  ├─ Riveris.ezg
│  ├─ Riveris.fzs
│  ├─ Riveris.kol
│  ├─ Riveris.kx
│  ├─ Riveris.ky
│  ├─ Riveris.lin
│  ├─ Riveris.s01
│  ├─ Riveris.slp
│  ├─ Riveris.use
│  ├─ Riveris.lnk
│  ├─ Riveris.wit
│  ├─ Riveris.zon
├─ Init_1/
├─ Init_2/
├─ Init_3/
├─ Init_4/
├─ Init_5/
├─ Init_6/
├─ Init_7/
├─ Init_8/
├─ Init_9/
├─ Init_10/
├─ Init_11/
├─ Init_12/
├─ Output_1/
├─ Output_2/
├─ Output_3/
├─ Output_4/
├─ Output_5/
├─ Output_6/
├─ Output_7/
├─ Output_8/
├─ Output_9/
├─ Output_10/
├─ Output_11/
├─ Output_12/

```


