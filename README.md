# HDCZA Sleep State Detection

This repository implements the Heuristic Algorithm based on the Distribution of Change in Z-angle (HDCZA) method for detecting sleep states from accelerometer data, as proposed in the paper ["Estimating sleep parameters on accelerometer without sleep diary"](https://www.nature.com/articles/s41598-018-31266-z). The method was applied to the dataset from the Detect Sleep States Kaggle challenge hosted by the Child Mind Institute.

## Overview

Sleep state detection using accelerometer data is challenging, especially without traditional sleep diaries. The HDCZA method analyzes changes in the Z-angle of the accelerometer signal to estimate sleep parameters. It leverages variations in the Z-axis acceleration to classify sleep states, with the key insight that the arm angle varies less during sleep than when awake. To accommodate different lifestyles, the method uses a percentile-based threshold, offering flexibility for individuals with varying activity levels.

## Dataset

The data used in this project comes from the [Detect Sleep States Kaggle Challenge](https://www.kaggle.com/competitions/child-mind-institute-detect-sleep-states) hosted by the Child Mind Institute. It includes accelerometer data from wearable devices that capture movement patterns to infer sleep states.

## Usage
Code can be run directly through the jupyter notebook

## Acknowledgments

- The dataset used in this project is from the Detect Sleep States Kaggle challenge hosted by the Child Mind Institute.
- The HDCZA method is based on the work of [Authors from the paper "Estimating sleep parameters on accelerometer without sleep diary"](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8359864/).
