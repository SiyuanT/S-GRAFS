# S-GRAFS
This is a demo script for the assimilating satellite soil moisture data into an API model for soil moisture reanlaysis. Sample data are provided for the cosmoz sites and the location of those points are described in cosmoz_site_info.csv
The forcing data are GPM rainfall and air temperature anomalies and the parameters were calibrated and included in API_parameters.csv.
The assimilated data is the satellite soil moisture data from 2019 - 2020
The model for surface soil moisture is a simple API model and the root-zone soil moisture is derived from an exponential filter
