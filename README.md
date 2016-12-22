# TERMITE - An R script for fast reduction of LA-ICPMS data and its application to trace element measurements
## TERMITE software repository
### Simon A. Mischel, Regina Mertz-Kraus, Klaus Peter Jochum, Denis Scholz


This repository contains example files for the R script TERMITE. 


The user should download the file your_main_directory.zip and unzip the example file. 
Included is the script and the mandatory files and folders. <br>

A step by step guide (file: Step_by_step_Instruction_TERMITE.docx) for using the script is provided within the TERMITE repository.
It is advised that the users of TERMITE should read this instruction prior to the first use of TERMITE.


Content of the example file "your_main_directory.zip"

your_main_directory/ <br>
your_main_directory/TERMITE_linescan.r <br>
your_main_directory/TERMITE_spotscan.r <br>
your_main_directory/TERMITEScriptFolder/ <br>
your_main_directory/TERMITEScriptFolder/AtomGewIsoAbund_NIST.csv <br>
your_main_directory/TERMITEScriptFolder/Standards_GeoReM.csv <br>
your_main_directory/TERMITEScriptFolder/Auswertung_Skript_line_scan_TERMITE.r <br>
your_main_directory/TERMITEScriptFolder/Auswertung_Skript_spot_scan_TERMITE.r <br>
your_main_directory/TERMITEScriptFolder/.Rhistory <br>
your_main_directory/.Rhistory <br>
your_main_directory/Results/ <br>
your_main_directory/Results/LoD_ReferenceMaterial_your_sample_name_spotscan.pdf <br>
your_main_directory/Results/LoD_ReferenceMaterial_your_sample_name_spotscan.csv <br>
your_main_directory/Results/LoD_ReferenceMaterial_your_sample_name_linescan.pdf <br>
your_main_directory/Results/LoD_ReferenceMaterial_your_sample_name_linescan.csv <br>
your_main_directory/Results/Outlier_Test_your_sample_name_linescan.csv <br>
your_main_directory/Results/Outlier_Test_your_sample_name_spotscan.csv <br>
your_main_directory/Results/rawCountrate_your_sample_name_spotscan.pdf <br>
your_main_directory/Results/rawCountrate_your_sample_name_linescan.pdf <br>
your_main_directory/Results/Results_your_sample_name_linescan.csv <br>
your_main_directory/Results/Results_your_sample_name_linescan.pdf <br>
your_main_directory/Results/Results_your_sample_name_spotscan.csv <br>
your_main_directory/Results/Results_your_sample_name_spotscan.pdf <br>
your_main_directory/Results/RSFused_your_sample_name_linescan.pdf <br>
your_main_directory/Results/RSFused_your_sample_name_linescan.csv <br>
your_main_directory/Results/RSFused_your_sample_name_spotscan.pdf <br>
your_main_directory/Results/RSFused_your_sample_name_spotscan.csv <br>
your_main_directory/Results/SD_your_sample_name_spotscan.csv <br>
your_main_directory/Rawdata_linescan/ <br>
your_main_directory/Rawdata_linescan/HLK2_linescan_example_001.csv <br>
your_main_directory/Rawdata_spotscan/ <br>
your_main_directory/Rawdata_spotscan/HLK2_spotscan_example_001.csv <br>
your_main_directory/Rawdata_spotscan/HLK2_spotscan_example_002.csv <br>
your_main_directory/Rawdata_spotscan/HLK2_spotscan_example_003.csv <br>
your_main_directory/Rawdata_spotscan/HLK2_spotscan_example_004.csv <br>
your_main_directory/Rawdata_spotscan/HLK2_spotscan_example_005.csv <br>
your_main_directory/Rawdata_QCM/ <br>
your_main_directory/Rawdata_QCM/MACS3_QCM_example-001.asc <br>
your_main_directory/Rawdata_QCM/MACS3_QCM_example-002.asc <br>
your_main_directory/Rawdata_QCM/MACS3_QCM_example-003.asc <br>
your_main_directory/ReferenceMaterial_linescan/ <br>
your_main_directory/ReferenceMaterial_linescan/NIST612_linescan_example_001.csv <br>
your_main_directory/ReferenceMaterial_linescan/NIST612_linescan_example_002.csv <br>
your_main_directory/ReferenceMaterial_linescan/NIST612_linescan_example_003.csv <br>
your_main_directory/ReferenceMaterial_linescan/NIST612_linescan_example_004.csv <br>
your_main_directory/ReferenceMaterial_linescan/NIST612_linescan_example_005.csv <br>
your_main_directory/ReferenceMaterial_linescan/NIST612_linescan_example_006.csv <br>
your_main_directory/ReferenceMaterial_spotscan/ <br>
your_main_directory/ReferenceMaterial_spotscan/MACS3_spotscan_example_001.csv <br>
your_main_directory/ReferenceMaterial_spotscan/MACS3_spotscan_example_002.csv <br>
your_main_directory/ReferenceMaterial_spotscan/MACS3_spotscan_example_003.csv <br>
your_main_directory/ReferenceMaterial_spotscan/NIST612_spotscan_example_001.csv <br>
your_main_directory/ReferenceMaterial_spotscan/NIST612_spotscan_example_002.csv <br>
your_main_directory/ReferenceMaterial_spotscan/NIST612_spotscan_example_003.csv <br>
your_main_directory/ReferenceMaterial_spotscan/NIST612_spotscan_example_004.csv <br>
your_main_directory/ReferenceMaterial_spotscan/NIST612_spotscan_example_005.csv <br>
your_main_directory/ReferenceMaterial_spotscan/NIST612_spotscan_example_006.csv <br>
