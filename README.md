# Predicting-price-of-an-apartment-in-mexico-city
## Introduction
Mexico city is the capital and largest city of Mexico, and the most populous city in North America. This project is focused on predicting the prices of apartment in mexico using a linear regression model. The data was gotten from the World Quant Datascience Lab tutorial.
About the Dataset: The Dataset contains four(4) csv file which was cleaned & wrangled using a wrangle function. Columns in the dataset are;
                  Property_type,
                  Place_with_parent-names,
                  Surface_covered_in_m2,
                  lat-lon,
                  Expenses,
                  Floor,
                  surface_total_in_m2,
                  rooms,
                  Operation,
                  Currency,
                  Property_url,
                  price,
                  price_aprox_local_currency,
                  price_per_m2,
                  price_usd_per_m2
## Data Wrangling & Exploration
      A wrangle fnction was created for the wrangle process
      The four csv files were imported using the glob function
      The wrangle process was done iteratively and involves removing outliers, streamlining features, splitting columns, dropping features with highest null count,
      high and low cardinality and leaky features.

     
                   
                    
