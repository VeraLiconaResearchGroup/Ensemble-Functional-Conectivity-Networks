# Individual and combined methods analysis

This subfolder contains the code and data for analyzing the networks created by the 40 single methods inmplemented in MULAN and molecular biology methods 


The code to perform the analysis can be found in  `analysis.Rmd`. An rmarkdown .html file is also found within this folder (`analysis.html`)

The `sim` subfolders contain the following files for each simulated network:

- Combined_Data_onlyAUC.csv: the area under the reciever operating characteristic (AUROC, abbreviated here as AUC) values for each method for the 50 time series simulations of the network calculated by MULAN
- Combined_Data_onlyACC.csv: the accuracy (ACC) values for each method for the 50 time series simulations of the network calculated by MULAN
- Combined_data_sums_onlyAUC: The Row Sums for each  method across the 50 simulated time series using the weight Weight_{AUC=1}, Weight_{ACC=0}
- Combined_data_sums_onlyACC: The Row Sums for each method across the 50 simulated time series using the weight Weight_{AUC=0}, Weight_{ACC=1}
- Combined_data_median_onlyAUC: The Median value for each method across the 50 simulated time series using the weight Weight_{AUC=1}, Weight_{ACC=0}
- Combined_data_median_onlyACC: The Row Sums value for each method across the 50 simulated time series using the weight Weight_{AUC=0}, Weight_{ACC=1}
- Combined_data_sums_equal: The Row Sums for each method across the 50 simulated time series using the weight Weight_{AUC=0.5}, Weight_{ACC=0.5}
- Combined_data_median_equal: The Median value for each method across the 50 simulated time series using the weight Weight_{AUC=0.5}, Weight_{ACC=0.5}
- Combined_data_sums_73: The Row Sums for each method across the 50 simulated time series using the weight Weight_{AUC=0.7}, Weight_{ACC=0.3}
- Combined_data_median_73: The Median value for each method across the 50 simulated time series using the weight Weight_{AUC=0.7}, Weight_{ACC=0.3}
- Combined_data_sums_37: The Row Sums for each method across the 50 simulated time series using the weight Weight_{AUC=0.3}, Weight_{ACC=0.7}
- Combined_data_median_37: The Median value for each method across the 50 simulated time series using the weight Weight_{AUC=0.3}, Weight_{ACC=0.7}

The `averages` subfolder contains the values of the averages for each method across all simulated networks for both the row sums and median values under the various weights of AUROC and ACC

The heatmap and lineplots that display the row sums and median values can be found in the main folder.
