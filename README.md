# Mouse Temperature and Activity Analysis

This repository contains Python code for analyzing sex differences in core body temperature (CBT) and locomotor activity (LA) patterns in mice, including analyzing the effects of the estrous cycle in females. 

It demonstrates practical applications of time series techniques to biological data, making it suitable for:

- learning real-world applications of time series analysis methods including wavelet transforms, Dynamic Time Warping, and variance analysis applied to complex biological rhythms.
- learning how to identify and quantify sex differences in physiological data
- understanding methods for detecting and analyzing multiple nested biological rhythms (ultradian, circadian, and estrous cycles) in physiological data.

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
- `Fem Temp`: Core body temperature readings for female mice (f1-f13)
- `Male Temp`: Core body temperature readings for male mice (m1-m13)
- `Fem Act`: Locomotor activity counts for female mice
- `Male Act`: Locomotor activity counts for male mice

Each row represents a one-minute time point over 14 consecutive days.
Temperature is measured in degrees Celsius, and activity is measured in counts.

## Recommended Reading

- [Circadian and sex differences in core body temperature (PMC5301430)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5301430/)
- [Effects of the estrous cycle on temperature regulation (10.1186/s13293-022-00451-1)](https://bsd.biomedcentral.com/articles/10.1186/s13293-022-00451-1)
