# Supporting information for the Neural networks for operational SYM-H forecasting using attention and SWICS plasma features paper

The repository contains the predictions made by the four models and the two extra scenarios

## Authors

- Armando Collado-Villaverde (Universidad de Alcalá)
- Pablo Muñoz (Universidad de Alcalá)
- Consuelo Cid (Universidad de Alcalá)

--------------------------------
## Files and directories


- metrics_and_plots.ipynb: Main Jupyter notebook, used to create the tables and plots used on the paper

- supporting_information/: Directory for the supporting information tex source file and pdf

- supporting_information/paper_plots/: Directory with the plots used in the paper and the supporting information document

- rmses.csv: CSV file with the RMSE metrics for the predictions made Iong et al. GBM model (https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1029/2021SW002928), Siciliano et al. LSTM Model (https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020SW002589), the Burton equation (https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/1998JA000437), our previous work (https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1029/2021SW002748) and the persistence model

- predictions_SYM-H_1hour_swepam_real_time: SYM-H index one hour ahead forecasts made by the model trained only with SWEPAM data in operational conditions. 

- predictions_SYM-H_2hour_swepam_real_time: SYM-H index two hours ahead forecasts made by the model trained only with SWEPAM data in operational conditions. 

- predictions_SYM-H_1hour_swics_real_time.csv: SYM-H index one hour ahead forecasts made by the model trained only SWEPAM and SWICS data in operational conditions. 

- predictions_SYM-H_2hour_swics_real_time.csv: SYM-H index two hours ahead forecasts made by the model trained only SWEPAM and SWICS data in operational conditions. 

- predictions_SYM-H_1hour_swics.csv: SYM-H index one hour ahead forecasts made by the model trained with SWEPAM and SWICS data in laboratory conditions.

- predictions_SYM-H_2hour_swics.csv: SYM-H index two hours ahead forecasts made by the model trained with SWEPAM and SWICS data in laboratory conditions.
