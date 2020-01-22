# STEP

This is the supporting code for the manuscript:

**Investigating Sources of Inaccuracy in Wearable Optical Heart Rate Sensors**

Authors: Brinnae Bent1, Benjamin A. Goldstein2, Warren A. Kibbe2, Jessilyn P. Dunn1,2* /n
1Department of Biomedical Engineering, Duke University, Durham NC. /n
2Department of Bioinformatics and Biostatistics, Duke University, Durham NC. /n


* Import_Raw_Data_Merge_csv.Rmd - Writes large .csv that contains all data for all participants, devices, and activities
* Mixed_Effects_Models.Rmd - Mixed models and interaction effect models
* Signal_Lag_Rolling_Window.Rmd - Applies a rolling window over data and outputs a data frame with window length added as a column
* Signal_Lag_Analysis_Model.Rmd - Takes output from Signal_Lag_Rolling_Window.Rmd and performs same mixed effects models as in Mixed_Effects_Models.Rmd
* Power_Analysis.Rmd - calculations of sample size power
* Figures-Plotting_Parameters_Only.Rmd - GGplot code for how figures for paper were designed in R

For more details on Heart Rate Variability Analytics, see the Digital Biomarker Discovery Pipeline: https://github.com/Big-Ideas-Lab/DBDP
For more details on formatting Empatica E4 Signals, see: https://github.com/brinnaebent/Empatica_Data
