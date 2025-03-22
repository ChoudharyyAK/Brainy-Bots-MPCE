# MPCE - Monthly Per Capita Consumption Expenditure

**Authors:** 
Akshit Choudhary, Disha Shimpi, Manthan Hirani, Mihir Modi, Aditya Trivedi

The Household Consumption Expenditure Survey (HCES) collects data on household consumption patterns, living standards, and demographics across India. Conducted in 2022-23, it covered 2,61,746 households from 8,723 villages and 6,115 urban blocks, helping derive economic indicators and Consumer Price Indices (CPIs).

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Data Pre-processing & Cleaning](#Data_Cleaning_&_Pre-processing)

## Overview
The Household Consumption Expenditure Survey (HCES) is designed to collect information
on consumption of goods and services by the households. The survey also collects some
auxiliary information on household characteristics and demographic particulars of the
members of the households. Information collected in HCES is useful for understanding the
consumption pattern, standard of living and hence, well-being of the households. Besides,
the data of the survey provides budget shares of different commodity groups that is used for
preparation of the weighting diagram for compilation of official Consumer Price Indices
(CPIs). The data collected in HCES is also utilized, inter-alia, for deriving various other
macroeconomic indicators. The survey covered the whole of the Indian Union except a few
inaccessible villages in the Andaman and Nicobar Islands. Conducted in 2022-23, HCES
collected information from 8,723 villages and 6,115 urban blocks spread over the entire
country covering 2,61,746 households (1,55,014 in rural areas and 1,06,732 in urban
areas). The survey also collected some auxiliary information on household characteristics
and demographic particulars of the members of the households in Questionnaire - HCQ:
Household Characteristics.

## Installation
1. Clone the repo:
   ```bash
   [git clone https://github.com/yourusername/projectname.git

## Data Pre-processing & Cleaning
1. Fill the Data in House hold(HH) data file
      - Fill the empty column starting with IS_online and Is_HH_Have with 0.

2. Fill the Data in Person data file
      - Fill the empty cell of different columns with median, mode and 0 considering the better approach.
      - WE fill the column 'Total year of education completed' using XGBOOST.
