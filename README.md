# Sales Forecasting: A Novel Ensemble Model by Combining LSTM, Facebook Prophet and Informer Model

# Introduction
This project is aim to make a novel model by combining LSTM, Facebook Prophet and Informer. And provide some help about Informer in field of sales forecasting.

# Enviorment
In this project, the experiments and the acquisition of the results were performed on Jupyter Notebook. Before running, please install required library by following command.

pip install pandas numpy matplotlib statsmodels scikit-learn torch tqdm prophet

# Files
## 5 ipynb files:

  data.ipynb is about preprocessing the original data.
  
  lstm1.0.ipynb is about the LSTM model.
  
  prophet.ipynb is about the Facebook Prophet model.
  
  informer.ipynb is about the Informer model.
  
  ensemble.ipynb is about the ensemble model.

## 7 CSV files:
  Iowa_Liquor_Sales.csv
  
  Iowa_Liquor_Sales_20230725.csv
  
  sales_data.csv
  
The first two files are the original data which process in data.ipynb and save as sales_data.csv after processing.

  fb_data.csv
  
  lstm_data.csv
  
  informer_data.csv
  
These three CSV files store the prediction results of Facebook Pprophet, LSTM and Informer respectively and will be create after running lstm1.0.ipynb, prophet.ipynb and informer.ipynb.

  ensemble_data.csv
  
This CSV file store the final prediction after ensemble Facebook Pprophet, LSTM and Informer.

## 2 folder:

  'Informer2020' is the open-source Informer model which is developed by Zhou et al(2021) and available from 'https://github.com/zhouhaoyi/Informer2020'
  
  'result' is store the some results which created by informer.ipynb.

# method of use

Run the ipynb files in order 'data.ipynb->lstm1.0.ipynb->prophet.ipynb->informer.ipynb->ensemble.ipynb'


