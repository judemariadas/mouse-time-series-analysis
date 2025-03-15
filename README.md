# Mouse Temperature and Activity Analysis

This repository contains Python code for analyzing sex differences in core body temperature (CBT) and locomotor activity (LA) patterns in mice, including analyzing the effects of the estrous cycle in females.

## Overview

The analysis explores biological time series data using various techniques including:
- Exploratory data analysis of temperature and activity patterns
- Statistical comparison of variability between sexes
- Estrous cycle effects on physiological patterns
- Wavelet transforms to identify periodic rhythms
- Dynamic Time Warping to quantify pattern similarities

## Requirements

- Python 3.6+
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- pywt (PyWavelets)
- dtaidistance

## Data Description

The `Mouse_Data_Student_Copy.xlsx` file contains the following sheets:
- `Fem Temp`: Core body temperature readings for female mice (f1-f15)
- `Male Temp`: Core body temperature readings for male mice (m1-m15)
- `Fem Act`: Locomotor activity counts for female mice
- `Male Act`: Locomotor activity counts for male mice

Each row represents a one-minute time point over 14 consecutive days.
Temperature is measured in degrees Celsius, and activity is measured in arbitrary counts.

## Recommended Reading

- [Circadian and sex differences in core body temperature (PMC5301430)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5301430/)
- [Effects of the estrous cycle on temperature regulation (10.1186/s13293-022-00451-1)](https://bsd.biomedcentral.com/articles/10.1186/s13293-022-00451-1)